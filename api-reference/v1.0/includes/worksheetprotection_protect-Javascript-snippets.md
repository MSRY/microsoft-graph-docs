
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

const protect = {
  options: {
    allowFormatCells: true,
    allowFormatColumns: true,
    allowFormatRows: true,
    allowInsertColumns: true,
    allowInsertRows: true,
    allowInsertHyperlinks: true,
    allowDeleteColumns: true,
    allowDeleteRows: true,
    allowSort: true,
    allowAutoFilter: true,
    allowPivotTables: true
  }
};

let res = await client.api('/me/drive/items/{id}/workbook/worksheets/{id|name}/protection/protect')
	.post(protect);

```