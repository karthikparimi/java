<html>
<body>

<h1>JavaScript Array Integers Assignment</h1>

<h2>Original Array Numbers</h2>
<p id="orig"></p>
<h3> Only Even Numbers in Array </h3>
<p id="demo"></p>

<script>

var origArray = [1,2,3,4,5,6,7,8,9,10,100,101,112,113];

var len = origArray.length;

var newArr = origArray.filter(function(num){ if( num % 2 == 0 ) return num;})

document.getElementById("orig").innerHTML = origArray;

document.getElementById("demo").innerHTML = newArr;

</script>


</body>
</html>


