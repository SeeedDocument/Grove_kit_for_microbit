---
title: Grove_Inventor_Kit_for_micro:bit
category: others
bzurl:  https://www.seeedstudio.com/Grove-Inventor-Kit-for-micro%3Abit-p-2891.html
oldwikiname: Grove_Inventor_Kit_for_micro:bit
prodimagename: https://statics3.seeedstudio.com/seeed/file/2017-06/bazaar492598_8.jpg
surveyurl: https://www.research.net/r/Grove_Inventor_Kit_for_microbit
sku:    110060762
---
![](https://github.com/SeeedDocument/Grove_kit_for_microbit/raw/master/img/zoro_im_kitbox.jpg)

The BBC micro:bit is a pocket-sized computer that can easily realize your creativity without much electrical and coding knowledge. There are numerous possibility of creation you can dig out by micro:bit, from robots to musical instruments. However if you want to create more things, just 1 micro:bit is barely not enough, That’s why we introduce the Grove Inventor Kit for micro:bit to you.

The Grove Inventor Kit for Micro:bit brings endless possibilities to your micro:bit. The core board in this kit is the Grove shield for micro:bit, with which you can use plenty of Grove modules including sensors, display, actuator to interact with micro:bit. If you never used and have no idea what grove is, here is the introduction of Grove. All you need to know is that with Grove, there is no need of soldering or jump wires any more. Your prototyping will be easier and much more convenient.

We have already prepared 8 grove modules to let you get started with micro:bit. With these grove modules, you can measure distance and display it, use gesture to play different music, or make a smart guard for your desk or room. We have prepared all the necessary libraries(packages) for free download. If you are a beginner to micro:bit, don’t worry because we have also prepare 12 different project which can teach you step by step. If you are an advanced user, this kit will help you more creative project than others.




[![](https://github.com/SeeedDocument/Seeed-WiKi/raw/master/docs/images/300px-Get_One_Now_Banner-ragular.png)](https://www.seeedstudio.com/Grove-Inventor-Kit-for-micro%3Abit-p-2891.html)

##  Features

    * Cool extension shield with rich and convenient peripherals;
    * 10 well selected Grove modules for working with micro:bit;
    * 12 awesome projects to let you get started quickly;
    * Well documented instruction.

##  Hardware Overview


![](https://github.com/SeeedDocument/Grove_kit_for_microbit/raw/master/img/first_im.jpg)

###  **Parts list**
| Part name | Quantity |
|--------------------------|-----|
|Grove Shield for micro:bit|  1  |
|Grove - Rotary Angle Sensor(P)| 1 |
|Grove - Speaker | 1 |
|Grove - Ultrasonic Ranger| 1 |
|Grove - Light Sensor v1.2| 1 |
|Grove - WS2812 Waterproof LED Strip - 30 LEDs 1 meter| 1 |
|Grove - Gesture | 1 |
|Grove - 4-Digit Display| 1 |
|Grove - Red LED| 1 |
|Micro USB Cable - 48cm| 1 |
|12 Projects Manual| 1 |
|Alligator Cable| 10 |
|Grove Cable| 7 |


##  Getting Started

###  Fundamentals with  Micro:bit

You need to know some essential knowledge if it is the first time that you get involved with Micro:bit. You can click [ **here** ](https://microbit.org/code/) to see more about Micro:bit.

Micro:bit offers two type of editor - JavaScript Block Editor and Python Editor. JavaScript Block Editor support graphical programming, it's easy to learn. So this Tutorial is based on JavaScript Block Editor.

Here are two simple steps before you enjoy our kit, after that we can start program.

####  Step1.Open the Editor

Please click to open the **[JavaScript Block Editor](https://makecode.microbit.org/)** , and you will see a graphical programming web.


####  Step2.Add Grove Package
  - Click the gear in the top right corner > select **Add Package**

  ![](https://github.com/SeeedDocument/Grove_kit_for_microbit/raw/master/img/0-1.png)

  - Enter project URL: **github.com/seeed-studio/pxt-grove**

  ![](https://github.com/SeeedDocument/Grove_kit_for_microbit/raw/master/img/0-2.png)

  - Now you can find **Grove**  in the toolbar.

  ![](https://github.com/SeeedDocument/Grove_kit_for_microbit/raw/master/img/0-3.png)

### Demo 1. Gesture Recognition

The gesture sensor can recognize 9 different gestures, in this demo, you will learn how to display the recognized
gesture name on micro:bit.


#### Part list

|Part name|number|
|---|---|
|Grove - Gesture|1|
|Grove Shield for micro:bit|1|
|micro:bit|1|

#### Connection

  - Plug the micro:bit into Grove Shield for micro:bit.

!!!warning please make sure the LED Array is faced up when you plug the micro:bit, or you may damage the board.

  - Connect the Grove-Gesture to I2C Port of micro:bit via a Grove Universal 4 pin cable.
  - Connect micro:bit to PC via a Micro-USB cable.


![](https://github.com/SeeedDocument/Grove_kit_for_microbit/raw/master/img/Gesture%20Recognition.png)


#### Software
  - Step1: Add On Gesture Block

  ![](https://github.com/SeeedDocument/Grove_kit_for_microbit/raw/master/img/1-1.png)

  - Step2: Select Right, so that the sensor can recognize when you move your hand from right to the left.

  ![](https://github.com/SeeedDocument/Grove_kit_for_microbit/raw/master/img/1-2.png)

  - Step3: Add Basic block **show string** and embed it into the Gesture block.Then double click "Hello!", change it to "Right".

  ![](https://github.com/SeeedDocument/Grove_kit_for_microbit/raw/master/img/1-3.png)

  - Step4: Add "Left" and "Clockwise" the same way, and embed **show icon** into "Clockwise".

  ![](https://github.com/SeeedDocument/Grove_kit_for_microbit/raw/master/img/1-4.png)

  - Step5: Add


  ![](https://github.com/SeeedDocument/Grove_kit_for_microbit/raw/master/img/Gesture%20Recognition.png)
