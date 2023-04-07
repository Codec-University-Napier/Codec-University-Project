## Class to Student allocation table

### Description

This table should describe the relationship between [Classes](./class.md) and [Students](./student.md).
With this table the timetable for each individual student can be made.

### Contents

**ALL FIELDS ARE REQUIRED**

* `Class ID`
    - The ID of the class to be assigned to the student
* `Student Matriculation Number`
    - The Student that the class is assigned to
    - Should match only one student in the `Students` entity table
* `Time Slot`
    - Should be a date type (format : `day | hour`)
    - Should be one of the available time slots in the list
        - Verify by looking at the `Available Time Slots` list of the class with the correct `Class ID`

### Rules

* Can only have one `Matriculation Number` per `Class ID` pair