# Blazor WPF Application

A sample application demonstrating how to embed [Blazor components](https://www.syncfusion.com/blazor-components) with an interactive WPF grid component inside a WPF (Windows Presentation Foundation) desktop application using the `Microsoft.AspNetCore.Components.WebView.Wpf` package and grid controls.

## Overview

This project demonstrates integration of Blazor's component-based UI with traditional WPF desktop applications. It showcases a data grid displaying order information, illustrating how modern web-inspired components work seamlessly within native Windows applications.

## Features

- **Blazor WebView Integration** — Seamlessly embeds Blazor components directly into WPF windows, enabling web-based UI composition within desktop applications
- **Component-Based Architecture** — Utilizes reusable Razor components for modular, maintainable UI development
- **Interactive Data Grid** — Features a responsive, feature-rich grid component that displays dynamically generated order data with support for multiple data columns and rows
- **Dependency Injection** — Implements proper service configuration using Microsoft's dependency injection system for managing Blazor and Syncfusion services
- **.NET 8.0 Windows Platform** — Built on the latest stable .NET runtime with full Windows desktop platform support

## Prerequisites

- [.NET 8.0 SDK](https://dotnet.microsoft.com/download/dotnet/8.0) or later
- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
- [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone and Build

```bash
git clone https://github.com/SyncfusionExamples/blazor-with-wpf.git
cd blazor-with-wpf
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

- [Getting Started with WPF Blazor App](https://blazor.syncfusion.com/documentation/getting-started/wpf-blazor-app)
- [WPF DataGrid Control ](https://learn.microsoft.com/en-us/dotnet/desktop/wpf/controls/datagrid)
