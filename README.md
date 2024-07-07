answer of given questions:-
<b>1.</b> B
2. B 
3. B 
4. A 
5. C 
6.(a) const people = [
    { id: 1, name: 'John', age: 30 },
    { id: 2, name: 'Jane', age: 25 },
    { id: 3, name: 'Bob', age: 40 },
];

const names = people.map(person => person.name);

console.log(names); // Output: ['John', 'Jane', 'Bob'] 
(b) const peopleWithSalary = people.map(person => ({
    ...person,
    salary: 50000
}));

console.log(peopleWithSalary);
(c) const peopleAbove30 = people
    .filter(person => person.age > 30)
    .map(person => ({
        name: person.name,
        age: person.age
    }));

console.log(peopleAbove30);
7. // Define cb1 to add two numbers
function cb1(x, y) {
    return x + y;
}

// Define cb2 to subtract two numbers
function cb2(x, y) {
    return x - y;
}

// Define the main function that takes two callbacks and two numbers
function main(cb1, cb2, x, y) {
    const sum = cb1(x, y);
    const difference = cb2(x, y);
    
    console.log(Sum: ${sum});
    console.log(Difference: ${difference});
}

// Test the main function with x = 11 and y = 4
const x = 11;
const y = 4;
main(cb1, cb2, x, y);
8. C
10. C
11. A
12. A
13. C
