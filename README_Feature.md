# Plugin.Maui.Feature

`Plugin.Maui.Feature` provides the ability to do this amazing thing in your .NET MAUI application.

## Getting Started

* Available on NuGet: <http://www.nuget.org/packages/Plugin.Maui.Feature> [![NuGet](https://img.shields.io/nuget/v/Plugin.Maui.Feature.svg?label=NuGet)](https://www.nuget.org/packages/Plugin.Maui.Feature/)

## API Usage

`Plugin.Maui.Feature` provides the `Feature` class that has a single property `Brightness` that you can get or set.

You can either use it as a static class, e.g.: `Feature.Default.Property = 1` or with dependency injection: `builder.Services.AddSingleton<IFeature>(Feature.Default);`