# Blazor WPF Application

A sample application demonstrating how to embed Blazor components inside a WPF (Windows Presentation Foundation) desktop application using the `Microsoft.AspNetCore.Components.WebView.Wpf` package.

## Overview

This project showcases the integration of Blazor's component-based UI model with traditional WPF applications. It displays a data grid of sample orders using Syncfusion Blazor components, providing a modern web-inspired interface within a native desktop window.

## Features

- **Blazor-WebView Integration** — Hosts Blazor content directly inside WPF using `BlazorWebView`
- **Data Grid** — Displays data with the feature-rich `SfGrid` component
- **Razor Components** — Leverages .razor files for modular UI development
- **.NET 8.0** — Built on the latest stable .NET runtime for Windows

## Prerequisites

- [.NET 8.0 SDK](https://dotnet.microsoft.com/download/dotnet/8.0) or later
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
- [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone and Build

```bash
git clone https://github.com/SyncfusionExamples/blazor-with-wpf.git
cd blazor-wpf/blazor-with-wpf/WPF_Grid
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```

## References

- [Microsoft Blazor WebView for WPF](https://docs.microsoft.com/aspnet/core/blazor/webview/)
- [Getting Started with WPF Blazor App](https://help.syncfusion.com/staging/documentation/getting-started/wpf-blazor-app)
