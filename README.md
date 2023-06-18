# Ex.07 JavaScript - Simple Calculator
## AIM
  To write a program in JavaScript for implementing a simple calculator.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to implement the simple calculator.

### STEP-3
  Using branching statements to find the corresponding operation.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
<html>
<head>
<script type="text/javascript">
function calc()
{
var a=prompt("Enter 1st Value");
var b=prompt("Enter 2st Value");
var op=prompt("Enter Operation to Perform 1.Addition 2.Subtraction 3.Multiplication 4.Division");
var d;
if(op==1)
{
d=a+b;
alert(d);
}
else if(op==2)
{
d=a-b;
alert(d);
}
else if(op==3)
{
d=a*b;
alert(d);
}
else if(op==4)
{
d=a/b;
alert(d);
}
else
{
alert("Invalid Operation");
}
}
</script>
</head>
<body onload="calc()">
<h1>
Simple Calculator
</h1>
<hr color="red">
<p> 
Enter option for doing the corresponding operation
</p>
</body>
</html>



## OUTPUT
![image](https://github.com/sharaneeya/Ex07_Web-Design/assets/119670918/0525d5ca-4a79-43f4-8ed2-f9ff6fdedf88)
![image](https://github.com/sharaneeya/Ex07_Web-Design/assets/119670918/eeed17ed-6938-4aae-84dc-6dfd2bf842ac)
![image](https://github.com/sharaneeya/Ex07_Web-Design/assets/119670918/b30fd56d-dcc3-40f8-9cec-06bd43c8c70b)
![image](https://github.com/sharaneeya/Ex07_Web-Design/assets/119670918/11e12dee-512e-43bb-abaa-f98453d31e9e)
![image](https://github.com/sharaneeya/Ex07_Web-Design/assets/119670918/8dc1fdf0-09e3-48b5-a32d-b28d2055f216)







## RESULT
  Implementation of a Simple Calculator using JavaScript is done successfully.
