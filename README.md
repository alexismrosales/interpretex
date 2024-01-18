# Interprex 
This is a basic interpreter where you can program some things.
The program can accept different data structures like
<ul>
  <li>if else conditional</li>
  <li>for loop</li>
  <li>while loop</li>
</ul>
and can solve operations like
<ul>
  <li>Sum</li>
  <li>Multiplication</li>
  <li>Division</li>
  <li>Exponen</li>
</ul>

    
You can create any type of variable using
```
    var your_var = your_value;
```
data types like double, float, int and string are accepted.

This is a code example
```
  //Fibbonacci series
  var fib = 0;
  var lim = 5;
  var aux = 1;
  var init = 1;
  
  print "Begin of algorithm";
  while(init <= lim){
      print fib;
      aux = aux + fib;
      fib = aux - fib;
      init = init + 1;
  }
  
  print "End of algorithm ";
```   
## Execution
The program will execute the prompt when you run the interpreter file without any input.
If theres an input file it has to be a text file and there will be an output.
```
example_text.txt 
```
