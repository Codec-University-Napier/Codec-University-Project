## Course Entity

### Description

This table should describe all courses available in the university

### Contents

* ID
    - **Required**
    - Automatically generated id
    - With prefix `course-`
    - Unique for each record
* Name
    - **Required**
    - Name of the course
* Available slots
    - **Required**
    - Number
    - Minimum number is 0
* Description
    - **Optional**
* Faculty
    - **Required**
    - Lookup

### Rules

* No duplicates in `Name`
