<html>
<titleWord Template</title>
<meta charset="UTF-8">
<style>
body {font-family: "Raleway", Arial, sans-serif}
.w3-row img {margin-bottom: -8px}
</style>
<body>

 

  <p>Word in English can have a Prefix, Middle Part and Suffix, Use the dropdown
to form a word. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </p>

<select id="mySelect" onchange="myFunction()">

<option value=" "></option>
  <option value="Enjoy">Enjoy</option>
  <option value="Amuse">Amuse</option>
  <option value="Punish">Punish</option>
  <option value="Excit">Excit</option>
  <option value="Measure">Measure</option>
  <option value="Achieve">Achieve</option>
  <option value="Commit">Commit</option>
  <option value="Embarrass">Embarrass</option>
  <option value="Manage">Manage</option>
  <option value="Hope">Hope</option>
  <option value="Care">Care</option>
  <option value="Rest">Rest</option>
  <option value="Taste">Taste</option>
  <option value="Pain">Pain</option>
  <option value="Home">Home</option>
  <option value="End">End</option>
  <option value="Fear">Fear</option>
  <option value="Use">Use</option>
  <option value="Help">Help</option>
  <option value="Re">Help</option>
  <option value="En">En</option>
  <option value="Con">Con</option>
  <option value="Be">Be</option>



</select><select id="mySelect1" onchange="myFunction1()">
  <option value=" "></option>
  <option value="ment">ment</option>
  <option value="less">less</option>
  <option value="claim">claim</option>
  <option value="new">new</option>
  <option value="joy">joy</option>
  <option value="form">form</option>
  <option value="hold">hold</option>
   <option value="fair">fair</option>

</select>

 <select id="mySelect2" onchange="myFunction2()">
  <option value=""></option>
  <option value="able">able</option>

</select>
<p id="demo"> </p>
<p id="demo1"> </p>
 

 











<script>
function myFunction() {
  var x = document.getElementById("mySelect").value;
  var y = document.getElementById("mySelect1").value;
  var z = document.getElementById("mySelect2").value;
  document.getElementById("demo").innerHTML =  "Word is " + x +y +z;

}
function myFunction1() {
  var x = document.getElementById("mySelect").value;
  var y = document.getElementById("mySelect1").value;
  var z = document.getElementById("mySelect2").value;
  document.getElementById("demo").innerHTML =  "Word is " + x +y +z;

}
function myFunction2() {
  var x = document.getElementById("mySelect").value;
  var y = document.getElementById("mySelect1").value;
  var z = document.getElementById("mySelect2").value;
  document.getElementById("demo").innerHTML =  "Word is " + x +y +z;

}








</script>




</body>
</html>
