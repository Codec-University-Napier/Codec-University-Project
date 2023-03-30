## Faculty Entity Table

### Description

This table should hold all information on each faculty

### Contents

* `ID`
    - An automatically generated ID
    - Has prefix `faculty`
    - 4 number digits after prefix
    - Must be unique
* `Name`
    - Single line text field
    - Gives the faculty name
* `Description`
    - Should be a multi-line text field
    - Gives a breif description of the job slot
* `Head of faculty`
    - Should be of type lookup
    - Is linked to a [Teacher entity](./teacher.md)

### Rules

* Can only have one `Head of faculty`