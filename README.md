<h1>The Bash Course exercises</h1>

These are the requirements of each task:

<h3>TASK 1</h3>
The Fibonacci numbers are the numbers in the following integer sequence. 0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, …….. In mathematical terms, the sequence Fn of Fibonacci numbers is defined by the recurrence relation Fn = Fn-1 + Fn-2 with seed values F0 = 0 and F1 = 1. Write a function fib that returns Fn. For example:<br>
    - if n = 0, then fib should return 0<br>
    - if n = 1, then it should return 1<br>
    - if n > 1, it should return Fn-1 + Fn-2

<h3>TASK 2</h3>
Write bash script accepting operation parameter (“-”, “+”, “*”, “%”), sequence of numbers and debug flag. For example:<br>
    - ./your_script.sh -o % -n 5 3 -d > Result: 2<br>
    - ./your_script.sh -o + -n 3 5 7 -d > Result: 15=<br>
If -d flag is passed, script must print additional information:<br>
    - User: username of the user running the script<br>
    - Script: script name<br>
    - Operation: operation<br>
    - Numbers: all space-separated numbers<br>


<h3>TASK 3</h3>
You need to write a script that prints the numbers from 1 to 100 such that:<br>
    - If the number is a multiple of 3, you need to print "Fizz" instead of that number.<br>
    - If the number is a multiple of 5, you need to print "Buzz" instead of that number.<br>
    - If the number is a multiple of both 3 and 5, you need to print "FizzBuzz" instead of that number.<br>

<h3>TASK 5</h3>
Write script with following functionality:<br>
    - If -v tag is passed, replaces lowercase characters with uppercase and vise versa<br>
    - If -s is passed, script substitutes <A_WORD> with <B_WORD> in text (case sensitive)<br>
    - If -r is passed, script reverses text lines<br>
    - If -l is passed, script converts all the text to lower case<br>
    - If -u is passed, script converts all the text to upper case<br>
    - Script should work with -i <input file> -o <output file> tags<br>

<h3>TASK 6</h3>
Create script, that generates report file with following information:<br>
    - current date and time;<br>
    - name of current user;<br>
    - internal IP address and hostname;<br>
    - external IP address;<br>
    - name and version of Linux distribution;<br>
    - system uptime;<br>
    - information about used and free space in / in GB;<br>
    - information about total and free RAM;<br>
    - number and frequency of CPU cores
