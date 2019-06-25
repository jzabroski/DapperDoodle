# DapperDoodle
.NET Reporting framework

## Competitors

From Gembox.Spreadsheet documentation:

> ## Clean and easy to use API
> GemBox.Spreadsheet is a designed and developed to conform to Microsoft standards for .NET libraries. Caching also enables you to access the worksheet in a more natural way. For example, the same task of changing cell text orientation would be one line in GemBox.Spreadsheet:
> 
> ```c#
> ws.Cells[6, 0].Style.Rotation = 30;
> ```
> 
> and three lines in one of the competing products:
> 
> ```c#
> XLStyle someStyle = new XLStyle(book);
> someStyle.Rotation = 30;
> sheet[6, 0].Style = someStyle;
> ```
>
> The latter is a hassle and forces you to think about Excel’s unique cell style limit. In other words, you will have to pay attention to not creating the same cell style again in a more complex worksheet.
