# camara-en-perspectiva

void setup(){
size(640,360,P3D);

}
void draw(){
background(0);
camera(320,mouseY,mouseX,width/2,height/2,0,0,1,0);
translate(width/2,height/2,-100);
stroke(255);
noFill();
box(200);

}
