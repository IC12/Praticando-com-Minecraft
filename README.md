# Praticando-com-Minecraft

https://studio.code.org/c/1401301819

Código movimentos:

turnLeft();
for (var count = 0; count < 2; count++) {
  moveForward();
}
for (var count2 = 0; count2 < 2; count2++) {
  destroyBlock();
  moveForward();
}
turnRight();
destroyBlock();
moveForward();
turnRight();
for (var count3 = 0; count3 < 4; count3++) {
  moveForward();
}
turnLeft();
for (var count4 = 0; count4 < 2; count4++) {
  moveForward();
}
turnRight();
destroyBlock();
placeTorch();
for (var count5 = 0; count5 < 3; count5++) {
  moveForward();
}
placeTorch();
turnRight();
for (var count6 = 0; count6 < 2; count6++) {
  moveForward();
}
turnLeft();
for (var count7 = 0; count7 < 3; count7++) {
  moveForward();
}
turnRight();
for (var count8 = 0; count8 < 4; count8++) {
  ifBlockAhead("", function() {
    placeBlock("bricks");
  });
  moveForward();
}
for (var count9 = 0; count9 < 2; count9++) {
  moveForward();
}
turnLeft();
for (var count10 = 0; count10 < 3; count10++) {
  ifBlockAhead("lava", function() {
    placeBlockAhead("stone");
  });
  moveForward();
}
turnRight();
moveForward();
for (var count11 = 0; count11 < 3; count11++) {
  destroyBlock();
  moveForward();
}
turnRight();
destroyBlock();
moveForward();
turnRight();
destroyBlock();
turnLeft();
moveForward();
ifBlockAhead("lava", function() {
  placeBlockAhead("stone");
});
moveForward();
turnRight();
for (var count12 = 0; count12 < 3; count12++) {
  ifBlockAhead("lava", function() {
    placeBlockAhead("stone");
  });
  moveForward();
}
turnLeft();
for (var count13 = 0; count13 < 10; count13++) {
  moveForward();
}
ifBlockAhead("water", function() {
  placeBlockAhead("planksAcacia");
});
for (var count14 = 0; count14 < 3; count14++) {
  moveForward();
}
turnRight();
shear();
for (var count15 = 0; count15 < 2; count15++) {
  turnLeft();
}
moveForward();
turnRight();
shear();
for (var count16 = 0; count16 < 2; count16++) {
  turnLeft();
}
moveForward();
turnRight();
shear();
for (var count17 = 0; count17 < 2; count17++) {
  turnRight();
}
for (var count18 = 0; count18 < 7; count18++) {
  moveForward();
}
placeBlockAhead("dirtCoarse");
turnRight();
ifBlockAhead("water", function() {
  placeBlockAhead("planksAcacia");
});
for (var count19 = 0; count19 < 6; count19++) {
  moveForward();
}
placeTorch();
for (var count20 = 0; count20 < 3; count20++) {
  moveForward();
}
placeTorch();
turnLeft();
for (var count21 = 0; count21 < 2; count21++) {
  moveForward();
}
turnLeft();
moveForward();
