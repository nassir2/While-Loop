

<!DOCTYPE html>
<html>

<body>

<p>While Loop</p>

<button onclick="myFunction()">Try it</button>

<p id="demo"></p>

<script>
function myFunction() 
{
    var text = "";
    var i = 0;
    while (i < 10) {
        text += "<br>The number is " + i;
        i++;
    }
    document.getElementById("demo").innerHTML = text;
}
</script>

</body>

</html>


a+=b ---> a=a+b;  

