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
![image](https://github.com/user-attachments/assets/5b195360-61e2-4f9c-956d-3954ac8c35c5)


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
![image](https://github.com/user-attachments/assets/39e90b77-add7-42ef-be2b-ac552b21c8c5)


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
![image](https://github.com/user-attachments/assets/b9f2d9c4-c3fa-47d1-8e11-05b69e5ad9c6)

