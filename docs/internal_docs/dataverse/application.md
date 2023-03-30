## Application Entity

### Description

This table should hold all applications for jobs in faculties

### Contents

**ALL FIELDS ARE REQUIRED**

* ID
    - Automatically generated id
    - With prefix `app-`
    - Unique for each record
* Name of the Applicant
    - `Single line text`
* Email
    - Email `Format`
* Phone Number
    - Phone Number `format`
* Job
    - `Lookup`
* Cover Letter
    - `Text Field`
    - Must have a set maximum word count

### Rules

* Cannot have a duplcate `Name of the Applicant` and `Job` pair
