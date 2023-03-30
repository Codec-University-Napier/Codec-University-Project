## Class Entity Table

### Description

This is a record for module classes

### Contents

**ALL FIELDS ARE REQUIRED**

* `ID`
    - Unique for each 
    - Auto generated number
    - With prefix `class-`
* `Name`
    - `single line text`
    - Name of the class
* `Available Time Slots`
    - Should be a list of dates (`day/hour`) where the class can be held

### Rules

* No Duplicates for `ID` and `Name`