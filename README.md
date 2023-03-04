# calculatrice
<!DOCTYPE html>
<html>
<head>
	<title>Calculatrice en ligne</title>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<div class="calculator">
		<div class="display">
			<input type="text" id="result" disabled>
		</div>
		<div class="keys">
			<button onclick="clearDisplay()">C</button>
			<button onclick="deleteLastDigit()">CE</button>
			<button onclick="addToDisplay('/')">/</button>
			<button onclick="addToDisplay('*')">*</button>
			<button onclick="addToDisplay('7')">7</button>
			<button onclick="addToDisplay('8')">8</button>
			<button onclick="addToDisplay('9')">9</button>
			<button onclick="addToDisplay('-')">-</button>
			<button onclick="addToDisplay('4')">4</button>
			<button onclick="addToDisplay('5')">5</button>
			<button onclick="addToDisplay('6')">6</button>
			<button onclick="addToDisplay('+')">+</button>
			<button onclick="addToDisplay('1')">1</button>
			<button onclick="addToDisplay('2')">2</button>
			<button onclick="addToDisplay('3')">3</button>
			<button onclick="calculate()">=</button>
			<button onclick="addToDisplay('0')">0</button>
			<button onclick="addToDisplay('.')">.</button>
		</div>
	</div>
	<script src="script.js"></script>
</body>
</html>
