## Teacher Entity Table

### Description

This is an extension of the [Contact entity](./contact.md) for teacher contacts.

### Contents

**ALL FIELDS ARE REQUIRED**

* `Contact`
    - Should be of type `Lookup`
    - Links to the main contact record
* `Job ID`
    - `Single text line`
    - Should be relating to an existing record in `Jobs`

### Rules

* Can only have one `Contact` per `Jobs` pair