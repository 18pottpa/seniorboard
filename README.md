void setup(){

size (3000,2000);

PImage unnamed  = loadImage("unnamed.jpg");

unnamed.resize(1000,650);

image(unnamed, 0, 200);

}
void draw(){
  
  fill(34,131,29);
  
  rect(0,0,3000,200);
  
  fill(0);
  
  rect(1000,0,3000,2000);
  
  PImage img2;
  
  img2 = loadImage("placeholder.jpg");
  
image(img2, 240 , 50);

fill(0);

textSize(15);

text("31",750,520);

fill(0);

line(913,410,850,305);

text("65,66,69",825,305);

line(912,395,910,350);

text("5,36,56",900,347);

text("50",900,470);

text("19",410,520);

text("62",160,390);

//fill(255);

//textSize(55);

//textAlign(CENTER);

//frameRate(1);

//int m = minute();

//int h = hour();

//String t = h + ":" + nf(m, 2);

//text (t, 1500, 50);

PImage img3 = loadImage("p1.png");

img3.resize(225,425);

image(img3,1000,0);

PImage img4= loadImage("p2.png");

img4.resize(225,425);

image(img4,1000,425);

PImage img5= loadImage("p3.png");

img5.resize(225,425);

image(img5,1225,0);

}
