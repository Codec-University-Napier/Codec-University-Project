## Module enrollment Table

### Description

This table should link the [Student entity](./student.md) and the [Module entity](./module.md) to show what the students status is in the module

### Contents

* `Student ID`
    - The `Contact` table's `ID` field for the student
    - Must match an existing record
* `Assignment ID`
    - The ID of the module
    - Must match an existing record
* `Status`
    - Should be a choice type. Choices should include:
        - Active
        - Inactive
        - Passed
        - Failed
    - Only one can be selected
* `Grade`
    - A single text line
    - Should be either A, B, C, D or Fail

### Rules

* Many to many relationship
* Status cannot be anything other than `Active` or `Inactive` if the module has not been completed yet
* Grade cannot be assigned until module has been completed