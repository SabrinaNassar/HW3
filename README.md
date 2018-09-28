# HW3

What code draws the blades of grass?

 stroke(random(60, 70), 100, 90);
 line(x, height-10, x + random(-10, 10), height-10-random(h));

  x = x + 10;

  if (x > width) {
    x = random(10);
    h = h + 3;
  }
  
What code makes the "lawnmower" come by? How often does it come by?

 if (random() > 0.999) {
    noStroke();
    fill(255);
    rect(-1, -1, width+2, height-15);
    h = 10;
  }
  
  
What's the point of the h variable?
It for the hight of the grass

What do the three numerical arguments of colorMode do?
Hue, Saturation, brightness, transparency

What does the -10 do in the second and fourth arguments of the line function, height-10-random(h)? Why is it there?
because the grass grows on the dirt and the number shows where the grass would grow from
