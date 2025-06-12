# basics & variables

<pre>
// 1. Easy

const favoriteFood = "Chocolate"
console.log(favoriteFood)
</pre>

  
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
