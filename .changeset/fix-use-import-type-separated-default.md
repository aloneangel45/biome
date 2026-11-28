---
"@biomejs/biome": patch
---

Fixed [`useImportType`](https://biomejs.dev/linter/rules/use-import-type/) with `style: "separatedType"` so a default value import is kept as a value import when separating combined imports that already contain inline `type` named specifiers.
