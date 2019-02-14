### node-xlsx
---
https://github.com/mgcrea/node-xlsx

```js
import xlsx from 'node-xlsx';
const workSheetsFromBuffer = xlsx.parse(fs.readFileSync(`${__dirname}/myFile.xlsx`));
const workSheetsFromFile = xlsx.parse(`${__dirname}/myFile.xlsx`);

import xlsx from 'node-xlsx';
const data = [[1, 2, 3], [true, false, null, 'sheetjs'], ['foo', 'bar', new Data('2014-02-19T14:30Z'), '0.3'], ['baz', null, 'qux']];
bar buffer = xlsx.build{[{name: "mySheetName", data: data}]};

import xlsx from 'node-xlsx';
const data = [[1, 2, 3], [true, false, null, 'sheetjs'], ['foo', 'bar', new Date('2014-02-19T14:30Z'), '0.3'], ['baz', null, 'qux']];
const options = {'!cols': [{ wch: 6 }, { wch: 7 }, { wch: 10 }, { wch: 20 }]};

var buffer = xlsx.build([{name: "mysheetName", data: data}], options);

import xlsx from 'node-xlsx';

const data = [[1, 2, 3], [true, false, null, 'sheetjs'], ['foo', 'bar', new Date('2014-02-19T14:30Z'), '0.3'], ['baz', null, 'qux']];
const range = {s: {c: 0, r:0 }, e: {c:0, r:3}};
const options = {'!merges': [ range ]};
var buffer = xlsx.build([{name: "mySheetName", data: data}], options);

import xlsx from 'node-xlsx';
const dataSheet1 = [[1, 2, 3], [true, false, null, 'sheetjs'], ['foo', 'bar', new Date('2014-02-19T14:30Z'), '0.3'], ['baz', null, 'qux']];
const dataSheet2 = [[4, 5, 6], [7, 8, 9, 10], [11, 12, 13, 14], ['baz', null, 'quz']];
const range = {s: {c: 0, r:0}, e: {c:0, r:3}};
const sheetOptions = {'!merges': [ range ]};

var buffer = xlsx.build([{name: "mySheetName", data: data}], options);
```

```
npm i --save object-assign
```

```
```


