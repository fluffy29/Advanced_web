# Student Object Example

This is a JavaScript excercise where I manipulate a `student` object. It shows how to update properties, add new ones, and perform some array operations.

## Code

```js
const student = {
    name: "Marie",
    age: 20,
    courses: []
};

student.age = 21;

student.grade = "A";

student.courses.push("Math", "Physics", "Chemistry");

const physicsIndex = student.courses.indexOf("Physics");

const firstTwoCourses = student.courses.slice(0, 2);


console.log(student);

console.log("Index of Physics:", physicsIndex);

console.log("First two courses:", firstTwoCourses);
```

## What's Happening?

- **Initial Object**: 
  - name : marie
  - age : `20`
  - courses: An empty array.

- **Array Operations**:
  - Found the index of "Physics".
  - Extracted the first two courses using slice().

## Output

The `student` object looks like this:

```json
{
    "name": "Marie",
    "age": 21,
    "courses": ["Math", "Physics", "Chemistry"],
    "grade": "A"
}
```

### How to Run

Simply copy and paste the code into any JavaScript environment and check the console for outputs.

For example: node index.js