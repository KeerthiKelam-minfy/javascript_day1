# basics & variables

## 1. [Easy]

**Code:** 
<pre>
const favoriteFood = "Chocolate"
console.log(favoriteFood)
</pre>

**Output:**   
![image](https://github.com/user-attachments/assets/41f62e5e-e3d9-445b-b442-f81fa08fc525)


## 2. [Easy]  

**Code:**   
<pre>

let numA = 15
let numB = 10
if(numA > numB) {
    console.log(`numA(${numA}) is larger.`)
}else if(numB > numA) {
    console.log(`numB(${numB}) is larger.`)
}else {
    console.log("Both are equal")
}
</pre>

**Output:**  
![image](https://github.com/user-attachments/assets/ed387881-1445-4228-9fee-3e99c3d61bc5)


## 3. [Medium]

**Code:**   
<pre>

for(let i = 1; i <= 20; i++) {
    if(i % 3 == 0 && i % 5 == 0) {
        console.log(`${i} - FizzBuzz`)
    }else if(i % 3 == 0) {
        console.log(`${i} - Fizz`)
    }else if(i % 5 == 0) {
        console.log(`${i} - Buzz`)
    }else {
        console.log(`${i}`)
    }
}
</pre>

**Output:**  
![image](https://github.com/user-attachments/assets/23c0e843-2fe5-45c5-bd52-ea7fcadcd5ed)
