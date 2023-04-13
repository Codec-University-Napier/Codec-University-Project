## Assignment to Teachers relationship table

### Description

This is an table relating the [assignments](./assignment.md) to [teachers](./teacher.md).
This relationship shows which teacher can mark the assignments for students.

### Contents

**ALL FIELDS ARE REQUIRED**

* `Assignment ID`
    - The ID of the assignment
    - Must match an existing record
* `Teacher ID`
    - The `Contact` table's `ID` field for the teacher
    - Must match an existing record

### Rules

* Many to Many relationship