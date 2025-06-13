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
![image](https://github.com/user-attachments/assets/0cffec7e-cf4d-4cb6-bb8e-583184211b6f)



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
![image](https://github.com/user-attachments/assets/a79a7a5a-0747-425c-9126-97184b84cdd1)


## 3. [Medium]

**Code:**   
<pre>
let scores = [25, 80, 45, 95, 60, 75];
const greaterThan70 = scores.filter(score => score >= 70)
console.log(greaterThan70)
</pre>

**Output:**  
![image](https://github.com/user-attachments/assets/75d682f8-ffa5-423b-8a4a-cffcf48f2121)


## 4. [Hard]

**Code:**   
<pre> 
let scores = [25, 80, 45, 95, 60, 75];
const average = scores.reduce((a, currentValue) => a + currentValue, 0) / scores.length
console.log(average)  
</pre>

**Output:**  
![image](https://github.com/user-attachments/assets/6935504d-61ab-460f-97bb-7d78711f19aa)
