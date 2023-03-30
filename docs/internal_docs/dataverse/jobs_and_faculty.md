## Jobs and Faculty table

### Description

This table should describe which [`Jobs`](./job.md) are part of which [`Faculty`](./faculty.md) and how many available positions there are.

### Contents

**ALL FIELDS ARE REQUIRED**

* `Faculty ID`
    - Must match an ID in the `Faculties` table
* `Job ID`
    - **Required**
    - Must match an ID in the `Job` table
* `Available slots`
    - Number
    - Minimum number is 0

### Rules

* No duplicate pairs of `Faculty ID` and `Job ID`
