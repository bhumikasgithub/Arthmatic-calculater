<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>js</title>
    </head>
    <body>
        <h3></h3>
       <label>First number</label><br>
       <input type="text" id="firstNum"/><br> 
       
       <label>Second number</label><br>
       <input type="text" id="secNum"/><br>
      <!--<button onclick="document.write(parseInt(firstNum.value)+parseInt(secNum.value))">Add</button>-->
      <!--<button onclick="alert(parseInt(firstNum.value)+parseInt(secNum.value))">Add</button>-->
      <button onclick="result.value=parseInt(firstNum.value)+parseInt(secNum.value)">Add</button>
      <button onclick="result.value=firstNum.value-secNum.value">sub</button>
      <button onclick="result.value=firstNum.value*secNum.value">prod</button>
      <button onclick="result.value=firstNum.value/secNum.value">div</button>
      <button onclick="result.value=firstNum.value%secNum.value">Mod</button>
      <br><br>
      <output id="result"></output>
     </body>
</html>
