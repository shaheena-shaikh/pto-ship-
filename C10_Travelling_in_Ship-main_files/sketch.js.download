var ship,ship1;
var sea,sea1;
function preload(){
ship=loadAnimation("ship-1.png","ship-2.png","ship-3.png","ship-4.png");
sea=loadAnimation("sea.png");
}

function setup(){
  createCanvas(400,400);
  // creating the sea;
  sea =createSprite(600,300);
  sea.addAnimation("running",sea1);
  sea.scale=0.5;
  sea.velocityX=1;

  //creating ship;
  ship=createSprite(50,200,20,50)
  ship.addAnimation("running",ship1);
  Edges=createEdgeSprites();

  //creating position of ship;
  ship.scale=0.25;
  ship.velocityY=500;
  ship.velocityX=90;
}

function draw() {
  background("blue");
 if(keyDown("enter"));
 ship.velocityX=5;

 if(keyDown("left"));
 ship.velocityX=-5;

 if(keyDown("space"));
 ship.velocityX=0;

 if (sea.X<0 );
    sea.X =sea.width/2;

 drawSprites();
}