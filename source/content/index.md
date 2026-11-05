---
tags:
created: 2026-8-28
---
Items still to be updated
- [ ] tags for all items
- [ ] Some notes not transferred yet.
- [ ] The [[Emotion Thermometer.canvas|Emotion Thermometer]]
- [ ] Notable missing pages
	- [ ] [[Radical Acceptance]]
	- [ ] [[Turn Your Mind]]
	- [ ] [[PLEASE Skills]]
	- [ ] Reach out if others are found
## Skills
```base
views:
  - type: table
    name: DBT
    filters:
      and:
        - file.hasTag("dbt")
    order:
      - file.name
      - dbt
    sort:
      - property: dbt
        direction: ASC
    columnSize:
      file.tags: 432
      file.name: 381
  - type: table
    name: Skills
    filters:
      and:
        - file.hasTag("dbt")
        - dbt
    order:
      - file.name
      - file.tags
    columnSize:
      file.name: 500
      file.folder: 500
      file.ctime: 175
      file.mtime: 175

```
