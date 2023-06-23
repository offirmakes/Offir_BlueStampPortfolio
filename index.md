# Pen Plotter Project
Imagine a robot that can draw any image you want, with maximum precision, and moderate speed. The pen plotter machine accomplishes just this! Based upon a two axis system, the pen uses an arduino board to power its motors.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Offir C | Mountain View High School | Computer Science | Incoming Junior

<!---**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Final Milestone
Overview:

For milestone 3, I desgined my project to be able to draw a custom image. 

Design:
Making the pen plotter draw any image is a multi step process.
1: Find an image, preferably not too complex and involving few colors.
2: Download inkscape and load your image. Turn on edge detection for the image and save it as a svg file.
3. Open jscut and load your svg file in. Set all measurements to mm, and create an operation. Select the engrave option, and download your file as g-code.
4. The g-code file in its current state, does not have the commands to lift the pen up and down. Thus, open an editor, I used notepad++, and replace ever instance of the retract command with M5 and M3S1000 of plunge (Ctrl H to replace).
5. Then, simply enter the g-code into a grbl software.

Challenges:
Altough this process involved a lot of steps, I only faced one major issue. When I first ran the code, the pen did not lift up at all. This was because the g-code I gave it did not contain the commands to lift the pen, instead it just said retract and plunge in a comment. I fixed this by uploading the code to notepad++ and replacing these commands with the proper line of code. This is step 4 of the process.

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

-->
# Second Milestone
<iframe width="560" height="315" src="https://www.youtube.com/embed/IUFbGnLYD8A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Overview:

For milestone 2, I implemented the software invovled with my project so that it can draw a given image. 

Design:
To build the software portion of my project, I used the candle software. The candle software uses g-code in order to direct the motors and lift the pen up. Unlike in the next milestone, the g-code was given to me, and so I just plugged the g-code into in the candle software and it worked!

Challenges:
While this process may seem simple, I did run into a few issues. At first, it draw a very messy and abstract version of my image. I was very puzzled as to why this happened, but then when I looked at the hardware I realized that the timing belt, the component responsible for moving the machine, was very loose. Turns out that I forgot to strap the timing belt to stop it from loosening out. In addition, I faced a small issue in which the pen plotter wasn't drawing the image in the middle of the page. This issue is very simple to fix as all what I needed to do was align the pen plotter a little to the left.   

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

# First Milestone
<iframe width="560" height="315" src="https://www.youtube.com/embed/OKzIARZuX_Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Overview:

For milestone 1, I completed all the hardware invovled with my pen plotter project. This meant that I built all the components, attached them together, and completed all the electrical wiring. 

Design:

To build this project, I first needed to construct the 5 main componets. This included building the frame and parts for the two motor components, building the component for the pen holder, constructing the piece opposite to the oen holder, just to keep the machine stable, and the center piece, which connects all the different components together. Afterwards, I attached all the different components together via the 4 steel rods. These steel rods pass through all the components and connect them. Then, I simply installed the timing belts, which is what the motors would be moving and consequently the machine too. Finally, I just had to install the electrical wirings for the motors, and steering gear, and attachem them to the arduino. 

Challenges:

I faced many issues when building this project. To begin, there were many screws and hex nuts which were placed in very obscure angles and were thus very hard to tighten. In addition, when I started this project, I failed to remove the stickers placed on the steel to protect it. This meant that I had to dismantle some of the compenents that I built in order to remove.

# Starter Project - Weevil Eye LED Bug
<iframe width="560" height="315" src="https://www.youtube.com/embed/RqrsvF4pcRo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Design:

The premise of this project was to have two leds light up when it is dark. The light would be received by a photocell, which would generate electricity. If the generated electricity would be within a certain voltage, the transistor would switch on. Afterwards, there would be three resistors which would limit the current. Finaly, the current would light up the leds. I installed all these components via soldering.

Challenges:

While making this project, I encountered various issues. The first of these challenges came up, when I actually finished the project, but instead of the weevil eye only lighting up when it was dark, it always light up. The staff and I determined that the transistor was broken, and we needed to replace it. Thus, we tried to desolder the battery and transistor, but unfortunately, during the process we burned the photocell and had to re-start. The 2nd attempt was much more successful. I did encounter one issue though, in which I accidently install the photocell upside down. Fortunately, this was easily fixed as all I needed to do was de-solder it and re-attach it the right way up. Then I just attach the battery holder and it worked!
<!---
# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```
# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| 2 PCS 8mm polished rods 450mm | Connecting the two motor componenets together | $11.39 | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| 2 PCS 8mm polished rods 360mm | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
-->
