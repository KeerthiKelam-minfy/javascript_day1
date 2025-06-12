# advanced

## 1. [Hard]

**Code:** 
<pre>
function getHighAchievers(students, passingScore) {

    const passedStudents = students.filter(student => student.score >= passingScore)
    const highAchievers = passedStudents.map(student => student.name.toUpperCase())
    
    return {passedStudents, highAchievers}
}

students = [
    {id: 1, name: "Keerthi", score: 90},
    {id: 2, name: "Aarthi", score: 100},
    {id: 3, name: "Sam", score: 75 }
]

const {passedStudents, highAchievers} = getHighAchievers(students, 80)
console.log(passedStudents)
console.log(highAchievers)
</pre>

**Output:**   
<pre>
[
  { id: 1, name: 'Keerthi', score: 90 },
  { id: 2, name: 'Aarthi', score: 100 }
]
[ 'KEERTHI', 'AARTHI' ]
</pre>


## 2. [Hard]  

**Code:**   
<pre>
function createGame() {
    let secretNumber = Math.floor(Math.random() * 10 + 1)
    function guess(number) {
        if(secretNumber === number) {
            console.log("You guessed it!")
        }else if(number < secretNumber) {
            console.log(secretNumber - number > 3? "Too low!" : "Low, but close!")
        }else{
            console.log(number - secretNumber > 3? "too high!" : "High, but close!")
        }
    }
    return guess
}


const play = createGame()
play(1)
play(2)
play(3)
play(4)
play(5)
play(6)
play(7)
play(8)
play(9)
play(10)
</pre>

**Output:**  
<pre>
Too low!
Too low!
Too low!
Too low!
Too low!
Too low!
Low, but close!
Low, but close!
Low, but close!
You guessed it!
</pre>
