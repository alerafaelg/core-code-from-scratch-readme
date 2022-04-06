# core-code-from-scratch-readme


<details><summary> first week </summary>
  
<p>
  
<details><summary> tuesday april 5th </summary>

 ### interpreted & compiled programming languages
 
 #### interpreted programming languages
  
  > since this language is not compiled, everybody will be needing an interpreter to be able to execute the code itself
  
 interpreted programming languages are slower than compiled programming languages, they also go through a program line by line and they execute each command
 also, it can be modified while you are working on them, so you can make changes on the go and also check the results
 
  
| pros | cons |
| ----------- | ----------- |
| cross-platform | an interpreter is required |
| easier to test | usually is slower |
| simply to debug | the source code is public |

#### compiled programming languages
 
  > the compiler uses the source code to produce an exe that contains the machine code
  
compiled programming languages are faster than interpreted programming languages, because in this case the source code is written and a compiler (program)
goes through that source code producing a new file that contains the machine code, usually an executable file
  
  | pros | cons |
| ----------- | ----------- |
| ready to run | not cross-platform |
| it's faster | it's not flexible |
| source code is private | takes extra step |
  
<hr>
  
  >**Java script is both, interpreted and compiled programming language at the same time, because it has characteristics of this two types, it's hybrid**
  
  <hr>

  ### currency converter pseudocode
  > a pseudocode is the way of describing the steps of an algorythm to solve a problem, without using a programming language itself
  
  ```
  #### n1 = usd to convert
  #### n2 = btc price
  #### converted = usd to btc converted
  
  start
  print introduce the amount in usd for converting to btc
  n1 <--- get
  print converting the amount in usd to btc
  n2 <--- get (www.btcprice.com.ve)
  converted <--- n1 * n2
  print converted
  end
  ```    
