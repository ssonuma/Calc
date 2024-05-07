# Ex.08 Design of a Standard Calculator
 Date:07.05.24

## AIM:
To design a web application for a standard calculator with minimum five operations.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for creating attractive colors.

### Step 4:
Write JavaScript program for implementing five different operations.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :

```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>CALCULATOR</title>
<script>
function fn(e){
    if (e.innerHTML == '=') {
        output. value = eval (output.value);
}
else if (e.id == 'back') {
    v = output. value;
    output. value = v.substring(0, v.length - 1);
}
else if (e. innerHTML == 'C') {
    output. value = '';
}
else if (e.id == 'pi')
{
  output.value+='3.14'
}

else if(e.id == 'sin')
{
 output.value= Math.sin(output.value)
}

else if(e.id == 'cos')
{
 output.value= Math.cos(output.value)
}

else if(e.id == 'tan')
{
 output.value= Math.tan(output.value)
}
else if(e.id == 'atan')
{
 output.value= Math.atan(output.value)
}
else if(e.id == 'asin')
{
 output.value= Math.asin(output.value)
}
else if(e.id == 'acos')
{
 output.value= Math.acos(output.value)
}
else if(e.id == 'h')
{
 output.value= '6.62607015*(10**(-34))'
}
else {
    output.value += e.innerHTML;
}
}
</script>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
</head>
<body>
  <div class="bg-dark row mx-auto text-center" style="width: 24rem;border-radius: 15px;" >
    <div class="bg-dark mx-auto text-center text-white" style="width: 24rem;">SONU S (212223220107)</div>
    <div class="col-12 my-4"><input type="text" name="" id="output" style="width: 100%;height: 50px;border-radius: 25px;background-color: azure;"></div> 

<div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)" >(</div> 
<div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">)</div> 
<div class="m-3 col-2 btn btn-danger rounded-4" onclick="fn(this)">C</div> 
<div class="m-3 col-2 btn btn-danger rounded-4" onclick="fn(this)" id="back"><i class="bi bi-backspace"></i></div>
<div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this) " style="background-color: brown;" id="sin">sin</div>
<div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this) " style="background-color: brown;" id="cos">cos</div>
<div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this) " style="background-color: brown;" id="tan">tan</div>
<div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this) " style="background-color: brown;" id="pi"> π</div>
<div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this) " style="background-color: brown;" id="asin">sin<sup>-1</sup></div>
<div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this) " style="background-color: brown;" id="acos">cos<sup>-1</sup></div>
<div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this) " style="background-color: brown;" id="atan">tan<sup>-1</sup></div>
<div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this) " style="background-color: brown;" id="h">h</div>
<div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">7</div>
<div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">8</div>
<div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">9</div> 
<div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">*</div>
<div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">4</div>
<div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">5</div>
<div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">6</div>
<div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">-</div>
<div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">1</div> 
<div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">2</div>
<div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">3</div>
<div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">+</div>
<div class="m-3 col-2 btn btn-success rounded-4" onclick="fn(this)">0</div>
<div class="m-3 col-2 btn btn-success rounded-4" btn-success onclick="fn(this)">.</div>
<div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">%</div>
<div class="m-3 col-2 btn btn-primary rounded-4" onclick="fn(this)">/</div> 
<div class="m-3 col-11 btn btn-warning rounded-4" onclick="fn(this)" style="background-color:darkslategray;border-color:black ;color: white">=</div>
</div>
</body>
</html>


```

## OUTPUT:

![Screenshot 2024-05-07 040324](https://github.com/ssonuma/Calc/assets/150653312/5185e356-b177-4157-938c-678861a701b5)


## RESULT:
The program for designing a standard calculator using HTML and CSS is executed successfully.
