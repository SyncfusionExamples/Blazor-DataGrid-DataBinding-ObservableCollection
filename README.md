# Blazor DataGrid - DataBinding with ObservableCollection

## Overview

This sample demonstrates how to bind a Syncfusion Blazor DataGrid to an `ObservableCollection` data source. The implementation shows how collection-level changes are automatically reflected in the grid when items are added to or removed from the underlying data source. This approach is useful for applications that need to keep the UI synchronized with dynamic in-memory data without manually rebinding or refreshing the DataGrid after every collection update.

## Key Features

- Uses the Syncfusion Blazor DataGrid as the primary data presentation component.
- Binds the grid data source to an `ObservableCollection`, enabling automatic UI updates when the collection changes.
- Demonstrates notification-based data updates for create and delete operations performed on the underlying collection.
- Uses strongly typed data models from the project's `Data` folder to populate grid records.

## Prerequisites

* Visual Studio 2022  or Visual Studio Code

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open `BindWithObservableCollection.sln` in Visual Studio 2022.
3. Restore the NuGet packages.
4. Build the solution.
5. Run the application.
6. Navigate to the page that hosts the Syncfusion Blazor DataGrid sample.
7. Perform record add or delete operations and observe how the grid automatically reflects changes made to the underlying observable collection.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the project directory.

```bash
dotnet restore
dotnet run
```

## Project Structure

- `Pages/` — Contains the page that renders and hosts the Syncfusion Blazor DataGrid sample.
- `Data/` — Contains the data model and observable collection source used by the grid.
- `Program.cs` — Configures application services and startup behavior for the Blazor application.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For DataGrid data binding documentation, see: https://help.syncfusion.com/grid-sdk/blazor/data-grid/data-binding/local-data#observable-collection

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
