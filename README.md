# simple-dice-game
This is a simple game created along side the course of Java Script of Jonas Schimedtman, for study purpouse only.

<a href="#" class="myButton">PLAY NOW</a>

.myButton {
	box-shadow: 0px 1px 0px 0px #f5978e;
	background:linear-gradient(to bottom, #f24537 5%, #c62d1f 100%);
	background-color:#f24537;
	border:1px solid #d02718;
	display:inline-block;
	cursor:pointer;
	color:#ffffff;
	font-family:Arial;
	font-size:15px;
	font-weight:bold;
	padding:14px 24px;
	text-decoration:none;
	text-shadow:0px 1px 0px #810e05;
}
.myButton:hover {
	background:linear-gradient(to bottom, #c62d1f 5%, #f24537 100%);
	background-color:#c62d1f;
}
.myButton:active {
	position:relative;
	top:1px;
}
[Play Now](https://sandrolevy.github.io/simple-dice-game/)

![game-image](https://github.com/sandrolevy/simpledicegame.github.io/blob/master/game-image.png?raw=true)




## Rules

- The game has 2 players, playing in rounds
- In each turn, a player rolls a dice as many times as he whishes. Each result get added to his ROUND score
- BUT, if the player rolls a 1, all his ROUND score gets lost. After that, it's the next player's turn
- The player can choose to 'Hold', which means that his ROUND score gets added to his GLOBAL score. After that, it's the next player's turn
- A player looses his ENTIRE score when he rolls two 6 in a row.
- The first player to reach 100 points on GLOBAL score wins the game

## Features
- Option to change the Winning Score!

