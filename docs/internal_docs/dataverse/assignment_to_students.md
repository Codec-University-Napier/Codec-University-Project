## Class to Teacher relation Table

### Description

This table should link the [Student entity](./student.md) and the [Assignment entity](./assignment.md)

### Contents

* `Student ID`
    - The `Contact` table's `ID` field for the student
    - Must match an existing record
* `Assignment ID`
    - The ID of the assignment
    - Must match an existing record
* `Due date`
    - Should be a date type (format : `day | hour`)
* `Grade`
    - A single text line
    - Should be either A, B, C, D or Fail

### Rules

* Many to many relationship