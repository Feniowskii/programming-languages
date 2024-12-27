<h1>Programming Languages Projects</h1>

<p>A repository for Programming Languages course projects. These projects were completed as part of the 3rd semester of the Computer Science program at Gdańsk University of Technology. The course aimed at teaching the basics of paradigms of different languages, such as OOP for Smalltalk and functional programming for Haskell.</p>

<p>Here are the tasks for specified languages:</p>

<h2>Ada95</h2>

<ol>
  <li>Create a program for simulating the operations of producers, consumers, and buffers (magazines) and add your own theme.</li>
  <li>Use rendezvous: selective wait and selective with conditional entry calls.</li>
  <li>Cover edge cases:
    <ul>
      <li>The consumer shouldn't receive assembly number 0.</li>
      <li>What happens if the producer cannot deliver an assembly to the buffer?</li>
      <li>Other cases arising from your implementation.</li>
    </ul>
  </li>
  <li>Solve concurrency problems:
    <ul>
      <li>Prevent deadlock.</li>
      <li>Propose an idea for balancing the buffer or deliveries to ensure the program runs as smoothly as possible.</li>
    </ul>
  </li>
  <li>Create a task called "Cleaning", including an entry "Start" (similar to Consumer and Producer):
    <ul>
      <li>In the body of the task, initialize the variable day_number and assign it the value 1.</li>
      <li>Simulate a countdown of days with a fixed duration, incrementing the value of day_number by one. When the variable reaches the value 10, invoke the buffer entry Cleaning_day and reset day_number to 1.</li>
    </ul>
  </li>
  <li>In the Buffer task, add the entry Cleaning_day, and in its body:
    <ul>
      <li>A procedure Today_Is_Cleaning_Day that removes 3 products of each type from the storage on day 10.</li>
      <li>Add another or condition to the select statement in the buffer to accept Cleaning_day and invoke Today_Is_Cleaning_Day.</li>
    </ul>
  </li>
</ol>

<h2>Smalltalk</h2>

<ol>
  <li>Create a subclass of the Polygon class: An isosceles triangle (base, height). The first vertex of each new polygon should be located at the point (0,0). The new class should, just like the Square class, allow adding figures in terms of area. The result of the addition should have an area equal to the sum of the areas of the added figures and should also be a figure that retains the proportions of the recipient. The class should implement messages: "area" and "+".</li>
  
  <li>Create a message "scale: number", which will scale the sides of the polygon according to the given scale.</li>
  
  <li>Define the message "print", which will print the vertices and area of the polygon. This message should be defined for the Polygon class. When adding transformation messages and other messages resulting from the task description, also ensure that the results are printed in the "print" message.</li>
  
  <li>Create a new message for objects of the Polygon class - "rotate". This message should accept a parameter angle and check if 0 < angle <= 90. Then, the polygon should be rotated by the specified angle to the right.</li>
</ol>

<h2>Haskell</h2>

<ol>
  <li>For a given natural number n, find the smallest natural number m ≥ n such that a set A can be formed consisting of two types of elements X and Y with the size |A| = |X| + |Y| = m, where |X| ≥ |Y|. The probability of selecting two elements X in a row from the set A should be equal to 1/2. For example, for n = 20, m = 21, |X| = 15, and |Y| = 6, the probability of selecting two elements X in a row is P(xx) = (15/21) * (14/20) = 1/2.</li>
  
  <li>For any set of numbers S, let sum(S) denote the sum of its elements. For a certain set T and a certain k < n, where n = |T|, consider all the sums sum(Ui) of all subsets Ui (where 0 < i ≤ Cn,k) of size k from the set T. The subsets Ui represent all Cn,k k-element combinations of the n-element set T. Some of these sums sum(Ui) appear more than once, while others are unique. Provide the sum of the unique sums sum(Ui) of the set T. For example: for the set T = {1, 3, 6, 8, 10, 11} and k = 3, there are C6,3 = 20 subsets Ui, of which only 8 will have unique sums sum(Ui), and their total sum will be 156. </li>
  
  <li>For a given natural number n, find the largest palindrome that can be obtained by multiplying two n-digit numbers. For n=2, the largest palindrome is 9009 = 91 × 99.</li>
</ol>

<h2>Prolog</h2>

<p><b>TBA</b></p>
