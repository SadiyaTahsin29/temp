Quiz.app
//quiz  using html ,css//
<!DOCTYPE html>
<html>
<head>
	<title>Quiz on Artificial Intelligence</title>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<div class="container">
		<h1>Quiz on Artificial Intelligence</h1>
		<form action="submit.php" method="post">
			<h3>1. What is Artificial Intelligence?</h3>
			<input type="radio" name="q1" value="a" required> a. The simulation of human intelligence processes by computer systems<br>
			<input type="radio" name="q1" value="b"> b. The study of how to create computers that are capable of intelligent behavior<br>
			<input type="radio" name="q1" value="c"> c. Both a and b<br><br>
<h3>2. Which of the following is not a type of Artificial Intelligence?</h3>
			<input type="radio" name="q2" value="a" required> a. Reactive Machines<br>
			<input type="radio" name="q2" value="b"> b. Limited Memory<br>
			<input type="radio" name="q2" value="c"> c. Consciousness<br><br>

<h3>3. Which programming language is commonly used for Artificial Intelligence?</h3>
			<input type="radio" name="q3" value="a" required> a. Java<br>
			<input type="radio" name="q3" value="b"> b. Python<br>
			<input type="radio" name="q3" value="c"> c. Both a and b<br><br>

<input type="submit" value="Submit">
		</form>
	</div>
</body>
</html>
