## Module to Teacher allocation table

### Description

This is table describes which [teachers](./teacher.md) are allocated to which [modules](./module.md) that they teach.

### Contents

**ALL FIELDS ARE REQUIRED**

* `Teacher ID`
    - Must match an ID in the [`Contacts`](./contact.md)
    - Must also be a contact that is looked up in the [`Teachers` entity table](./teacher.md)
* `Module ID`
    - Must match an ID in the [`Module` entity table](./module.md)

### Rules

* Many to Many relationship