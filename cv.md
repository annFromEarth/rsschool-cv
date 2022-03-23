# Anna Dvor
****
*artist* * *sculptor* *   www.annadvorart.com
****
### Why programming?
I decided to start learning programming in February 2022 to get my head busy and to stop thinking about the war. Before, I did only have a little experience with programming - in one of my art projects Arduino controllers were used to empower the lightning system.  

### Code example
The project in case was dedicated to ecological footprint of traffic, and its part was a lightning system that imitated changing air-quality index in certain locations (light was changing from green to yellow to red and back at random times, where green signalized good air quality, yellow stood for moderate air quality, and red - for unhealty). I had a crew who instructed me how to use Adafruit NeoPixel Library for controlling single wire LED pixels, and there was an abstract I had to adjust multiple times, to get the desired lightning effect:

*code extract, Arduino IDE*

```
void loop () {
  int t1=random (3300);  //time in milliseconds
  int t2=random (900);
  int t3=random (540);
  
  colorWipe(strip.Color(150, 0, 255), 10*(300+t1)); // green-ish
  colorWipe(strip.Color(255, 0, 180), 10*(300+t2)); // yellow-ish
  colorWipe(strip.Color(255, 0, 0), 10*(60+t3));  // red
  colorWipe(strip.Color(255, 0, 180), 10*(300+t2)); // yellow-ish
  }
````
## Skills
* 2d: Adobe Photoshop, Adobe Illustrator
* 3d: ZBrush, 3dsMax

## Languages
Russian - native * English - advanced
