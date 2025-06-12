# basics & variables

<pre>
// 1. Easy

const favoriteFood = "Chocolate"
console.log(favoriteFood)
</pre>

**Output:**   
Chocolate

  
<pre>
//2. Easy

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
numA(15) is larger.
  
<pre>
//3. Medium

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
1  
2  
3 - Fizz  
4  
5 - Buzz  
6 - Fizz  
7  
8   
9 - Fizz  
10 - Buzz  
11  
12 - Fizz   
13  
14  
15 - FizzBuzz  
16  
17  
18 - Fizz  
19  
20 - Buzz  
