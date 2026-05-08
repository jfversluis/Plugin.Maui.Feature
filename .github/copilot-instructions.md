# $ Copilot InstructionsREPO 

## Project Overview

This is a .NET MAUI plugin that is a template repository for bootstrapping new .NET MAUI plugins. It targets Android, iOS, macOS (Catalyst), Windows.

### Architecture

**Template  clone and rename to create a new plugin.repo** 

Standard structure with IFeature interface, static facade, platform stubs.
Find/replace 'Feature' with your plugin name to get started.

## Code Conventions

### Namespace
All code uses: `Plugin.Maui.Feature`

### File Naming
- `*.shared. Cross-platform codecs` 
- `*.android. Androidcs` 
- `*.macios. iOS/macOScs` 
- `*.windows. Windowscs` 
- `*.net. Generic .NET fallbackcs` 

### Standards
- File-scoped namespaces
- `camelCase` for private fields, `PascalCase` for public
- XML docs required on all public APIs
- Null-conditional operators for platform interop

## Building

```bash
dotnet build src/Plugin.Maui.Feature/Plugin.Maui.Feature.csproj -c Release
```

## When Making Changes
1. Ensure the plugin builds on all target platforms
2. If adding public API, update the interface
3. Implement on all supported platforms
4. Update sample app and README
