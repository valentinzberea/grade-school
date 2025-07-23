# Grade School Roster

## Instructions

Implement a `GradeSchool` class that manages a school roster (student database). Students are organized by grade level, and within each grade, students should be sorted alphabetically.

## Required Methods

### `add` 
Add a student to the specified grade.

### `grade`
Return an array of all students in the specified grade, sorted alphabetically.

### `roster`
Return an object representing the complete school roster. Keys are grade numbers, values are arrays of student names

## Example Usage

```javascript
const school = new GradeSchool();

school.add('Jim', 2);           // Add Jim to grade 2
school.add('Alice', 1);         // Add Alice to grade 1
school.add('Bob', 2);           // Add Bob to grade 2

school.grade(2);                // Returns: ['Bob', 'Jim']
school.grade(1);                // Returns: ['Alice'] 
school.grade(3);                // Returns: []

school.roster();                // Returns: { 1: ['Alice'], 2: ['Bob', 'Jim'] }
```

Note: All students have single names only (it's a small town!).
