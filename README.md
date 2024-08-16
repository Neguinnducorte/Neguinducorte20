# Neguinducorte20
<!DOCTYPE html>
<html lang="en">
<head>
<script
src="https://cdnjs.cloudflare.com/ajax/libs/p5.js
/1.9.2/p5.js"></script>
<script
src="https://cdnjs.cloudflare.com/ajax/libs/p5.js
/1.9.2/addons/p5.sound.min.js"></script>
<link rel="stylesheet" type="text/css"
href="style.css">
<meta charset="utf-8"/>





function setup() {
  createCanvas(400, 400);
  background("red");
}

function draw() {
  stroke("white");
  fill("black");
  
     if(mouseIsPressed) {
     rect(mouseX, mouseY, 20, 20);
  }
}
