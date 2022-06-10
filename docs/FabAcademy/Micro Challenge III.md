---
hide:
    - toc
---

# Micro Challenge  III FabAcademy

### Personal reflection

#### Context empowering by data

This Micro Challenge had the goal to create some output from a ethical perspective; is from this starting point that we developed this project.

From our last intervention at this point, we worked with a community garden in which we build with them a community compost bin, an artifact that is supposed to be used by all the members in the garden.

At this point, whit the community we identify that not all members know about the benefits of the compost or how to make it, at the same time we learn more about the participatory process that they perform around any matter of the garden.

From an ethical perspective we sought to have a tool that empower all the member of the community, so we decided that the best way to accomplish that was by disseminate all the information regarding the health of the compost, in that way everyone could know how the compost is doing and encourage discussions, actions and participation. Having from only one expert and one interested to many experts and many interested.

#### Process

We began the exploration to have a autonomous circuit powered by the sun. For the composter, the initial idea was to have a sensor that could function all the time, and sent the information to the member in a regular basis or too have a repository if the information in real time.

We have as inspiration the Smart Citizen project as well as the (Grow Observatory)[https://growobservatory.org/data/]. From this, we started to use a capacitive humidity sensor with an analog output to use it with the ESP32.
The first step was to understand how it works and the measures that are presented in the serial monitor. I choose to have a numerical output rather than the graph to understand better the information.

As all analog sensors, this one send the information from 0 to 4095, measuring the conductivity from one diode to the other, that means when the soil is wet or completely soak, the conductivity is high and when the soil is completely dry, the conductivity is almost cero.

I tested the sensor with different types of soil and I tried to set a standard for the compost soil; with Santi we started to work with a tutorial, which I explain more in the week 14, in which the ESP could function as a WebServer; with that application I can send the lecture of the sensor via Wi-Fi to an IP.

In the code I have to transformed the information from the raw values of the sensor to percentage, in that way it could be easier for the people to understand the humidity of the sensor.

When the ESP is connected to the Wi-Fi creates an IP, so everyone could access the measure of the humidity of the compost in any moment. So if connect my device to that IP I can have that information in any place.

After we make the code works, with Mikel and Víctor. I try the prototype with a battery to have autonomy and to prove it in different places without be connected to the computer.

Edu helped me in defining the best battery for the final product, I design a PCB for milling and mount the ESP with the battery and I weld the connector for the ESP and the sensor. I explain more of this in the week 10-13.

When the circuit is done with the PCB and the LiPo battery, I design a case and print it, having in mind that it has to have an easy access to the ESP to charge the LiPo battery.

easly to open to access  after this I design a case for enclosure the ESP   










#### ---- The next post is the team documentation  ----
link to repository
(https://github.com/terauchi-rei/fabchallenge3.git)

## Micro Challenge III


===============



by [Rei Terauchi](https://terauchi-rei.github.io/mdefweb/) & [Emilio Smith](https://emiliosmith.github.io/mdef_emilio2/)

## Objective

How can we activate participation in a community
Using data to encourage an activity that benefit all the members

In a community based project, we have to encourage the participation of people, we have to design the inputs that motivate people to integrate and participate for the good of the community.
When we talk about compost making, we are lacking inputs to know if we are doing well or not if we are not used to work with soil and plants.
With that in mind, it is needed to design something that can give a lecture and create an output of information that could be available for a community and in that way activate the participation.
We intend to use this concept to design an interaction between sensors that can be connected to the soil or the compost in order to connect to the people in the community and have a social action and integration in the task that benefits all.

## Process

1. Humidity sensor sharing data
2. Soil Mixer connected to wifi/moving with heat generated energy

![](/images/S__6307842.jpg)
![](/fimages/protocol.jpeg)
![](/images/ref.jpeg)

# Humidity sensor

This time we tried to use the humidity sensor connected to wifi, in order to make your phone showing the percentage of humidity whenever you connect to the page.  It detects the humidity at every certain time that you control by arduino.
First, we have this water pump kit that we wanted to use in order to automatically control the humidity of plants/compost.

![](/images/kit.jpeg)

In theory, if we have this on, we will not let the plants die. We killed some plants when we left them over the holidays.

![](/images/S__6438935.jpg)

We first planned to have this dream image.
Somehow we wanted to pursue the way that we share collected  data community wise since we are engaged in this community garden in Poblenou.
Emilio tried hard to control this humidity sensor using an arduino IDE for the CPU we had of ESP32.
So many problems happened through this process because the sensor gives the random numbers which indicate the voltage that sensor senses. So it was hard to convert them into the number of percentages.

![](/images/S__6438937.jpg)
![](/images/S__6438947.jpg)

Also, the percentage was somehow backward of the actual number. So it was also hard to fix it how it is supposed to be.
In the end, it is connected to the rechargeable battery to be on its own so it doesn't have to be connected to a computer. With a 3d printed case for both battery and the CPU, it can be embedded in the soil of plants/compost.
While printing, Emilio worked on the Html to visualize the percentage in a nicer way to show information.

![](/images/html.jpeg)
![](/images/pcb.jpeg)
![](/images/test2.jpeg)
![](/images/test5.jpeg)
![](/images/plants.jpeg)

!! It is still in the process. Now printing.

![](/images/case.jpeg)
