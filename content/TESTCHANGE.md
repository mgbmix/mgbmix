

```dataviewjs
await dv.queryMarkdown("LIST FROM #tag") =>
```



```dataviewjs
await dv.query("LIST FROM #tag") =>
    { successful: true, value: { type: "list", values: [value1, value2, ...] } }

await dv.query(`TABLE WITHOUT ID file.name, value FROM "path"`) =>
    { successful: true, value: { type: "table", headers: ["file.name", "value"], values: [["A", 1], ["B", 2]] } }

await dv.query("TASK WHERE due") =>
    { successful: true, value: { type: "task", values: [task1, task2, ...] } }
```

```dataviewjs
const markdown = dv.markdownList(dv.pages('#card/item and "CARDS/DROP01"').file.link);
dv.paragraph(markdown);
```




