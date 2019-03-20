# SpringBootApplication
Hi I'm Khairunisa.
This is my first trial.

Requirement:
- Create a Java Spring Boot application
- Add a REST GET endpoint (/hello) which return a car object as the JSON response.
Car object should contains manufacturer(String) and name(String).


<!DOCTYPE html>
<html>
<body>

<h1>CAR manufacturer</h1>

<p>Click the button to trigger a function that will output Car Manufacturer</p>

<button onclick="()">Click me</button>

<p id="demo"></p>

<script>
function myFunction() {
	$.get('car/hello).then(function(data){
	
  	document.getElementById("demo").innerHTML = data;
}
</script>

</body>
</html>
