void setup(){
  size(400,400);
  background(0,250,255);
}
void draw(){
fill(0,255,0);
//Legs
triangle(225,290,240,270,270,340);
triangle(175,290,160,270,130,340);
triangle(270,340,260,330,230,400);
triangle(130,340,140,330,170,400);
//Body
ellipse (200,240,100,120);
//Head
ellipse (200,160,120,80);
//Arms
triangle(160,210,150,230,100,170);
triangle(240,210,250,230,300,170);
//Eyes
fill(255,255,255);
ellipse (240,120,40,40);
ellipse (160,120,40,40);
line(150,115,150,125);
line(250,115,250,125);
//Face
fill(255,182,193);
ellipse(160,160,20,10);
ellipse(240,160,20,10);
fill(255,0,0);
triangle(200,160,170,180,230,180);
}
