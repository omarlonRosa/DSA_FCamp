
 #  Data Structures an Introduction 
A data structure (DS) is a way of organizing data so that it can be used effectivelly. 

## why Data Structures?

They are essential ingredients in creating fast and powerful algorithms. 

They help to manage and organize data.

They make code cleaner and easier to understand. 

# Abstract Data Types vs. Data Structures. 

## Abstract Data Type

 An *abstrcture data type* (ADT) is an abstraction of data structure which provides only the interface to which a data struture must adhere to.

 The interface does not give any specific details about how something should be implemented or in what programming language.  

 ### Examples 
| Abstraction (ADT)  |                      Implementation (DS)                      |
|:------------------:|:-------------------------------------------------------------:| 
|        List        |                   Dynamic Array Linked List                   |
|       Queue        | Linked List based Queue, Array based queue,Stack based Queue  |
|        MAP         |                Tree Map, Hash Map/ Hash Table                 |
|      Vehicle       |                 Golf Cart, Bicycle, Smart Car                 |

## Complexity Analysis 

 As prorammers, we often find ourselves asking the same two questions over and over again: 

How much <span style="color:orange">**time**</span> does this algorithm need to finish?

How much <span style="color:orange">__space__ </span> does this algorithm need for its computation?

## Big-O Notation 

 Big-O Notation gives an uppper bound of the complexity in the <span style="color:green">__worst__ </span> case, helping to quantify perfomance as the input size becomes <span style="color:green"> __arbitrarily large__ </span>. 
   
 n - The size of the input <br>
Complexities ordered in from smallest to largest.
<div style="text-align:center">
Constant Time:  <span style="color:orange"> O(1) </span>. 

Logarithmic Times: <span style="color:orange"> O(log(n)) </span>.

Linear Time: <span style="color:orange"> O(n) </span>.

Linearithmic Time: <span style="color:orange"> O((n)) </span>.

Quadric Time: <span style="color:orange"> O(n²) </span>.

Cubic Time: <span style="color:orange"> O(n³) </span>.

Exponential Time: <span style="color:orange"> O(bⁿ)</span>, b > 1.

Factorial Time: <span style="color:orange">0(n!)</span> 
</div>

### Big-O Properties 
  O(n+c) = <span style="color:orange">O(n) </span> <br>
        O(cn) = <span style="color:orange">O(n)</span>, c > 0 <br>

Left f be a function that describes the running time of a particular algorithm for an iknput of size n:<br>
         f(n) = 7log(n)³ + 15n² + 2n³ + 8 <br>
                 O(f(n)) = <span style="color:orange">O(n³)</span>

 <!-- Pratical example coming up don't worry. --> 

The following run in linear time: <span style="color:orange">O(n) </span> 
 <div style="display:inline-flex; justify-content: space-between;">
    <div style="width: 45%;">
             i := 0
             <span style="color:red"> While </span> i < n <span style="color:red"> Do </span> <br>
                 i = i + 1
                    f(n) = n 
                  O(f(n)) = <span style="color:orange"> O(n)</span>
                    
   </div>
   <div style="width: 45%;">
             i := 0
             <span style="color:red"> While </span> i < n <span style="color:red"> Do </span> <br>
                 i = i + 3
                    f(n) = n/3 
                  O(f(n)) = <span style="color:orange"> O(n)</span>
                    
  </div>
</div>
