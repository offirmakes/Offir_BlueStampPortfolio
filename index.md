# Pen Plotter Project
Imagine a robot that can draw any image you want, with maximum precision, and moderate speed. The pen plotter machine accomplishes just this! It is based upon two motors, responsible for moving the machine upon the x and y coordinates, and a steering gear to lift the pen up and down, all connected to an arduino board.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Offir C | Mountain View High School | Computer Science | Incoming Junior

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Final Milestone
For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Second Milestone
For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# First Milestone
Overview:

For milestone 1, I completed all the hardware invovled with my pen plotter project. This meant that I built all the components, attached them together, and completed all the electrical wiring. 

Design:

To build this project, I first needed to build the 5 main componets. This included building the frame and parts for the two motor components, building the component for the pen holder, constructing the piece opposite to the oen holder, just to keep the machine stable, and the center piece, which connects all the different components together. Afterwards, I attached all the different components together via the 4 steel rods. These steel rods pass through all the components and connect them. Then, I simply installed the timing belts, which is what the motors would be moving and consequently the machine too. Finally,I just had to install the electrical wirings for the motors, and steering gear, and attachem them to the arduino. 

Challenges:

I faced many issues when building this project. To begin, there were many screws and hex nuts which were placed in very obscure angles and were thus very hard to tighten. In addition, when I started this project, I failed to remove the stickers placed on the steel to protect it. This meant that I had to dismantle some of the compenents that I built in order to remove.

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/CaCazFBhYKs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Starter Project - Weevil Eye LED Bug
Design:

The premise of this project was to have two leds light up when it is dark. The light would be received by a photocell, which would generate electricity. If the generated electricity would be within a certain voltage, the transistor would switch on. Afterwards, there would be three resistors which would limit the current. Finaly, the current would light up the leds. I installed all these components via soldering.

Challenges:

While making this project, I encountered various issues. The first of these challenges came up, when I actually finished the project, but instead of the weevil eye only lighting up when it was dark, it always light up. The staff and I determined that the transistor was broken, and we needed to replace it. Thus, we tried to desolder the battery and transistor, but unfortunately, during the process we burned the photocell and had to re-start. The 2nd attempt was much more successful. I did encounter one issue though, in which I accidently install the photocell upside down. Fortunately, this was easily fixed as all I needed to do was de-solder it and re-attach it the right way up. Then I just attach the battery holder and it worked!

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
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
