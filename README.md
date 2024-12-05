# Hi I'm Upasana Pradhan

Welcome to my ongoing exploration of design and technology! 🌍✨ This blog serves as a personal journal documenting my journey through various projects and progress updates as I navigate the world of design and engineering. Each week brings new challenges and insights. Through sketches ✏️, photos 📸, and detailed reports 📑, I aim to share my skills, thoughts, and experiments.

Whether it's learning to troubleshoot code 💡, prototyping physical objects 🔧, or exploring creative design processes 🎨. 

Join me as I experiment, fail, and ultimately succeed (hopefully)! 😅🙌

Below are links to each week’s progress:

- [Week 1](#report----week-1-08292024---09062024)
- [Week 2](#report---week-2-09092024-09132024)
- [Week 3](#report---week-3-09142024-09192024)
- [Week 4](#report---week-409192024-09262024)
- [Week 5](#report---week-509302024-10042024)
- [Week 6](#report---week-610032024-10102024)
- [Week 7](#report---week-710102024-10172024)
- [Week 8](#report---week-810172024-10242024)
- [Week 9](#report---week-910242024-10312024)
- [Week 10](#report---week-1010242024-10312024)
- [Week 11](#report---week-1110242024-10312024)
- [Week 12](#report---week-1211142024-11212024)
- [Week 13](#report---week-1311212024-11282024)
- [Week 14](#report---week-1411282024-12052024)

  

# Report  - Week 1 (08/29/2024 - 09/06/2024) #

### Getting to College ###

This week was all about figuring out the transport and how to get to classes the best route and on time. 

Getting used to the new means of transportation which isn't familiar to you means that you go to the stops way earlier so you don't miss the bus, it means that getting used to the way and finding alternative methods if a plan fails. (In my case, walking to school.)

<img width="400" alt="Figuring out Transportation" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/ACTransit.jpg">

### Old and New ###

This week I participated in an introductory session on Arduino except of classes. It was after my first year of engineering that I got to stay in a class as such. It was my first time ever working with an arduino, and a memory with working and basic electronics from college was reignited.

<img width="400" alt="Working with arduino" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Arduino.jpg">

### A Blank Canvas ###

A notebook to be filled with ideas. Excited with the end of the first week to be working on workshops, gearing up to the classes and the lessons ahead.

<img width="400" alt="Getting hands on THE notebook" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Notebook.jpg">

# Report - Week 2 (09/09/2024-09/13/2024) #

### Failing fast ###

Using the Rhino and Grasshopper is new, but starting to learn the software, the requirements and tutorials.

<img width="400" alt="Creating a sphere" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Rhino.png">

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

<img width="400" alt="3D Print" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/3D Print.jpg">
<img width="400" alt="Phone Stand" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/3DPrint PhoneStand.jpg">

##### The print in use: #####

<img width="400" alt="Phone stand with a phone" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/PhoneStand.jpg">
<img width="400" alt="Phone stand with Kindle" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/PhoneStandKindle.jpg">

It has been fascinating to see how digital models translate into tangible, functional objects.

# Report - Week 3 (09/14/2024-09/19/2024) #

I sucessfully printed the model for my pen stand.

<img width="400" alt="Pen Stand" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Penstand.jpg">

I wanted to create a honeycomb structure which I learned is called a geodesic structure that uses a mesh. 

<img width="400" alt="Honeycomb Geodesic" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/hexagonalmesh sketch.gif">

For that, I offset the outer circle, split it to create a mesh and extracted the face boundaries. I grafted and simplified it and then exploded for each vertex of the hexagon. The hexagon took the shape to of the sphere so I used plane fit to make it planar. I used this with the average of the vertices for the center and scaled it with a factor of 7. 
I again scaled it down to fit the inner circle lofted them and capped them to create individual hexagonal tubes that would pierce into the original phone stand.


Here is a moment in time where I was amazed by the power of Grasshopper. 

<img width="400" alt="All hexagonal tubes" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Mesh.png">

#### Final Hexagonal Mesh Geodesic Design ####

I added and created a honeycomb design with the file given to us by the professor. I was curious what my professor had originally imagined the phone stand to be used for. It was great to hear his answer that although it was intended for a phone stand, people use it as a paperweight and even a penholder.

<img width="400" alt="Pen Stand" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/honeycomb.jpg">
 
I can see myself delving deeper into generative design, where algorithms can help shape more organic and intricate forms. I also want to explore optimization techniques, using design algorithms to create models that are not only aesthetically pleasing but also structurally efficient. 

# Report - Week 4(09/19/2024-09/26/2024) #

### The Hero Shot ###
A Final Shot to document my success at the very first project.

<img width="400" alt="Phone Stand" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/FinalTDFProject01.png">

I had just printed out my stand, Chris and a fellow student helped me click good shots of the stand with a background. This was during the Laser Cutting Bootcamp. You can see a creation made using laser cutting in the reflection. (This is my reflection of the Laser Cutting Bootcamp. :) ) 

<img width="400" alt="reflection of the Laser Cutting" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/LaserCuttingBootcamp.png">

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
  <img width="400" alt="Reading Errors" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/ReadingErrors.png">
  <img width="400" alt="Handshake Connections Failed" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/CloudHandshake Failed.png">
</div>

Success! The Photon 2 printing "Hello World" with a steady delay, signaling that the basic code was finally up and running.


<img width="400" alt="Output to show hello world" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/SecondFile.gif">


Output for third file with delay: In this third iteration, the delay was adjusted to demonstrate controlled output timing. Execution of the delayed response.

<img width="400" alt="Output for Thinrd file with delay" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/DelayThirdFile.gif">


Now I was on to the important part, building the physical circuit connections for the Photon 2 was crucial to ensuring all components communicated as expected.

<img width="400" alt="Making connections to build the circuit" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/MakingConnections.jpg">

Creating a button to press and the light up the bulb. Following the image provided to create this.

<img width="400" alt="Connecting the Photon2" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/ConnectedPhoton.jpg">


Once I was able to compile a few files, I really felt like a maker.

<img width="400" alt="All files compiled" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Maker.png">

A simple input interaction—pressing a button and logging the data—proving that the system was ready to respond to user inputs.

<img width="400" alt="Pressing a button and logging" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/ButtonPressed.gif">

Finally, the Photon 2 blinks a bulb periodically, showcasing the controlled output functionality, much like the delayed printing of "Hello World."

<img width="400" alt="Bulb blinking periodically" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/BulbBlinking.gif">

As I keep exploring Photon 2, I’m curious how better cloud connections could make things run more smoothly. In the future, I hope to find ways to fix errors faster and improve how devices connect.

### 1. Button -> LED pulse rate ###
I turned on the verbose setting on my VS code so I had a lot of warning and feedback when my project was compiling.

Error: 
* 'buttonPressed' was not declared in this scope 21 | attachInterrupt(buttonPin, buttonPressed, RISING); //attach an interrupt to the button pin, based on the rising edge *

The error 'buttonPressed' was not declared in this scope means that the function buttonPressed is being used before it is  defined in the code. The compiler doesn't recognize the function at the point where it's called.

<img width="400" alt="Bulb blinking periodically" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/ButtonPressedLED.jpg">

This image shows the LED blinking at a set interval when the button is pressed. After solving the error, the interrupt worked as expected, and the LED blinked based on the pulse rate.

<img width="400" alt="Bulb blinking periodically" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets.jpg/Press.jpg">

LED blinking rapidly in response to button presses.

<img width="400" alt="Bulb blinking periodically" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/FastBlinkButton.gif">

### 2. FSR -> LED color  ###

I used a force-sensitive resistor (FSR) to control the color of an LED. This interaction allows the pressure applied on the FSR to influence the color output

<img width="400" alt="Bulb blinking periodically" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets.jpg/Pressure-LED.jpg">

By applying pressure to the sensor, I was able to change the intensity of the signal being sent, which in turn affected the LED color.

<img width="400" alt="Bulb blinking periodically" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/ColorChanging.gif">

### 2. Button send-on-change  ###

Another aspect I explored was the "send-on-change" feature, which only triggers when a button state changes. This optimizes feedback loops, as the system doesn’t continuously send data unless there’s a relevant change in input.

<img width="400" alt="Button Response" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/ButtonStateChange.jpg">

<img width="400" alt="State change Video" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/ButtonOnSendVideo.gif">

From button interactions to sensor-driven LED changes, I learned the prcess of feedback making the connection between physical input and digital response .

# Report - Week 6(10/03/2024-10/10/2024) #

### Refining what you learn ###
Getting comfortable with soldering and follwing along the video to ensure stability and avoid future issues.

<img width="400" alt="soldering" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/SolderingTimelapse1.gif">

<img width="400" alt="stemma" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/stemma.jpg">

The accelerometer and gyrometer working together to capture motion data. Testing these sensors helped me understand how I can accurately read and use real-time motion and orientation data in my project.

<img width="400" alt="accelerometer and gyrometer " src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Accel_gyro.gif">


This proximity sensor measures how close an object is. By integrating it into my setup, I was able to test its responsiveness and accuracy for detecting distances.

<img width="400" alt="Proximity value" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Proximity.gif">


#### Difference between Qwiic and STEMMA QT ####

Qwiic focuses on I2C devices and uses only 3.3V logic, making it simpler but limited to 3.3V systems.
STEMMA and STEMMA QT offer more versatility, supporting both I2C and non-I2C devices, with STEMMA QT being Qwiic-compatible. It also handles both 3.3V and 5V logic, providing more flexibility across different projects.

# Report - Week 7(10/10/2024-10/17/2024) #

### Building an Interactive Environment

For our second project, we're focusing on creating an interactive environment that collects, processes, and displays data using multiple inputs and outputs. Our system is designed to monitor a baby’s sleep or track their pulse rate—even when the parents are not physically present. This setup allows real-time monitoring, giving parents peace of mind by providing health and environmental data remotely.

We want to combine sensors, cloud connectivity, and feedback mechanisms, using Particle Photon 2 devices as the central hub for communication and data collection. The system will process inputs, send data to the cloud, and provide real-time feedback, all while enabling remote monitoring.

All of this data is transmitted to the cloud, where it’s processed and returned to you in real-time via a display or haptic feedback system (like a vibrating motor). You receive alerts if any irregularities occur, such as a higher-than-normal heart rate or sudden movements.

<img alt="Proximity value" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/DiagramProject 2.png">

Below is a breakdown of the components we'll be using:

#### Input
Analog Input (ADC)
Pulse Rate Sensor
Monitors heart rate and sends data to the system for health tracking.

Loudness Sensor
Measures sound levels in the environment and converts them into readable data.

PIR (Pyroelectric Infrared) Motion Detector
Detects motion using infrared technology, useful for sensing movement in a defined space.


#### Request 

Health API
Sends health-related data requests to an external API for processing.

Particle Cloud Services
Handles data transmission and communication between devices and the cloud for real-time processing.

Particle Photon 2
Main microcontroller for collecting sensor data and managing communication with the cloud.


#### Output

Haptic Driver Board (STEMMA QT)
Controls haptic feedback devices like vibration motors to provide tactile feedback.

Monochrome 1.3" OLED Graphic Display
Displays real-time data from sensors and cloud interactions in a visual format.

PWM 
Vibrating Mini Motor
Provides physical feedback through vibrations, enhancing interactivity.

### Progress So Far

#### Sensor Setup:
All sensors, including the pulse rate sensor, loudness sensor, and motion detector, have been connected to the Particle Photon 2 devices for data collection. We are getting the analog 

<img width="400" alt="Getting all the input to work" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/GettingInput.gif">

#### Cloud Connectivity:
We successfully connected all the Particle Photon 2 devices to the cloud using Wi-Fi, enabling communication between the system and cloud services.

#### Data Transmission:
We are now able to publish data from the sensors to the cloud and subscribe to receive feedback, enabling a two-way communication loop.

<img width="400" alt="accelerometer and gyrometer " src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Connecting2Photon.gif">

Next we are moving on to the integration and the fabrication for the project. One challenge we've been working through is ensuring that the OLED Graphic Display correctly displays real-time sensor data. We encountered some issues where the display. We're actively troubleshooting and expect to have these issues resolved soon to provide accurate real-time visual feedback.


# Report - Week 8(10/17/2024-10/24/2024) #

# Weekly Report: Baby Monitoring System – Project Exploration and Insights

This week, I focused on building a **Baby Monitoring System** that uses IoT to remotely track a baby’s pulse, sound levels, and movement. My work involved setting up cloud connectivity, calibrating sensors, and achieving real-time feedback, all critical steps for creating a responsive system. Here’s how each experiment unfolded:

<img width="400" alt="prototype" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Proto1.png">

I began by setting up **Particle Cloud Services** for real-time data flow. The goal was to sync each sensor (pulse, sound, and motion) with the cloud, publishing updates every five seconds. After a few troubleshooting rounds, I established a stable connection that provided consistent data, enabling real-time updates on the OLED display—a significant step for remote monitoring.

Configuring the sensors brought unique challenges. The **pulse rate sensor** was initially incompatible with the PulseSensor_Spark library, so I switched to a custom BPM calculation. I implemented a counter-based method to detect beats and calculate BPM accurately, adjusting thresholds and using debouncing for reliability. The **loudness sensor** required setting a threshold of 500 (in a 0–1023 range) to detect typical baby sounds like crying, which we calibrated through multiple sound tests. The **PIR motion detector** worked well as a binary sensor, effectively signaling movement.

<img width="400" alt="loudness2" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Loudness_value.png">

Troubleshooting the **OLED display** proved essential to providing clear, real-time visuals of sensor data. I debugged I2C connections and optimized the refresh rate to ensure consistent display updates. With the display now synced, it reliably shows pulse rate, sound levels, and motion changes, bringing an essential layer of functionality to the system.

BPM calculations took a few iterations to perfect. I started with the PulseSensor library, shifted to a 10-second averaging method, then finally adopted a counter-based formula:
\[
BPM = \frac{60000}{\text{beatInterval}}
\]
This method offered accurate, real-time updates without delays, marking a big improvement in the system’s responsiveness.

To enhance alerts, I connected the **Haptic Driver Board** and vibrating motor, adding tactile feedback to signal significant events like loud noises or high BPM readings. Integrating haptic feedback added an interactive element, instantly notifying users of critical changes.

<img width="400" alt="prototype 2" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Proto2.png">



## Reflections and Future Directions

This week taught me a lot about managing cloud services, handling real-time data, and configuring sensors accurately. Looking forward, I see potential in integrating **machine learning** to refine detection patterns, such as distinguishing specific sounds. Additionally, linking with the **Google Fitness API** could offer a holistic health view, combining sensor data with broader metrics. Expanding the system’s application to elderly care would be another meaningful direction, using similar components to monitor vital signs and improve care.


<img width="400" alt="prototype" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Intermediate1.png">

By the end of the week, I had a fully functioning prototype with synchronized real-time data display and tactile alerts, marking an exciting step forward in IoT for health monitoring.

<img width="400" alt="" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Final1.png">
<img  alt="final prototype" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Final2.png">
<img width="400" alt="final prototype" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Final3.png">
<img width="400" alt="prototype" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Demo.png">

# Report - Week 9(10/24/2024-10/31/2024) #

### Exploring RAG and LLM

This week, I worked through a tutorial focused on tuning similarity scores for more effective query results. The tutorial led me through adjusting parameters—like similarity thresholds—and seeing their impact on search outputs.

<img  alt="zero-width" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/image 9.png">

Through trial and error, I began to understand how changing similarity scores and re-running queries directly impacted the information returned. This iterative approach to refining queries gave me insight into the balance between model settings and the relevance of search results. 

I followed along the tutorial that TJ had provided to learn more on temperature control and more.

**Reflection**: Experimenting with threshold adjustments and similarity metrics opened up ways to control how information is retrieved, providing a clearer view of query customization. Moving forward, I’m curious to explore factors like model temperature or alternative model configurations to optimize search precision.

# Report - Week 10(10/31/2024-10/07/2024) #

## Building Oopsiedaisies – Creating a Conversational Digital Persona


<img width="640" alt="Conversational Digital Persona" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Week10OopsieDaisies.png">

This week, I embarked on developing **Oopsiedaisies**, my conversational digital persona, using **ZeroWidth** and advanced tools like **Large Language Models (LLM)** and **Retrieval-Augmented Generation (RAG)**. My goal was to create a responsive, friendly, and context-aware agent capable of reflecting my personal design journey.


<img width="640" alt="Perry the platypus" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Week10Challenge Level.png">
<img width="640" alt="Diagrammatic representation" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Week10Diagram.png">


The journey started with **sandboxing in ZeroWidth**, where I set up five experiments to explore different facets of conversational AI. I began by selecting an appropriate LLM from options like **GPT-4o**, **GPT-4 Mini**, and **GPT Turbo**. Each model offered a unique balance of depth, creativity, and clarity. After rigorous testing, I opted for a balanced approach, leaning toward **GPT 4o**.

<img width="640" alt="Comparision of responses of model" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Week10ResponseComparision.png">

To refine Oopsiedaisies' conversational ability, I experimented with **temperature control**. Adjusting the temperature allowed me to tweak the agent's tone—lower temperatures produced concise, precise answers, while higher settings brought creative, but occasionally erratic, responses. Striking a balance here was key to maintaining Oopsiedaisies’ approachable and upbeat personality.

<img width="640" alt="Experiment2" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Week10Experiement2.png">

One of the highlights was **integrating instructions** to define the agent’s personality traits. I crafted prompts that ensured the tone was friendly yet informative, aligning with my design philosophy. However, for more personalized and context-rich interactions, I needed a knowledge base.

<img width="640" alt="Experiment3" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Week10Experiment3.png">

## Adding Knowledge and Real-World Applications

This week, I focused on expanding Oopsiedaisies' capabilities by integrating a **personalized knowledge base** using **RAG**. I converted various documents—like my **GitHub blogs**, **resume**, and **portfolio**—into raw text to serve as a foundational knowledge base. This integration enabled the persona to provide contextually relevant and specific answers, making interactions more authentic.


<img width="640" alt="Knowledge chunking" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Week10Chunking.png">
<img width="640" alt="Knowledge chunks" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Week10Chunks.png">

I introduced **variables** into the system, allowing for dynamic responses based on context, such as location or year. This added a tailored layer to the agent’s output, making it feel responsive and personalized.

<img width="640" alt="Experiment4" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Week10Experiement10.png">

Testing Oopsiedaisies involved evaluating responses against baseline questions, such as:
- "What is your purpose?"
- "Who are you representing?"
  
I also included custom questions about my own work to test adaptability. For example, I asked about specific challenges in past projects and assessed the agent’s ability to provide detailed, accurate answers.

Finally, I applied these learnings to a real-world use case: **Oopsiedaisies as a voicemail assistant**. I imagined how it could screen calls, prioritize urgent messages, and handle routine inquiries. This experiment required balancing personality with clarity, ensuring responses were friendly but concise.

<img width="640" alt="Experiment5" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Week10Experiement5.png">

---

### Reflections and Future Directions

These two weeks taught me the importance of **balancing creativity and structure** in conversational AI. While tools like temperature control and RAG significantly enhance interactions, crafting concise and relevant responses remains a challenge.

Looking forward, I plan to:
1. Expand the knowledge base for broader context-awareness.
2. Explore integrating machine learning for real-time adaptability.
3. Refine the voicemail assistant idea for practical applications in communication.

The process of building Oopsiedaisies was both technical and creative—a perfect intersection of systems thinking and personal design philosophy. It’s exciting to see how AI tools like this can shape human-centered digital communication.


# Report - Week 11(11/07/2024-11/14/2024) #

This week was non instructional yet I spent it in preparation for the 4th and Final Project.

Besides TDF, Fabricating laser cut boxes and foam core boxes or Studio was also something fun and I feel Like I'm learning and applying all the skills that I have gainer throughout this semester.

<img width="400" alt="Foam Core boxes" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Boxes.png">

<img width="400" alt="Lasercut box" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/BoxUpa.png">

<img width="400" alt="2 laser cut box" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Iteration.png">


Over the weekend, me and a few classmates also took part in the Designathon. It was great with over 40 teams participating to solve a problem for WOMP: 3D Modeling Software

"HMW better intuitively communicate that Womp simplifies 3D design for users with all skill levels?"

<img width="640" alt="Womp Coach" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/WompCoach.png">

We identified the major pain point and were able to secure First Place. Yayyy!!!
<img width="640" alt="Designathon Winners" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Winners.jpeg">


### Onto the Next One!!!!!


# Report - Week 12(11/14/2024-11/21/2024) #


## Exploring Ideas for Smart Technologies and Final Project

This week started with a lot of exploration and inspiration from the environment, museums and internet.


<img width="640" alt="Door Knobs" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Door Knobs.jpg">

<img width="400" alt="Gesture sentive device" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Gesture inspiration.png">

With few inspirations, I can up with a few ideas:

<img width="640" alt="Singing bowl with pendulum mallet" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Literal Singing Bowl.png">


<img width="640" alt="Motorized Key holder" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Motorized Key holder.png">



<img width="400" alt="Push button form factor" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Form Factor.png">



For my pin up , I focused on the concept of **Safe Streets**, inspired by integrating **IoT and AI-driven systems** to improve pedestrian safety. The idea revolves around creating a **handheld pedestrian push button** that provides real-time crossing guidance for visually impaired pedestrians or individuals navigating complex urban environments. The device integrates **gesture sensors**, **proximity sensors**, and **AI-driven voice guidance**, ensuring adaptive safety solutions based on live traffic conditions.

<img width="640" alt="Draft for push button" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Draft for Push Button.png">





As part of the system design, I included integrating **AI voice guidance**, which leverages LLMs to provide adaptive instructions based on live traffic data. I also sketched the initial form factor of the handheld device, emphasizing ergonomics and functionality.

<img width="640" alt="Push button" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Interactionof Push Button.png">



### Augmenting Environments for Elderly Care

After the pin up session, I teams with Joseline and Hongxi and tried to put our minds together to solve the problem space of **elderly care**,  

After a day of brainstoring and mapping journeys we decided on developing a **wearable shoe insole** with IoT capabilities. Our objective is to empower elderly individuals by monitoring their movement patterns through a Photon2-powered insole, integrated with sensors and a cloud-connected system. My part in the project involved coding and cloud communication for the insole prototype.

<img width="640" alt="Augmenting the enviroment with touchpoints" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Augmenting Environment.png">

<img width="640" alt="Identifyling transitionary zones" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Transitionary zones.png">


We conducted research on the technology that has been developed already and how we can measure data outputs and integrating them with the cloud for machine learning development.

The biggest challenge lay in calibrating the sensors to detect subtle movement patterns while maintaining data accuracy. Also identifyling proper sensors as well.

I also attended the Design field notes and with the speaker Irmandy Wickaksono who worked expansively with fabric and textile macroelectronics and learned more on Electronic Textiles as well.

<img width="640" alt="Identifyling transitionary zones" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Fabric Inspiration.png">

<img width="640" alt="Identifying transitionary zones" src="https://github.com/Berkeley-MDes/tdf-fa23-upasanapradhan/blob/main/assets/Insole Exploration 1.jpg">


### Reflections and Speculations

This week highlighted the intersection of **IoT, AI, and user-centered design**. For our final project, I envision further development of voice guidance systems to include adaptive responses for more diverse explorations

# Report - Week 13(11/21/2024-11/28/2024) #


## Refining Elderly Care Insole Prototype

This week, my primary focus was on refining the **IoT-enabled wearable insole** for elderly care. My tasks revolved around ensuring smooth integration with the **Particle Photon2** for real-time cloud communication. 

Additionally, I started drafting and refining the **system architecture diagram** to visualize the insole's data flow. This diagram maps the journey from sensor input to cloud processing and eventual caregiver notification via a mobile app. It highlights my contributions to the coding and cloud communication setup.


# Report - Week 14(11/28/2024-12/05/2024) #

## Final Week and Testing

This week marked the transition from **prototype development** to **system integration**. 

I am currently working on the **code development** for the insole’s data flow, focusing on enhancing real-time responsiveness and reducing latency in cloud communication.

Collaborating with the team, we have an idea for the **mobile interface** for caregivers. This included ensuring that sensor data displayed accurately and in near-real-time. I also worked on refining the **process diagrams** to document the flow of information from the insole to the app, emphasizing usability and data clarity.


## Week 14 (11/28 - 12/05): Integrating Location Tracking for Elderly Care

This week, we focused on adding **location tracking** functionality to the wearable insole for elderly care. The goal was to enable caregivers to monitor the **grandmother’s location** in real time, ensuring both safety and independence.

To achieve this, we integrated the **Particle Photon2** with **Google Maps** using a custom setup through the **Google Cloud Console**. Here’s an overview of the process:


1. **Setting Up the Google Cloud Console**  
   We began by creating a project in the **Google Cloud Console** and enabling the **Geolocation API**. This API provides latitude and longitude coordinates based on Wi-Fi and cell tower data.

2. **Configuring the Particle Photon2**  
   - The Photon2 was set up to collect network data from nearby Wi-Fi signals.  
   - Using the Particle Workbench, I programmed the Photon2 to send this network data to the Geolocation API for processing.


The location data needs to be returned by the API and processed and visualized on Google Maps. 

I further plan customizing the integration to allow caregivers to view the grandmother’s real-time location on their mobile devices through a **simple web-based interface** in a certain period of time.



Adding location tracking to the insole enhances its utility, providing caregivers with peace of mind while the elderly way be outside the homes.






































