<!doctype html>
<html lang="en">

<head>
	<!-- Required meta tags -->
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">

	<!-- Bootstrap CSS -->
	<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-BmbxuPwQa2lc/FVzBcNJ7UAyJxM6wuqIj61tLrc4wSX0szH/Ev+nYRRuWlolflfl" crossorigin="anonymous">

	<!-- My CSS -->
	<link href="CSS/styles.css" rel="stylesheet">

	<title>Tic-Tac-Toe</title>
</head>

<body>
	<div class="board circle" id="board">
		<div class="cell" data-cell></div>
		<div class="cell" data-cell></div>
		<div class="cell" data-cell></div>
		<div class="cell" data-cell></div>
		<div class="cell" data-cell></div>
		<div class="cell" data-cell></div>
		<div class="cell" data-cell></div>
		<div class="cell" data-cell></div>
		<div class="cell" data-cell></div>
	</div>
	<div class="winning-message" id="winningMessage">
	<div data-winning-message-text></div>
	<button id="restartButton">Restart</button>
	</div>

	<!-- My Javascript -->
	<script src="JS/main.js" defer></script>
</body>

</html>
