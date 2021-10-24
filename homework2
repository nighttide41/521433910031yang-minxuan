int t=0;
void setup () {
  size(800,800);
  background(0);
  frameRate(50);
}
void draw() {
  for(int i=0;i<10;i++) {  
    for(int j=0;j<10;j++) {
    if (t>255){
      t=0;
    }
    t+=5;
    fill(25*j,0.3*t,25*i);
    noStroke();
    ellipse(80*i+40,j*80+40,60,60); 
    }
  }
}
