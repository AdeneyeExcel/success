# success
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h2>Success Calculator</h2>
<form>
    <div class="container">
        <h4>Number 1:</h4>    <input type ="text"id="box1"><br>

        <h4>Number 2:</h4>  <input type = "text"id="box2"><br>
    </div>


<h4>Answer</h4><input type = "text"id="+"><br>

    <input type="radio"value ="+" onclick="calcSum()" >
    <label for="+">Addition</label>

    <input type="radio"value ="-" onclick="calcDiff()" >
    <label for="-">Subtraction</label>



    <input type="radio"value ="x" onclick="calcDiff()" >
    <label for="x">Multiply</label>

    <input type ="radio"value ="/" onclick="calcdivision()" >
    <label for="/">Divide</label>
    


</form>    
<script>
    function calcSum() {

    let box1 = document.getElementById("box1"). value;
    let box2 = document.getElementById("box2"). value;
    let sum = Number(box1) + Number(box2);
    document.getElementById("+").value = sum
    }

    function calcDiff() {

    let box1 = document.getElementById("box1"). value;
    let box2 = document.getElementById("box2"). value;
    let sum = Number(box1) - Number(box2);
    document.getElementById("+").value = sum
}
function calcdivision() {

let box1 = document.getElementById("box1"). value;
let box2 = document.getElementById("box2"). value;
let sum = Number(box1) / Number(box2);
document.getElementById("+").value = sum
}


</script>
</body>
</html>
