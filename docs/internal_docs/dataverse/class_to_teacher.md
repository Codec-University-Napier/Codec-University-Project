## Class to Teacher relation Table

### Description

This table should link the [Teacher entity](./teacher.md) and the [Class entity](./class.md)

### Contents

* `Class ID`
    - The ID of the class to be assigned to the teacher
* `Teacher ID`
    - The ID of the teacher to be assigned to the class
    - Needs to match a [`Contact`](./contact.md) record that is also in a `Teacher` record
* `Time Slot`
    - Should be a date type (format : `day | hour`)
    - Should be one of the available time slots in the list
        - Verify by looking at the `Available Time Slots` list of the class with the correct `Class ID`

### Rules

* Can only have one `Head of faculty`