## Student Entity Table

### Description

This is an extension of the [Contact entity](./contact.md) for student contacts.

### Contents

**ALL FIELDS ARE REQUIRED**

* `Contact`
    - Should be of type Lookup
    - Links to the main contact record
* `Student Matriculation Number`
    - Should be automatically generated
    - 8 digit number
    - Must be unique

### Rules

* Can only have one `Matriculation Number` per `Student Contact`