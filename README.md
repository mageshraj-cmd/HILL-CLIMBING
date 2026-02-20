<h1>ExpNo 5 : Implement Simple Hill Climbing Algorithm</h1> 
<h3>Name: MAGESHRAJ P
<h3>Register Number:212224250010
<H3>Aim:</H3>
<p>Implement Simple Hill Climbing Algorithm and Generate a String by Mutating a Single Character at each iteration </p>
<h2> Theory: </h2>
<p>Hill climbing is a variant of Generate and test in which feedback from test procedure is used to help the generator decide which direction to move in search space.
Feedback is provided in terms of heuristic function
</p>


<h2>Algorithm:</h2>
<p>
<ol>
 <li> Evaluate the initial state.If it is a goal state then return it and quit. Otherwise, continue with initial state as current state.</li> 
<li>Loop until a solution is found or there are no new operators left to be applied in current state:
<ul><li>Select an operator that has not yet been applied to the current state and apply it to produce a new state</li>
<li>Evaluate the new state:
  <ul>
<li>if it is a goal state, then return it and quit</li>
<li>if it is not a goal state but better than current state then make new state as current state</li>
<li>if it is not better than current state then continue in the loop</li>
    </ul>
</li>
</ul>
</li>
</ol>

</p>
<hr>
<h3> Steps Applied:</h3>
<h3>Step-1</h3>
<p> Generate Random String of the length equal to the given String</p>
<h3>Step-2</h3>
<p>Mutate the randomized string each character at a time</p>
<h3>Step-3</h3>
<p> Evaluate the fitness function or Heuristic Function</p>
<h3>Step-4:</h3>
<p> Lopp Step -2 and Step-3  until we achieve the score to be Zero to achieve Global Minima.</p>

<hr>
<h2>Sample Input and Output</h2>
<h2>Sample String:</h2> Artificial Intelligence
<h2>Output:</h2>
Score: 643  Solution :  8RzF:oG ]%;CPORRMe!zGvk<br>
Score: 609  Solution :  8RzF:oG ]%;CPqRRMe!zGvk<br>
Score: 604  Solution :  8RzF:oG ]%;CPqRRMe!zGqk<br>
Score: 594  Solution :  8RzF:oG ]%;CPqRRWe!zGqk<br>
Score: 551  Solution :  8RzF:oGK]%;CPqRRWe!zGqk<br>
Score: 551  Solution :  8RzF:oGK]%;CPqRRWe!zGqk<br>
Score: 551  Solution :  8RzF:oGK]%;CPqRRWe!zGqk<br>
Score: 551  Solution :  8RzF:oGK]%;CPqRRWe!zGqk<br>
Score: 551  Solution :  8RzF:oGK]%;CPqRRWe!zGqk<br>
....................................................<br>
..................................................<br>
................................................<br>
Score: 1  Solution :  Artificial Intelligencf<br>
Score: 1  Solution :  Artificial Intelligencf<br>
Score: 1  Solution :  Artificial Intelligencf<br>
Score: 1  Solution :  Artificial Intelligencf<br>
Score: 0  Solution :  Artificial Intelligence<br>
<!DOCTYPE html>
<html>
<head>
  <title>Experiment No. 5 - Simple Hill Climbing Algorithm</title>
</head>
<body>

<h1>Exp No. 5 : Implement Simple Hill Climbing Algorithm</h1>

<h3>Name: Janani Shree G R</h3>
<h3>Register Number: 212224060105</h3>

<hr>

<h2>Aim:</h2>
<p>
To implement a Simple Hill Climbing Algorithm and generate a target string by mutating a single character at each iteration.
</p>

<h2>Theory:</h2>
<p>
Hill Climbing is a variant of the Generate-and-Test algorithm in which feedback from the test procedure is used to decide the direction of movement in the search space.
The feedback is provided in terms of a heuristic function that measures how close the current state is to the goal state.
Hill climbing moves step by step toward a better solution until a local or global optimum is reached.
</p>

<h2>Algorithm:</h2>
<ol>
  <li>Evaluate the initial state. If it is a goal state, return it and quit; otherwise, continue with the initial state as the current state.</li>
  <li>Loop until a solution is found or there are no new operators left to apply in the current state:
    <ul>
      <li>Select an operator that has not yet been applied to the current state and apply it to produce a new state.</li>
      <li>Evaluate the new state:
        <ul>
          <li>If it is a goal state, return it and quit.</li>
          <li>If it is not a goal state but better than the current state, make it the new current state.</li>
          <li>If it is not better than the current state, continue the loop.</li>
        </ul>
      </li>
    </ul>
  </li>
</ol>

<hr>

<h2>Steps Applied:</h2>

<h3>Step 1:</h3>
<p>Generate a random string of the same length as the target string.</p>

<h3>Step 2:</h3>
<p>Mutate the randomized string by changing one character at a time.</p>

<h3>Step 3:</h3>
<p>Evaluate the fitness or heuristic function to measure how close the current string is to the target string.</p>

<h3>Step 4:</h3>
<p>Repeat Step 2 and Step 3 until the score becomes zero (achieving the goal string — global minima).</p>

<hr>

<h2>Sample Input and Output:</h2>

<h3>Sample String:</h3>
<p>Artificial Intelligence</p>

<h3>Output:</h3>
<p>
Score: 643 &nbsp; Solution: 8RzF:oG ]%;CPORRMe!zGvk<br>
Score: 609 &nbsp; Solution: 8RzF:oG ]%;CPqRRMe!zGvk<br>
Score: 604 &nbsp; Solution: 8RzF:oG ]%;CPqRRMe!zGqk<br>
Score: 594 &nbsp; Solution: 8RzF:oG ]%;CPqRRWe!zGqk<br>
Score: 551 &nbsp; Solution: 8RzF:oGK]%;CPqRRWe!zGqk<br>
...<br>
...<br>
Score: 1 &nbsp; Solution: Artificial Intelligencf<br>
Score: 0 &nbsp; Solution: Artificial Intelligence<br>
</p>

<hr>

<h2>Conclusion:</h2>
<p>
The Simple Hill Climbing Algorithm successfully generates the target string “Artificial Intelligence” by iteratively improving the random string through single-character mutations guided by a heuristic function. 
The process stops when the score becomes zero, indicating that the goal state has been achieved.
</p>

</body>
</html>
