# A Mermaid Syntax

```mermaid
gantt
    title 70 TPH WHRB
    dateFormat  YYYY-MM-DD
    section Task
    a1 Fabrication of Columns             : a1, 2014-01-01, 30d
    a2 Fabrication of Beams       : after a1  , 20d
    a3 Fabrication of Bracing       : after a2  , 2d
    section Another
    Task in sec        : 2014-01-12  , 12d
    another task       : 24d
```
