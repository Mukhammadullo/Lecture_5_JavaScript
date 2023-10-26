# _1.What is Object in JavaScript?_
> _In JavaScript, an object is a data type that allows you to store and organize related data and functions together. It is like a container that holds properties and methods._
```js

//Object
let person={
    firstName:"Muhammadullo",
    LastName:"Nastulloev",
    age:21,
    job:"Stundent"
}

```
# _How add in object element?_
```js
let person={
    name:"Muhammadullo",
    age:12
}
person.lastname="Nastulloev"
console.log()
```

# _How change element in Object?_
```js
let person={
    firstName:"Muhammadullo",
    lastName:"Nastulloev",
    age:21
}
person.age=18
console.log(person) //output age:18
```
# _How element delete in Object?_
```js

let person={
    firstName:"Muhammadullo",
    age:19,
}
delete person.age
console.log(person) //Output {firstName:"Muhammadullo"}

```

# _Methods object in JavaScript?_
>_1.Object.keys()-In JavaScript, the Object.keys() method is used to extract all the keys of an object and return them as an array. It allows you to iterate over the keys of an object and perform operations on them._

```js

let person={
    name:"Muhammadullo",
    age:21
}
let keys=Object.keys(person)
console.log(keys) //output:["name", "age"]
```
>_2.Object.values()-In JavaScript, the Object.values() method is used to extract all the values of an object and return them as an array. It allows you to iterate over the values of an object and perform operations on them._

```js

let person={
    name:"Amir",
    age:21
}
let valuesObj=Object.values(person)
console.log(valuesObj) //output:

```
> _2.Object.entries()-In JavaScript, the Object.entries() method is used to extract both the keys and values of an object and return them as an array of key-value pairs._

