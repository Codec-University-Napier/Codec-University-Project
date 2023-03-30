## Course Enrolment Record

### Description

This is the table to record all the enrolments of [`Students`](./student.md) to the particular [`Course`](./course.md) in the university.
This table should also hold the record of courses that the student has previously enrolled to as well.

### Contents

**ALL FIELDS ARE REQUIRED**

* `Course ID`
    - Should match and ID of a `course`
* `Student Matriculation Number`
    - Should match an existing `Matriculation Number`
    - 8 digit number
* `Status`
    - Describes the current relationship of the student with the course
    - Options:
        1. `Active` - The student is attending the course
        2. `Inactive` - The student has completed the course
        3. `Suspended` - The student has suspended the studies

### Rules

* Can only have one `Matriculation Number` per `Course`