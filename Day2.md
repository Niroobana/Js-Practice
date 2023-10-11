q1:
let c = { greeting: 'Hey!' };
let d;

d = c;
c.greeting = 'Hello';
console.log(d.greeting);

Q2:
const obj = { 1: 'a', 2: 'b', 3: 'c' };
const set = new Set([1, 2, 3, 4, 5]);

obj.hasOwnProperty('1');
obj.hasOwnProperty(1);
set.has('1');
set.has(1);

Q3:
const obj = { a: 'one', b: 'two', a: 'three' };
console.log(obj);

q4:
const a = {};
const b = { key: 'b' };
const c = { key: 'c' };

a[b] = 123;
a[c] = 456;

console.log(a[b]);

q5:
const numbers = [1, 2, 3];
numbers[10] = 11;
console.log(numbers);

q6:
[[0, 1], [2, 3]].reduce(
  (acc, cur) => {
    return acc.concat(cur);
  },
  [1, 2],
);

q7:
let person = { name: 'Lydia' };
const members = [person];
person = null;

console.log(members);

q8:
const numbers = [1, 2, 3, 4, 5];
const [y] = numbers;

console.log(y);

q9:
const user = { name: 'Lydia', age: 21 };
const admin = { admin: true, ...user };

console.log(admin);

q10:
const settings = {
  username: 'lydiahallie',
  level: 19,
  health: 90,
};

const data = JSON.stringify(settings, ['level', 'health']);
console.log(data);

q11:
const person = {
  name: 'Lydia',
  age: 21,
};

let city = person.city;
city = 'Amsterdam';

console.log(person);

q12:
let newList = [1, 2, 3].push(4);

console.log(newList.push(5));

q13:
const colorConfig = {
  red: true,
  blue: false,
  green: true,
  black: true,
  yellow: false,
};

const colors = ['pink', 'red', 'blue'];

console.log(colorConfig.colors[1]);