---
hide:
    - toc
---

# Micro Challenge  III FabAcademy
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