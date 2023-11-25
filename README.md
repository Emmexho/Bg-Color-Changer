<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Color Changer</title>
</head>
<body>
    <div id="one"></div>
   <select onchange="change()" selected id="ade" style="color: blue;">
    <option value="red">Red</option>
    <option value="blue">Blue</option>
    <option value="yellow">Yellow</option>
    <option value="black">Black</option>
    <option value="green">Green</option>
    <option value="violet">Violet</option>
   </select> 
   <a href = "sms:09042717975?body=how are you">Send a Sms</a>
</body>
<style>
    #one:hover{
        transform: rotate(360deg);
        transition: 3000ms;
        background-color: aqua;
        transition: ease-in-out 3000ms;
    }
    #one{
        background-color: rgb(35, 3, 3);
        width: 200px;
        height: 150px;
        border-radius: 30px;
        overflow:auto ;
    
    }
</style>

<script>
  function change(){
  var colex = document.getElementById("one");
   
  colex.style.backgroundColor = ade.value;
   
    }
</script>
</html>
