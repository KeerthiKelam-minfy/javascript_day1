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
![image](https://github.com/user-attachments/assets/d21782b0-338d-44fc-8d5e-09bfd992783f)


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
![image](https://github.com/user-attachments/assets/ab50b9b5-1a4a-40d7-97d3-4126f28bd203)


## 3. [Medium]

**Code:**   
<pre>
let scores = [25, 80, 45, 95, 60, 75];
const greaterThan70 = scores.filter(score => score >= 70)
console.log(greaterThan70)
</pre>

**Output:**  
![image](https://github.com/user-attachments/assets/f7fc0ff1-2991-408d-a1f1-251d14a81c46)


## 4. [Hard]

**Code:**   
<pre> 
let scores = [25, 80, 45, 95, 60, 75];
const average = scores.reduce((a, currentValue) => a + currentValue, 0) / scores.length
console.log(average)  
</pre>

**Output:**  
![image](https://github.com/user-attachments/assets/c5e549bf-fd4a-46b7-929c-f6a85bd8b5aa)
