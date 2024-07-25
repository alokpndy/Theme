# A Mermaid Syntax

```mermaid
gantt
    title 70 TPH WHRB
    dateFormat  YYYY-MM-DD
    section FabricationTask
    a1 Fabrication of Columns : a1, 2024-08-01, 30d
    a2 Fabrication of Beams : after a1  , 20d
    a3 Fabrication of Bracing : after a2  , 10d
    section ErectionTask
    e1 Erection of Column :e1, 2024-09-01 15d
    e2 Erection of Beams and Bracing : after e1, 10d
    Task in sec        : 2014-01-12  , 12d
    another task       : 24d
```
