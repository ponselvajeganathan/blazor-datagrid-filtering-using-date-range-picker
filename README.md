# Blazor DataGrid - Filtering Using Date Range Picker

## Overview

This sample demonstrates how to integrate a Date Range Picker into the Syncfusion Blazor DataGrid filter menu and use the selected range to filter date values. Instead of filtering by a single date, users can choose a start date and end date and apply filtering using a between-style operation. This approach provides a more intuitive filtering experience for scenarios where records must be filtered within a specific date period.

## Key Features

- Demonstrates a Syncfusion Blazor DataGrid filtering scenario focused on date values.
- Renders a Date Range Picker component within the Grid filter menu.
- Applies filtering based on a selected start and end date range.
- Uses a between-style filtering operation to return records that fall within the selected date interval.
- Customizes the default filter menu experience to support date-range-based filtering.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the solution file located inside the `DateRangePickerFiltering` project folder.
3. Restore all NuGet packages.
4. Set the appropriate startup project from the solution if required.
5. Build the solution.
6. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the project directory located inside the `DateRangePickerFiltering` folder.

```bash
dotnet restore
dotnet run
```

4. Open the local application URL displayed in the terminal after the application starts.

## Project Structure

- `DateRangePickerFiltering/Pages/` — contains the page that renders the Grid and custom filter menu implementation. 

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For feature documentation, see the Syncfusion Blazor DataGrid filtering documentation: https://help.syncfusion.com/grid-sdk/blazor/data-grid/filtering

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.