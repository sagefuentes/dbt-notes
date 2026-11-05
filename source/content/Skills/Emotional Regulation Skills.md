---
tags:
  - dbt
  - MOC
created:
status: in-progress
---



```base
views:
  - type: table
    name: Table
    filters:
      and:
        - file.hasProperty("dbt")
        - dbt == ["emotion regulation"]
    order:
      - file.name
      - file.tags
    columnSize:
      file.name: 279
      file.folder: 500

```


