# Gesture Controlled Rover
This is an Arduino four-wheeled rover that is controlled via an accelerometer - hence, gesture controlled. Bluetooth modules on the controller and the rover communicate with each other to send and recieve commands respectively. Ultimately, by tilting the controller, I can make the rover move forwards, backwards, right, left, freeze, and stop. As a modification, I added an ultrasonic distance sensor to prevent head-on collisions with objects. 

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Zuri Y. | Stanford Online High School | Aerospace Engineering | Incoming Junior

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**


  
# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE



# Second Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/nz1h3VtZ7I8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

My second milestone was assembling the bluetooth controller
- This consists of wiring an Arduino Micro, accelerometer, and bluetooth module to a breadboard.
- There is a second bluetooth module on the rover, connected to the Uno. 
- Bluetooth modules will only succesfully sync if both wires connecting to EN are left floating. 
- All commands and wiring that I used/did are in my Milestone 2 video.
- You can keep the controller connected to a port (via the Micro's USB), but I wired it so that it connects to a battery pack instead for convenience.
- Since I am almost done, I will focus on finding stable places to place all my componenets and also start considering modifications. 

<img src="solder.png" width="560" height="315" />

Soldering accelerometer


<img src="control.png" width="560" height="315" />

Wired controller


# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/0JvK0g1WN4c" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

My first milestone was assembling the rover and getting it to move. 
- This consists of assembling the physical body of the rover, attatching motors, and wiring to the motor driver and Arduino Uno.
- One battery pack was not enough voltage, so I used two.
- I then connected the Arduino Uno and uploaded movement code.
- In the future, I hope to find a neater arrangement for my wires. 

<img src="motor.png" width="560" height="315" />

Assembled body of rover


<img src="body.png" width="560" height="315" />

Motors added


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
| Car Chassis Kit | Building the body of the car (including motors) | $18.99 | <a href="https://www.amazon.com/gp/product/B06VTP8XBQ"> Link </a> |
| Motor Drive Board | Controlling motors | $6.99 | <a href="https://www.amazon.com/Qunqi-Controller-Module-Stepper-Arduino/dp/B014KMHSW6/ref=asc_df_B014KMHSW6/?tag=hyprod-20&linkCode=df0&hvadid=167139094796&hvpos=&hvnetw=g&hvrand=13469222211329594770&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9032008&hvtargid=pla-306436938191&psc=1"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
