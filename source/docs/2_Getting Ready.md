# 2. Quick User Experience

<p id="anchor_1"></p>

## [1. APP Installation and Connection ]()

<p id="anchor_2_1"></p>

## 2. APP Control

### 2.1 Getting ready

Follow the tutorial in [1. APP Installation and Connection]() under "[3. Color Threshold Adjustment]()" to install the app and connect to the SpiderPi Pro.

### 2.2 Start Games

After connecting, click SpiderPi Pro icon to enter the mode selection interface.

<img src="../_static/media/chapter_2/section_2/image1.jpeg"  alt="loading" />

In the mode selection interface, click the icon corresponding to the game to enter the game interface.

<img src="../_static/media/chapter_2/section_2/image2.png"  alt="loading" />

<img src="../_static/media/chapter_2/section_2/image3.jpeg"  alt="loading" />

**2.2.1 Robot Control**

This game allows you to control the movement and the action group execution of the robot in real time. The interface consists of four parts, and the descriptions and function icons of each part are shown below:

<img class="common_img" src="../_static/media/chapter_2/section_2/image4.jpeg"  alt="loading" />

The interface of `Robot Control` can be divided into three parts. The left side of the interface can control the movement of the SpiderPi Pro by dragging the slider. Other function icons can refer to the following table:


|                                                  Icon                                                  |                                                        **Corresponding Function**                                                        |
| :-----------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------: |
|  <img src="../_static/media/chapter_2/section_2/image5.png" style="width:1.1875in;height:1.18125in" />  |                                                Drag to control SpiderPi Pro's movement.                                                |
|   <img src="../_static/media/chapter_2/section_2/image6.png" style="width:1.16667in;height:0.5in" />   | Clicking on the icons from left to right can control the robot to perform left slide, stand at attention, and right slide, respectively. |
| <img src="../_static/media/chapter_2/section_2/image7.png" style="width:0.84514in;height:0.54444in" /> |                                           Make SpiderPi Pro perform provided built-in actions.                                           |
| <img src="../_static/media/chapter_2/section_2/image8.png" style="width:1.01111in;height:0.64444in" /> |                                         Provide a guide for the remote control of the SpiderPi.                                         |
| <img src="../_static/media/chapter_2/section_2/image9.png" style="width:0.92917in;height:1.88611in" /> |                                                     Make SpiderPi Pro perform provi                                                     |
| <img src="../_static/media/chapter_2/section_2/image10.png" style="width:2.00625in;height:0.96944in" /> |                                                    Adjust SpiderPi's movement speed.                                                    |

Click the icon <img src="../_static/media/chapter_2/section_2/image11.png" style="width:0.375in;height:0.37222in" /> at the top to bring up the interface for controlling the robotic arm. The movement of the robotic arm can be controlled by adjusting the angle of its 5 servos using the buttons.

<img class="common_img" style="width:50%" src="../_static/media/chapter_2/section_2/image12.jpeg"  alt="loading" />

If you want to back to the games option interface, you can click the blank area, then the title bar will appear. Next, click <img src="../_static/media/chapter_2/section_2/image13.png" style="width:0.27222in;height:0.21944in" /> at the left side.

**2.2.2 Color Recognition**

This game can recognize red, green, and blue. SpiderPi Pro will nod when it detects red and shake its head when it detects blue or green.

:::{Note}

* Please start this game under a well-lit environment, but try to keep it from direct light.

* When recognizing, please do not have the same or similar colored object within the detected range to avoid interference.

* If the recognition effect is not good enough, please refer to  "[3. Color Threshold Adjustment]()".
:::

(1) Click "Color Recognition" to enter this game. Its interface consists three parts:

<img class="common_img" src="../_static/media/chapter_2/section_2/image14.png"  alt="loading" />

① The status bar is located at the top of the interface.

②  The left side of the interface is the area for enabling, disabling the game and adjusting the color threshold.

③ The right side of the interface is the area for displaying the live camera feed.

(2) Click the "Start" allows you to place red, blue, and green objects one by one in front of the camera.

| Recognized Color |                              Outcome                              |
| :--------------: | :----------------------------------------------------------------: |
|       Red       |  The buzzer emits a "beep" sound, and the camera nods its head.  |
|      Green      | The buzzer emits a "beep" sound, and the camera shakes its head. |
|       Blue       | The buzzer emits a "beep" sound, and the camera shakes its head. |

(3) If want to back to mode selection interface, you can arbitrarily click the blank area in interface, then click <img src="../_static/media/chapter_2/section_2/image13.png" style="width:0.31496in;height:0.31496in" />.

**2.2.3 Target Tracking**

(1) Click "Target Tracking" to enter the game interface. Once activated, this game enables the pan-tilt of SpiderPi Pro to move along with the movement of the target color.

:::{Note}

Please start this game under a well-lit environment, but try to keep it from direct light.

When recognizing, please do not have the same or similar colored object within the detected range to avoid interference.

If the recognition effect is not good enough, please refer to "[3.Color Threshold Adjustment]()".

:::

<img class="common_img" src="../_static/media/chapter_2/section_2/image15.png"  alt="loading" />

① The status bar is located at the top of the interface.

② The tracking switch area is located on the left side of the interface

③ The live camera feed area is located on the right side of the interface.

(2) If want to back to mode selection interface, you can arbitrarily click the blank area in interface, then click <img src="../_static/media/chapter_2/section_2/image13.png" style="width:0.31496in;height:0.31496in" />.

**2.2.4 Line Following**

(1) Click "Line Following" to enter this game. After activating it, the SpiderPi Pro will move forward along a black, white or red line.

:::{Note}

* Please start this game under a well-lit environment, but try to keep it from direct light.

* When recognizing, please do not have the same or similar colored object within the detected range to avoid interference.

* If the recognition effect is not good enough, please refer to "[3. Color Threshold Adjustment]()".
  :::

<img src="../_static/media/chapter_2/section_2/image16.png"  alt="loading" />

① The status bar is located at the top of the interface.

②  The line tracking switch area is located on the left side of the interface

③ The camera live feed area is located on the right side of the interface.

(2) Click "Start following" to enter this game and select color. Then SpiderPi will follow the targeted line.

|                                               Icon Button                                               |         Function Instruction         |
| :-----------------------------------------------------------------------------------------------------: | :----------------------------------: |
| <img src="../_static/media/chapter_2/section_2/image17.png" style="width:1.1811in;height:0.24586in" /> |       Start or stop this game.       |
| <img src="../_static/media/chapter_2/section_2/image18.png" style="width:0.79514in;height:1.37569in" /> |      Select the targeted color.      |
| <img src="../_static/media/chapter_2/section_2/image19.png" style="width:0.94514in;height:0.76806in" /> | Display the selected tracking color. |

(3) If want to back to mode selection interface, you can arbitrarily click the blank area in interface, then click <img src="../_static/media/chapter_2/section_2/image13.png" style="width:0.31496in;height:0.31496in" />.

**2.2.5 Face Recognition**

:::{Note}
* Please start this game in a well-lit environment, but keep robot from the direct light.

* When recognizing, one human face only is allowed to appear within the detected range. Otherwise, it will affect the game result.

* The max recognition distance is about 1 meter.
:::

(1) Click Face Recognition to enter this game.

<img class="common_img" src="../_static/media/chapter_2/section_2/image20.png"  alt="loading" />

(2) After clicking  `Start`, the pan-tilt of the SpiderPi Pro will move left and right. When the face is detected, it will make a "Hello" action.

(3) If want to back to the mode selection interface, click the blank area of interface and then click <img src="../_static/media/chapter_2/section_2/image13.png" style="width:0.31496in;height:0.31496in" /> in the left side.

**2.2.6 Tag Recognition**

(1) Click "Tag Recognition" in mode selection interface to enter this game. This allows SpiderPi Pro's camera to recognize different QR code tags and execute corresponding actions.

:::{Note}
* When recognizing QR codes, the distance should not be too close or too far. The best distance between the QR code image and the camera is 35cm.

* Please start this game in a well-lit environment, but keep robot from the direct light.
:::

<img class="common_img" src="../_static/media/chapter_2/section_2/image21.jpeg"  alt="loading" />

(2) Click "Start". Then SpiderPi will identify tags within the detected range and carry out different actions according to the recognized ID.

| **ID** | Corresponding Action |
| :----: | :------------------: |
|   1   |   Wave "Hello".   |
|   2   |    Walk in place.    |
|   3   |   Twist the body.   |

(3) If want to back to the mode selection interface, click the blank area of interface and then click <img src="../_static/media/chapter_2/section_2/image13.png" style="width:0.31496in;height:0.31496in" /> in the left side.

**2.2.7 Obstacle Avoidance**

(1) Click Obstacle Avoidance to enter the game interface. After this game is activated, the SpiderPi Pro can use ultrasonic to detect obstacles ahead to avoid them.

:::{Note}
Do not detect object at close range for a long time.
:::

<img class="common_img" src="../_static/media/chapter_2/section_2/image22.png"  alt="loading" />

① The left side of the interface includes the obstacle avoidance game switch and the obstacle threshold setting area.

② The middle of the interface is the camera transmission image area.

③ The right side of the interface includes the setting area for the RGB light and motor speed.

(2) Click "Start avoidance". SpiderPi Pro will move forwards and it will turn left when detecting obstacle ahead. Then continue moving forward until there is no obstacle.

|                                               Button Icon                                               |           Function Instruction           |
| :-----------------------------------------------------------------------------------------------------: | :---------------------------------------: |
| <img src="../_static/media/chapter_2/section_2/image23.png" style="width:2.20972in;height:0.36806in" /> |         Start or close this game.         |
| <img src="../_static/media/chapter_2/section_2/image24.png" style="width:2.2125in;height:0.87847in" /> | Set obstacle threshold in the unit of mm. |
| <img src="../_static/media/chapter_2/section_2/image25.png" style="width:2.20903in;height:0.47639in" /> |         Turn on or off RGB light.         |
| <img src="../_static/media/chapter_2/section_2/image26.png" style="width:0.92639in;height:0.87014in" /> |          Adjust RGB light color.          |

(3) If want to back to mode selection interface, you can arbitrarily click the blank area in interface, then click <img src="../_static/media/chapter_2/section_2/image13.png" style="width:0.31496in;height:0.31496in" />.

<p id="anchor_3"></p>

## [3.Adjust Color Threshold]()
