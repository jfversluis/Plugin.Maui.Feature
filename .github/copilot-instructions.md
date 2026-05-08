# Plugin.Maui.Feature - Copilot Instructions

## Project Overview

This is a template repository for bootstrapping new .NET MAUI plugins. It targets Android, iOS, macOS (Catalyst), and Windows.

## Architecture

**Template repo** - clone and rename to create a new plugin.

Standard structure with `IFeature` interface, static facade, and platform stubs.
Find/replace `Feature` with your plugin name to get started.

## Code Conventions

### Namespace
All code uses: `Plugin.Maui.Feature`

### File Naming
- `*.shared.cs` - Cross-platform code
- `*.android.cs` - Android-specific code
- `*.macios.cs` - iOS/macOS-specific code
- `*.windows.cs` - Windows-specific code
- `*.net.cs` - Generic .NET fallback

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
