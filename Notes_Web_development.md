## Javascript
What is Javascript - 
<p>"JS is the high level programming language which is used to create the dynamic web pages". Nowadays JS can also be used on server side to act as a dynamic programming language such as <b>C#</b> and <b>Java</b>.<br> One of the prime example is <b>Node</b> JS which is a framework used to create dynamic web pages. Similarly using <b>REACT</b> library we can make web as well as mobile application. <b>Electron JS</b> which is quite new is used to make the standalone desktop application</p>   

#### Data Types & Variables - 
 We need Variable to store the data.

>![Datatype](/Data_types.PNG)

---

 _Below code shows the datatypes, Loosely typed programming langauge and Dynamically typed scripting language._
 ```JS
    <script type="text/javascript">
    
        //JS Dynamically typed
        // JS automatically declare the datatype when we define the variable
        var num = 16;   // this is int
        var Name = 'Manish Padole'; //This is string
        var flag = false;   //This is Boolean
        num = 'Manish';
        
        alert(num); //This will create an alert when run the live server
```

> Output
> ![Alert](/alert.PNG)

---
#### Operators in JS
![Operators](/operators.PNG)

---
#### Arithmatic oprertions in JS

```js
let num = 12
let num2 = num++  
console.log(num,num2); 

```

_Output of the above code is_ : ![output](/arith.PNG)
<table><tr><td>
What happened in the above code is that first the we stored the variable <b>num</b> and in the next line we defined another variable <b>num2</b>. So this is a classic case of pre-increment and post-increment, the value of 12 first got fetched and then assigned the value and then post increment 
</td></tr></table>

 :warning: If we want to get the power a number we type - 
 ```js
 
 num = 2 **3 //This means we want the cube root of the 2
 ``` 
 