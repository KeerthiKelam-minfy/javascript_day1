# objects & functions

## 1. [Easy]

**Code:** 
<pre>
const movie = {
    title: "Bahubali",
    director: "Rajamouli",
    releaseYear: 2019
}
console.log(movie.title)
</pre>

**Output:**   
<pre>
Bahubali
</pre>


## 2. [Medium]  

**Code:**   
<pre>
const person = {
    name: "Keerthi", 
    email:"keerthikelam77@gmail.com", 
    age:20
}
function printUserDetails({name, email, age}) {
    console.log(`User's name is ${name}, and they are ${age} years old.`)
} 
printUserDetails(person)
</pre>

**Output:**  
<pre>
User's name is Keerthi, and they are 20 years old.
</pre>

## 3. [Medium]

**Code:**   
<pre>
const users = [
    {id: 1, username: "keerthikelam"},
    {id: 2, username: "meghanasaibhima"}
]

const search = users.find(user => user.id === 1)
console.log(search)
</pre>

**Output:**  
<pre>
{ id: 1, username: 'keerthikelam' }
</pre>
