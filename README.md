Answer of given questions:-
<br> 
<b>1.</b> B
<br> 
<b> 2. </b> B 
<br> 
<b> 3. </b> B 
<br> 
<b> 4. </b> A 
<br> 
<b> 5. </b> C 
<br> 
<b> 6.(a) </b>const people = [
    { id: 1, name: 'John', age: 30 },
    { id: 2, name: 'Jane', age: 25 },
    { id: 3, name: 'Bob', age: 40 },
];
<br> 
const names = people.map(person => person.name);
<br> 
console.log(names); // Output: ['John', 'Jane', 'Bob'] 
<br> 
<b> (b) </b> const peopleWithSalary = people.map(person => ({
    ...person,
    salary: 50000
}));
<br> 
console.log(peopleWithSalary);
<br> 
<b> (c) </b> const peopleAbove30 = people
    .filter(person => person.age > 30)
    .map(person => ({
        name: person.name,
        age: person.age
    }));
<br> 
console.log(peopleAbove30);
<br> 
<b> 7. </b> // Define cb1 to add two numbers
<br> 
function cb1(x, y) {
    return x + y;
}
<br> 
// Define cb2 to subtract two numbers
<br> 
function cb2(x, y) {
    return x - y;
}
<br> 
// Define the main function that takes two callbacks and two numbers
<br> 
function main(cb1, cb2, x, y) { 
<br> 
    const sum = cb1(x, y);
    <br> 
    const difference = cb2(x, y);
    <br> 
    
    console.log(Sum: ${sum});
    <br> 
    console.log(Difference: ${difference});
    <br> 
}
<br> 
// Test the main function with x = 11 and y = 4
<br> 
const x = 11;
<br> 
const y = 4;
<br> 
main(cb1, cb2, x, y);
<br> 
<b> 8. </b> C
<br> 
<b> 10. </b> C
<br> 
<b> 11. </b> A
<br> 
<b> 12. </b> A
<br>
<b> 13. </b> C
