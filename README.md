# How to hide the expand and collapse button in WPF Pivot Grid

This sample demonstrates how to hide the expand and collapse buttons in the Syncfusion WPF Pivot Grid control.

The sample uses custom header cell styles to display the header text without the default expand/collapse indicator in the row and column headers.

## Project workflow

1. Open the solution file: `How to hide the expand and collapse button in WPF Pivot Grid/PivotGridCustomization.sln`
2. Build and run the project in Visual Studio.
3. The WPF Pivot Grid will load sample sales data and display the header cells without the expand/collapse button.

## Sample details

The application does the following:

- Assigns a sample `ItemSource` for the WPF Pivot Grid.
- Adds `Product` and `Year` as row fields.
- Adds `Country` and `State` as column fields.
- Adds `Amount` and `Quantity` as pivot calculations.
- Applies custom `RowHeaderCellStyle` and `ColumnHeaderCellStyle` to hide the expand/collapse button.

## Key files

- `How to hide the expand and collapse button in WPF PivotGrid/PivotGridCustomization/MainWindow.xaml`
- `How to hide the expand and collapse button in WPF PivotGrid/PivotGridCustomization/MainWindow.xaml.cs`
- `How to hide the expand and collapse button in WPF PivotGrid/PivotGridCustomization/PivotGridCustomization.csproj`

## Requirements

- Visual Studio 2017 or later
- .NET Framework 4.5 or later
- Syncfusion WPF controls

## Support

If you require any assistance, please contact our [Syncfusion support team](https://support.syncfusion.com/).
