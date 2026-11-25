# Master-Details View with Blazor DataGrid

A Blazor server application that demonstrates how to build a hierarchical master-details view using the [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) component.

## Overview

This project provides a complete example of implementing a master-details relationship using two synchronized Blazor DataGrid components. When you select a customer from the master grid, the details grid automatically updates to show all orders associated with that customer. This pattern is commonly used in business applications to display hierarchical data in an intuitive, interactive way.

## Features

- **Master-details relationship** — Select a customer in the master grid to view their orders
- **Event-driven synchronization** — Real-time binding between grids using row selection events
- **Sample data** — Pre-populated with customer and order information
- **Responsive design** — Clean layout with Bootstrap styling
- **Blazor Server** — Full server-side rendering with interactive components

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2026](https://visualstudio.microsoft.com/downloads/) or [Visual Studio Code](https://code.visualstudio.com/)

## Run with Visual Studio

**Visual Studio 2026**:

* Checkout this project to a location in your disk.
* Open the project (`Master-Detail-Grid.csproj`) file.
* Restore the NuGet packages.
* Run the project.

**Visual Studio Code**:

* Checkout this project to a location in your disk.
* Open the repository folder in Visual Studio Code.
* Open the integrated terminal.
* Navigate to the repository root.

```bash
cd create-master-details-view-using-blazor-datagrid
dotnet restore
dotnet run
```

Open the URL displayed in the terminal after the application starts.

## References

**Online example**: https://blazor.syncfusion.com/demos/datagrid/master-details?theme=fluent2