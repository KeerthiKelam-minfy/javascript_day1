# arrays

## 1. [Easy]

**Code:** 
<pre>
let colors = ["Green", "Red", "Pink"]
colors.push("Orange")
colors.unshift("Purple")
console.log(colors)
</pre>

**Output:**   
<pre>
[ 'Purple', 'Green', 'Red', 'Pink', 'Orange' ]
</pre>


## 2. [Medium]  

**Code:**   
<pre> 
let numbers = [10, 20, 30, 40, 50];
const increasedNumbers = numbers.map(function(number) {
    return number + 5
})
console.log(increasedNumbers)
</pre>

**Output:**  
<pre>
[ 15, 25, 35, 45, 55 ]
</pre>

## 3. [Medium]

**Code:**   
<pre>
let scores = [25, 80, 45, 95, 60, 75];
const greaterThan70 = scores.filter(score => score >= 70)
console.log(greaterThan70)
</pre>

**Output:**  
<pre>
[ 80, 95, 75 ]
</pre>

## 4. [Hard]

**Code:**   
<pre> 
let scores = [25, 80, 45, 95, 60, 75];
const average = scores.reduce((a, currentValue) => a + currentValue, 0) / scores.length
console.log(average)  
</pre>

**Output:**  
<pre>
63.333333333333336
</pre>
