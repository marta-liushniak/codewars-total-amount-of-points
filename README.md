Our football team has finished the championship and match results are recorded in an array of Strings. Each match is represented by a String in the format **"x:y"**, where **x** is our team's score and **y** is our opponents score.

For example: **["3:1", "2:2", "0:1", etc]**.

Points are awarded for each match as follows:

if x > y: *3* points (win)     
if x < y: *0* points (loss)      
if x = y: *1* point (tie).

Task: we need to write a function that takes this array and returns the number of points our team (**x**) got in the championship by the rules given above.
