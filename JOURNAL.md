# Strawberry_Pi

## Day 1

I spent the entire day configuring the wiring up the strawberry pi board. Originally I wanted to use the stm32h757ZIYxx, but it was just way too complex due to the dual mcu architecture. I spent a whole lot of time on cubemx configuring that but it eventually went to waste. But I then went up with my trusty stm32h743vitx. Sure I had to remove some features like display but what it lost in functionality, it gained in it's convenience.

https://lapse.hackclub.com/timelapse/_1ylYZns9QVY
![Cubemx](Assets/image.png)

Then, I just read datasheets for the stm32 (On a separate device. So you won't see me changing windows very often.) and wired it up. Then the power components and finally the memory section.

https://lapse.hackclub.com/timelapse/YPAaonDyC28P
![Schematics](Assets/image-1.png)

Finally, I wired up the ethernet and the camera connectors. I was pretty confused at first regarding the etherned wiring as the references showed differential paris while cubemx had configured something else. But after a quick google search, I came to know that it was because of the RMII setting I had set up in cubemx. I just needed a small chip and a suitable ethernet connector.

https://lapse.hackclub.com/timelapse/z4tXTK4zzKuB
![Schematics](Assets/image-2.png)

## Day 2

Today was spent on finishing schematics!!!
I wired up the fan and breakout connectiors for SPI, I2C, UART, and 10 GPIO ports. I also wired the audio input connector and fixed any broken/error-prone connections. We had originally planned on a raspberry pi 4 form-factor board but due to the lack of USB-A ports, it's not feasible at the moment. So, I think we'll go with a raspberry pi zero form-factor but with ethernet capabilities like board.

https://lapse.hackclub.com/timelapse/AY0L5Gldac55
![Schematics](Assets/image-3.png)

## Day 3

THE BOARD IS COMPLETE!!! After 3 days of hard work, I finally finished the rpi-4 form factor Strawberry Pi. I have a total of 5 lapse times today. The first one is only 5 mins long bc my laptop decided to die in the middle of work. Here, I was p
lanning out the board.

https://lapse.hackclub.com/timelapse/ifrvSFvBeYo9

Then, I started work on finalizing sections and also editing any footprint/3d model errors. There were a lot of those for some reason but I fixed it. I planned out the component placements too. It was scary at first because of all the ratsnest lines going all over the board but little by little, I tidied it up to my abilities and it started to take shape.

https://lapse.hackclub.com/timelapse/IUfBVHrY7pCA
https://lapse.hackclub.com/timelapse/HjVgqjR3aEW2
![Placement](Assets/image-4.png)

Finally, I routed the components and added aesthetics to fill in the blank spaces and to make the board a little less empty. Lemme tell you, aesthetics add SOO much personality to a pcb project. Even the pcb routes make the board look pretty. I may not have the prettiest board, but some sections of this pcb are beautiful to me. Thus, I finished the board!

https://lapse.hackclub.com/timelapse/Y_POSmpzjU_k
https://lapse.hackclub.com/timelapse/AnoPyOCp-v4V
![Routing](Assets/image-5.png)
