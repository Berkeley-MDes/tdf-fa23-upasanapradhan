
# Report  - Week 1 (08/29/2024 - 09/06/2024) #

### Getting to College ###

This week was all about figuring out the transport and how to get to classes the best route and on time. 

Getting used to the new means of transportation which isn't familiar to you means that you go to the stops way earlier so you don't miss the bus, it means that getting used to the way and finding alternative methods if a plan fails. (In my case, walking to school.)

<img width="200" alt="Figuring out Transportation" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/ACTransit.jpg">

### Old and New ###

This week I participated in an introductory session on Arduino except of classes. It was after my first year of engineering that I got to stay in a class as such. It was my first time ever working with an arduino, and a memory with working and basic electronics from college was reignited.

<img width="200" alt="Working with arduino" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Arduino.jpg">

### A Blank Canvas ###

A notebook to be filled with ideas. Excited with the end of the first week to be working on workshops, gearing up to the classes and the lessons ahead.

<img width="200" alt="Getting hands on THE notebook" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Notebook.jpg">

# Report - Week 2 (09/09/2024-09/13/2024) #

### Failing fast ###

Using the Rhino and Grasshopper is new, but starting to learn the software, the requirements and tutorials.

<img width="200" alt="Creating a sphere" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Rhino.png">

The model was complex to grasp but the video and tutorials helped me along with a few questions that I could search about. 
I started with changing the parameters for the component, what would work and what would fail.

#### Diagram to show my understanding of the model ####
This diagram display the most important features from the model. I tried to break ot dom into simple form to truly understand what is happening. This visual representation simplified the structure and made it easier for me to focus on each part of the process. It helped turn an abstract model into something more concrete, clarifying the relationships between the elements in the design.
<img alt="Flowchart" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Flowchart.png">

#### Creating a Pen Stand ####
Learned how to create my own model and progressively learned:
1. Using a cylinder shape as a void to create the basic structure.
2. Lofting centers from the top and bottom to generate smooth transitions and curves. Each new step taught me something valuable, from manipulating shapes to refining the design.

<img width="400" alt="In Rhino" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/penstandsketch.gif">

Render in Rhino:

<img width="400" alt="In Rhino" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/PenStand.png">

The diagram in grasshopper:

<img width="400" alt="The Grasshopper model" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/PenStandGrasshopper.png">

*Learning a new tool is intimidating but finding success in small step really helps you go on and try new things.*
I learned that breaking tasks into smaller steps really helps. Each success, no matter how small, encouraged me to push forward and try new things. I now have a better understanding of how to manipulate geometry in Grasshopper, and it’s exciting to see ideas come to life as I develop the model.

#### My first shot at 3D Printing ####

The fabrication class helped me a lot when I tried to print a model. I was able to get my first ever print with a 3D Printer with a model that I found on the internet. 
I plan on getiing the Pen stand 3D printed as well.

<img width="200" alt="3D Print" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/3D Print.jpg">
<img width="200" alt="Phone Stand" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/3DPrint PhoneStand.jpg">

##### The print in use: #####

<img width="200" alt="Phone stand with a phone" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/PhoneStand.jpg">
<img width="200" alt="Phone stand with Kindle" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/PhoneStandKindle.jpg">

It has been fascinating to see how digital models translate into tangible, functional objects.

# Report - Week 3 (09/14/2024-09/19/2024) #

I sucessfully printed the model for my pen stand.

<img width="200" alt="Pen Stand" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Penstand.jpg">

I wanted to create a honeycomb structure which I learned is called a geodesic structure that uses a mesh. 

<img width="200" alt="Honeycomb Geodesic" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/hexagonalmesh sketch.gif">

For that, I offset the outer circle, split it to create a mesh and extracted the face boundaries. I grafted and simplified it and then exploded for each vertex of the hexagon. The hexagon took the shape to of the sphere so I used plane fit to make it planar. I used this with the average of the vertices for the center and scaled it with a factor of 7. 
I again scaled it down to fit the inner circle lofted them and capped them to create individual hexagonal tubes that would pierce into the original phone stand.


Here is a moment in time where I was amazed by the power of Grasshopper. 

<img width="200" alt="All hexagonal tubes" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Mesh.png">

#### Final Hexagonal Mesh Geodesic Design ####

I added and created a honeycomb design with the file given to us by the professor. I was curious what my professor had originally imagined the phone stand to be used for. It was great to hear his answer that although it was intended for a phone stand, people use it as a paperweight and even a penholder.

<img width="200" alt="Pen Stand" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/honeycomb.jpg">
 
I can see myself delving deeper into generative design, where algorithms can help shape more organic and intricate forms. I also want to explore optimization techniques, using design algorithms to create models that are not only aesthetically pleasing but also structurally efficient. 

# Report - Week 4(09/19/2024-09/26/2024) #

### The Hero Shot###
A Final Shot to document my success at the very first project.

<img width="200" alt="Phone Stand" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/FinalTDFProject01.png">

I had just printed out my stand, Chris and a fellow student helped me click good shots of the stand with a background. This was during the Laser Cutting Bootcamp. You can see a creation made using laser cutting in the reflection. (This is my reflection of the Laser Cutting Bootcamp. :) ) 

<img width="200" alt="reflection of the Laser Cutting" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/LaserCuttingBootcamp.png">

### Moving from 0 to 1, now 1 to 2. ###

The system map focuses on the ecosystem formed by your AirPods or headphones and the audio/video apps (Spotify, YouTube, etc.) they interact with. Key components include the devices (AirPods, headphones, phone), content platforms (Spotify, YouTube), and sound-related system features (volume,noise , pitch)

Connections: The primary device (phone or computer) acts as the hub, connecting your AirPods or headphones to the content platforms. Information flows from the apps, playing music or videos, to your listening devices, where sound is delivered.

Information Flow: The sound (music, video audio) is streamed through apps like Spotify and YouTube, then transmitted wirelessly to AirPods or headphones. Information such as volume, sound effects, pitch, and noise alerts is dynamically adjusted based on user input and environmental factors.

Feedback Loops: As you adjust the volume, sound effects, and noise alerts, the system optimizes sound quality.

<img alt="Audio Device Network Diagram" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Audio Device Network Diagram.png">

# Report - Week 5(09/30/2024-10/04/2024) #

### Reading between the errors ###
When I first started exploring the files in home, I connected the Photon, and I was able to compile it and flash. I was missing a step though. Connecting to Wifi. Although I had not connected it to my home wifi, it still worked to my surprise. I then went on to connect the circuit. The most helpful thing during my explorations were errors. 
<div>
  <img width="200" alt="Reading Errors" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/ReadingErrors.png">
  <img width="200" alt="Handshake Connections Failed" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/CloudHandshake Failed.png">
</div>

Success! The Photon 2 printing "Hello World" with a steady delay, signaling that the basic code was finally up and running.


<img width="200" alt="Output to show hello world" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/SecondFile.gif">


Output for third file with delay: In this third iteration, the delay was adjusted to demonstrate controlled output timing. Execution of the delayed response.

<img width="200" alt="Output for Thinrd file with delay" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/DelayThirdFile.gif">


Now I was on to the important part, building the physical circuit connections for the Photon 2 was crucial to ensuring all components communicated as expected.

<img width="200" alt="Making connections to build the circuit" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/MakingConnections.jpg">

Creating a button to press and the light up the bulb. Following the image provided to create this.

<img width="200" alt="Connecting the Photon2" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/ConnectedPhoton.jpg">


Once I was able to compile a few files, I really felt like a maker.

<img width="200" alt="All files compiled" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Maker.png">

A simple input interaction—pressing a button and logging the data—proving that the system was ready to respond to user inputs.

<img width="400" alt="Pressing a button and logging" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/ButtonPressed.gif">

Finally, the Photon 2 blinks a bulb periodically, showcasing the controlled output functionality, much like the delayed printing of "Hello World."

<img width="400" alt="Bulb blinking periodically" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/BulbBlinking.gif">

As I keep exploring Photon 2, I’m curious how better cloud connections could make things run more smoothly. In the future, I hope to find ways to fix errors faster and improve how devices connect.
