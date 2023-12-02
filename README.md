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
console.log(valuesObj) //output:["Amir", 21]

```
> _2.Object.entries()-In JavaScript, the Object.entries() method is used to extract both the keys and values of an object and return them as an array of key-value pairs._

```js

let person={
name:"Muhammadullo",
age:21,
job:"Student"
}

let entriesObj=Object.entries(person)
console.log(entries) //Output: [["name", "Muhammadullo"],["age", "21"],["job","student"]]
```

> #_What is destructuring in Object?_

```js
let person={
name:"Muhammadullo",
age:21,
job:"Stundent"
}

let {name,age, job}=obj

console.log(name) //output:"Muhammadullo"
console.log(age) //output:"21"
console.log(job) //output:"Student"
```


> #_Spread in Object?_

```js
let obj={
    name:"Muhammadullo",
    age:21
}


let copy={...obj}
console.log(copy) //output {name:"Muhammadullo", age:21}

```


> _What is this in JavaScript?-In JavaScript, the this keyword refers to the current execution context or the object that the function is being called on. Its value is determined by how a function is invoked.The behavior of this can vary depending on the context in which it is used. Here are some common scenarios:Global Scope: When this is used in the global scope (outside of any function), it refers to the global object, which is window in a browser environment or global in Node.js.Object Method: When this is used within a method of an object, it refers to the object itself._

```js

let  person = {
  name: 'Tom',
  sayHello: function() {
    console.log(`Hello, ${this.name}!`);
  }
};

person.sayHello(); // Output: Hello, Tom!


```

> _What is new Date in JavaScript?-In JavaScript, date and time are represented by the Date object.The Date object provides the date and time information and also provides various methods.A JavaScript date defines the EcmaScript epoch that represents milliseconds since 1 January 1970 UTC.This date and time is the UNIX epoch (predominant base value for computer-recorded date and time values.)_

> _Creating Date Objects.There are four ways to create a date object_
> _new Date_
```js
      let newDate=new Date(),
      console.log(newDate) //Output:Mon Oct 30 2023 18:44:54 GMT +0500 (Tajikistan)
```
> _new Date(milliseconds)_

```js
let  newDate=new Date(0)
console.log(newDate) //Output: Thu Jan 01 1970 06:00:00  (Tajikistan)
```
> _new Date (date string)_
```js
console.log(new Date("2024-03-09"))
```
> _now-returns the numeric value corresponding to the current time (the number of milliseconds elapsed since January 1, 1970 00:00:00 UTC)_
```js
console.log(Date.now()) //Output: 164578785498
```
> _getFullYear-gets the year according to local time_
```js
let newDate= new Date()
console.log(newDate.getFullYear()) //Output:2023
```
> _getMonth()-gets the month, from 0 to 11 according to local time_
```js
let newDate= new Date()
console.log(newDate.getMonth()) //Output:9
```
> _getDate()-gets the day of the month (1-31) according to local time_
```js
let newDate=new Date()
console.log(newDate.getDate()) //OutPut:30   
```
> _getDay()-Get the day of the week(0-6) according to local time_
```js
let newDate=new Date()
console.log(newDate.get.getDay()) //Output: 2
```
> _getHours()-Gets the hour from 0 to 23 according to local time_
```js
let newDate= new Date()
console.log(newDate.getDay()) //Output 🕖
```
> _getMinutes-Gets the minute from 0 to 59 according to local time_
```js
let newDate=new Date()
console.log(newDate.getMinutes()) //Output:5
```
> _getUTCDate()-Gets the day of the month (1-31) according to universal  time_
```js
let newDate= new Date()
console.log(newDate.getUTCDate)) //Output: 31
```
> _setFullYear-Sets the full year according to local time_
```js
let newDate = new Date()
console.log(newDate.setFullYear(2002)) //OutPut:1036034398368
```
> _setMonth()-Set the month according to local time_
```js
let newDate=new Date()
console.log(newDate.setMonth(2023)) //Output:6995042446215
```
> _setDate()-Sets the day  of the month accroding to loacl time_
```js
let newDate= new Date()
console.log(newDate.setDate(2023)) //Output:1870831429441
```
> _setUTCDate()-Sets the day of the month according to universal time_
```js
let newDate=new Date()
console.log(newDate.setUTCDate(2023)) //Output:1870831608556
```
