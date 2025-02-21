# 5. Action Editing

## 1. PC Software Introduction

The functions of PC software are introduced in details for you to master it quickly.

Firstly, connect to VNC remote desktop and double-click PC software "**SpiderPi**" to start it. If window pops up, click "**Run**".

<img class="common_img" src="../_static/media/chapter_7/section_1/image2.png"  />

<img src="../_static/media/chapter_7/section_1/image4.png"  alt="loading" />

The interface is divided into 5 areas.

<img src="../_static/media/chapter_7/section_1/image5.png"  alt="loading" />

### 1.1 Body control area

You can drag the slider to control the position of the corresponding servo so as to switch the moving posture of the SpiderPi Pro.

|                             Icon                             |                 Function                 |
| :----------------------------------------------------------: | :--------------------------------------: |
| <img src="../_static/media/chapter_7/section_1/image6.png"  alt="loading" /> |  ID number. Take NO.3 servo as example   |
| <img src="../_static/media/chapter_7/section_1/image7.png"  alt="loading" /> |   Adjust servo position from 0 to 1000   |
| <img src="../_static/media/chapter_7/section_1/image8.png"  alt="loading" /> | Adjust servo deviation from -125 to 125. |

### 1.2 Robotic arm control area

You can adjust the servo value in this area to control the posture of the robotic arm. Note: the ID of the servo on the robotic arm from the top to the bottom is 25 - 21.

|                             Icon                             |                 Function                 |
| :----------------------------------------------------------: | :--------------------------------------: |
| <img src="../_static/media/chapter_7/section_1/image9.png"  alt="loading" /> |  ID number.Take NO.25 servo as example   |
| <img src="../_static/media/chapter_7/section_1/image7.png"  alt="loading" /> |  Adjust servo position from 0 to 1000.   |
| <img src="../_static/media/chapter_7/section_1/image8.png"  alt="loading" /> | Adjust servo deviation from -125 to 125. |

### 1.3 Action list

The running time and servo data of the current action are displayed on the action list.

<img class="common_img" src="../_static/media/chapter_7/section_1/image10.png"  alt="loading" />

|                             Icon                             |                           Function                           |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| <img src="../_static/media/chapter_7/section_1/image11.png"  alt="loading" /> | The serial number of the action group. Here refer to NO.1 action. |
| <img src="../_static/media/chapter_7/section_1/image12.png"  alt="loading" /> |                 Running time of the action.                  |
| <img src="../_static/media/chapter_7/section_1/image13.png"  alt="loading" /> | Action data of the corresponding servo. Double click the figure to revise. |

### 1.4 Action group setting

|                             Icon                             |                           Function                           |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| <img src="../_static/media/chapter_7/section_1/image15.png"  alt="loading" /> | Action running duration time. Click the value to modify. Note: you need to click the "Update Action" button to make the modified settings take effect. In addition, the value range of the time is 20-9999. |
| <img src="../_static/media/chapter_7/section_1/image16.png"  alt="loading" /> | The total running time taking for all the actions in an action group to complete running. |
| <img src="../_static/media/chapter_7/section_1/image17.png"  alt="loading" /> | If you click this button, the joints of the robot will become loose, and you can drag the servo to form any posture. |
| <img src="../_static/media/chapter_7/section_1/image18.png"  alt="loading" /> | Read the servo angle you have designed before. This button should be used with<img src="../_static/media/chapter_7/section_1/image17.png"  alt="loading" /> |
| <img src="../_static/media/chapter_7/section_1/image19.png"  alt="loading" /> | Add the servo value as a action to the last line of the action list |
| <img src="../_static/media/chapter_7/section_1/image20.png"  alt="loading" /> |        Delete the action selected in the action list         |
| <img src="../_static/media/chapter_7/section_1/image21.png"  alt="loading" /> | Replace the angle value of the action selected in the action list with the servo value in the servo control area. And update the running time as the time set in "**Time**" |
| <img src="../_static/media/chapter_7/section_1/image22.png"  alt="loading" /> | Insert a new action above the selected action. The running time of this new action is the time set in "**Time**" and angle value is the current value in servo control area. |
| <img src="../_static/media/chapter_7/section_1/image23.png"  alt="loading" /> |             Move the selected action up one line             |
| <img src="../_static/media/chapter_7/section_1/image24.png"  alt="loading" /> |            Move the selected action down one line            |
| <img src="../_static/media/chapter_7/section_1/image25.png"  alt="loading" /> |     Click to run all the actions on the action list once     |
| <img src="../_static/media/chapter_7/section_1/image26.png"  alt="loading" /> | If "**Loop**" is ticked, SpiderPi Pro will repeat the action. |
| <img src="../_static/media/chapter_7/section_1/image27.png"  alt="loading" /> |  Load the data of the saved action group to the action list  |
| <img src="../_static/media/chapter_7/section_1/image28.png"  alt="loading" /> | Save the current actions in the action list into the designated path. |
| <img src="../_static/media/chapter_7/section_1/image29.png"  alt="loading" /> | Firstly, open one action group, then click this button, and then open other action group. And these two action groups will be integrated into one. |
| <img src="../_static/media/chapter_7/section_1/image30.png"  alt="loading" /> | Display the saved action groups. You can select the action to run |
| <img src="../_static/media/chapter_7/section_1/image31.png"  alt="loading" /> |       Delete the currently selected action group file.       |
| <img src="../_static/media/chapter_7/section_1/image32.png"  alt="loading" /> |     (**Be careful!**)Deleted all the action group files.     |
| <img src="../_static/media/chapter_7/section_1/image33.png"  alt="loading" /> |             Run the selected action group once.              |
| <img src="../_static/media/chapter_7/section_1/image34.png"  alt="loading" /> |                Stop running the action group.                |

### 1.5 Servo deviation setting area

|                             Icon                             |                          Function                           |
| :----------------------------------------------------------: | :---------------------------------------------------------: |
| <img src="../_static/media/chapter_7/section_1/image35.png"  alt="loading" /> |          Click to read the saved servo deviation.           |
| <img src="../_static/media/chapter_7/section_1/image36.png"  alt="loading" /> |   Click to download the adjusted deviation to the robot.    |
| <img src="../_static/media/chapter_7/section_1/image37.png"  alt="loading" /> | Click to return all the servos to the middle position(500). |

<p id="anchor_2"></p>

## 2. Action Editing

### 2.1 Project outcome

Create an action group consisting of 26 independent actions to allow the SpiderPi Pro to "move forward and pick".

### 2.2 Action design

This action group is divided into two parts. The first part is to make SpiderPi Pro to move forward, and the second part is to pick the block.

**2.2.1 Move forward**

The robot body consists of 6 legs, that is 1-6 zones, as shown in the figure below.

<img src="../_static/media/chapter_7/section_2/image1.png"  alt="loading" />

(1) Firstly, before starting the robot, set a initial posture for the robot. Click "**Open Action File**" and select the built-in action file "**stand_low.d6a**", and then click "**Open**". Then the first action is added to the action list.

<img class="common_img" src="../_static/media/chapter_7/section_2/image2.png"  />

<img class="common_img" src="../_static/media/chapter_7/section_2/image2.0.png"  />

(2) click <img src="../_static/media/chapter_7/section_2/image3.png" style="width:0.44792in;height:0.20139in" /> and update the action value to the servo control area.

<img src="../_static/media/chapter_7/section_2/image4.png"  alt="loading" />

(3) Adjust the slider of ID1, ID2, ID7, ID8, ID13 and ID14 servos to make robot lift NO.1, 3 and 5 legs and tilt forward. The adjusted values are shown as follow.

<img src="../_static/media/chapter_7/section_2/image5.png"  alt="loading" />

(4) Set the time as 300ms and click "**Add Action**". Then the second action is added to the action list.

<img class="common_img" src="../_static/media/chapter_7/section_2/image6.png"  alt="loading" />

(5) To make the transition between each action more fluent, it is necessary add transitional action between actions. Remain the servo value unchanged and modify the running time as 1000ms, and click "**Add Action**".

<img class="common_img" src="../_static/media/chapter_7/section_2/image7.png"  alt="loading" />

(6) Next, put down NO. 1, 3 and 5 legs. Modify the servo value of ID2, ID8 and ID14 according to the picture below.

<img src="../_static/media/chapter_7/section_2/image8.png"  alt="loading" />

Set the time as 300ms, and click "**Add Action**" to add NO.4 action.

<img class="common_img" src="../_static/media/chapter_7/section_2/image9.png"  alt="loading" />

<img class="common_img" src="../_static/media/chapter_7/section_2/image10.png"  alt="loading" />

(7) Add other transitional action and set the time as 200ms, and then click "**Add Action**" to form NO.5 action.

<img class="common_img" src="../_static/media/chapter_7/section_2/image11.png"  alt="loading" />

(8) Next, lift NO.2, 4 and 6 legs and make the servos on NO.1, 3 and 5 return to the mid position to make the robot move forward. Set he servo value according to the below figure

<img src="../_static/media/chapter_7/section_2/image12.png"  alt="loading" />

(9) Set the time as 400ms and click **"Add Action**" to obtain NO.6 action.

<img class="common_img" src="../_static/media/chapter_7/section_2/image13.png"  alt="loading" />

(10) Add a transitional action and set the time as 100ms and then click "Add Action". Then, NO.7 action is created.

<img class="common_img" src="../_static/media/chapter_7/section_2/image14.png"  alt="loading" />

(11) Lastly, put down NO 2, 4 and 6 legs. Please follow the picture below to set the value of ID5, 11 and 17 servos.

<img src="../_static/media/chapter_7/section_2/image15.png"  alt="loading" />

(12) Set the time as 600ms and click "**Add Action**" to add NO.8 action.

<img class="common_img" src="../_static/media/chapter_7/section_2/image16.png"  alt="loading" />

The action of moving forward is complete, which involves 8 independent actions. The servo values of each action are listed below.

<img src="../_static/media/chapter_7/section_2/image17.png"  />

**2.2.2 Pick the object**

After editing the action of "**moving forward**", design an action to make the robotic arm pick the block and place it to its right side. In the following steps, the values in robotic arm control area will be adjusted.

<img src="../_static/media/chapter_7/section_2/image18.png" class="common_img"  alt="loading" />

:::{Note}
robotic arm will move forward first and then pick the object, hence the action of picking object starts from NO.9 action.
You can take steps to set the servo value.
:::

(1) First, set the value of ID22 servo as 480 to make the robotic arm down.

<img src="../_static/media/chapter_7/section_2/image19.png" class="common_img"  alt="loading" />

(2) Then set the time as 600ms and click "**Add Action**" to create NO.9 action.

<img class="common_img" src="../_static/media/chapter_7/section_2/image20.png"  alt="loading" />

(3) As before, we need to add a transitional action. Set the time as 200ms and click **"Add Action**".

<img class="common_img" src="../_static/media/chapter_7/section_2/image21.png"  alt="loading" />

(4) Next, adjust the servo value of ID22 and ID23 to make the gripper approach the block.

<img class="common_img" src="../_static/media/chapter_7/section_2/image22.png"  alt="loading" />

(5) Set the time as 500ms and click "**Add Action**" to get NO.11 action.

<img class="common_img" src="../_static/media/chapter_7/section_2/image23.png"  alt="loading" />

(6) Set a transitional action and set the time as 200ms to build NO.12 action.

<img class="common_img" src="../_static/media/chapter_7/section_2/image24.png"  />

(7) When coming to the block, the robotic arm will start picking the block. Set the value of ID25 as 290 to make the gripper open.

<img class="common_img" src="../_static/media/chapter_7/section_2/image25.jpeg"  alt="loading" />

(8) Set the time as 600ms and click "**Add Action**" to form NO.13 action.

<img class="common_img" src="../_static/media/chapter_7/section_2/image26.png"  alt="loading" />

(9) Add a transitional action and set the time as 100ms to get NO.14 action.

<img class="common_img" src="../_static/media/chapter_7/section_2/image27.png"  alt="loading" />

(10) Adjust the servo value of ID22 to make the gripper approach the block.

<img class="common_img" src="../_static/media/chapter_7/section_2/image28.jpeg"  alt="loading" />

(11) Set the time as 400ms and click "**Add Action**" to design NO.15 action.

<img class="common_img" src="../_static/media/chapter_7/section_2/image29.png"  alt="loading" />

(12) Drag the slider of ID 25 to set the value as 510 making the gripper clamp the block.

<img class="common_img" src="../_static/media/chapter_7/section_2/image30.png"  alt="loading" />

Set the time as 200ms and click "**Add Action**" to get NO.16 action.

<img class="common_img" src="../_static/media/chapter_7/section_2/image31.png"  alt="loading" />

(13) Set the time as 100ms and click "Add Action" to add a transitional action.

<img class="common_img" src="../_static/media/chapter_7/section_2/image32.png"  alt="loading" />

(14) Set the value of ID22 as 510 to make the robotic arm lift the block.

<img class="common_img" src="../_static/media/chapter_7/section_2/image33.png"  alt="loading" />

(15) Set the time as 700ms and click "**Add Action**" to obtain NO.18 action.

<img class="common_img" src="../_static/media/chapter_7/section_2/image34.png"  alt="loading" />

(16) Set the time as 300ms and click "**Add Action**" to add a transitional action.

<img class="common_img" src="../_static/media/chapter_7/section_2/image35.png"  alt="loading" />

(17) After the block is picked, control the robotic arm to transfer the block to the right side. Adjust the slider of ID21 to set the value as 200.

<img class="common_img" src="../_static/media/chapter_7/section_2/image36.png"  alt="loading" />

(18) Set the time as 1000ms and click "Add Action" to receive NO.20 action.

<img class="common_img" src="../_static/media/chapter_7/section_2/image37.png"  alt="loading" />

(19) Set the time as 600ms and click "Add Action" to create a transitional action.

<img class="common_img" src="../_static/media/chapter_7/section_2/image38.png"  alt="loading" />

(20) Next, put down the block and drag the slider of ID22 to lower down the robotic arm.

<img class="common_img" src="../_static/media/chapter_7/section_2/image39.png"  alt="loading" />

(21) Set the time as 1000ms and click "**Add Action"** to generate NO.22 action.

<img class="common_img" src="../_static/media/chapter_7/section_2/image40.png"  alt="loading" />

(22) Release the block. Set the value of ID25 servo as 200 to open the gripper.

<img class="common_img" src="../_static/media/chapter_7/section_2/image41.jpeg"  alt="loading" />

(23) Set the time as 800ms and click "**Add Action**" to add NO.23 action.

<img class="common_img" src="../_static/media/chapter_7/section_2/image42.png"  alt="loading" />

(24) Having released the block, the robotic arm should be lifted. Set the value of ID22 servo as 550.

<img class="common_img" src="../_static/media/chapter_7/section_2/image43.jpeg"  alt="loading" />

(25) Set the time as 1000ms and click "**Add Action**" to get NO.24 action.

<img class="common_img" src="../_static/media/chapter_7/section_2/image44.png"  alt="loading" />

(26) Set the time as 1000ms and click "**Add Action**" to add a transitional action.

<img class="common_img" src="../_static/media/chapter_7/section_2/image45.png"  alt="loading" />

(27) Lastly, make the robotic arm return to the initial posture. Move to the action list and select NO.8 action, and then click<img src="../_static/media/chapter_7/section_2/image3.png" style="width:0.31496in;height:0.14161in" />to update the value of this action to the servo controlling area.

<img class="common_img" src="../_static/media/chapter_7/section_2/image46.png"  alt="loading" />

(28) Set the time as 1000ms and click "**Add Action**" to get NO.26 action.

<img class="common_img" src="../_static/media/chapter_7/section_2/image47.png"  alt="loading" />

<img class="common_img" src="../_static/media/chapter_7/section_2/image48.png" style="width:7.37569in;height:2.83819in" />

The servo value of the whole action group is as follow.

### 2.3 Save the Action

For the convenience of later debugging and management, it is recommended to save the action. Click "**Save Action File**" and select the path to save, `/home/pi/SpiderPi/ActionGroups`, and the enter the action group name "**go_forward_and_grip**". Lastly, click "**Save**".

:::{Note}
when entering the action group name, please do not press "**Space**", otherwise it may fail to save the action group.
:::

<img class="common_img" src="../_static/media/chapter_7/section_2/image49.png"  />

<img class="common_img" src="../_static/media/chapter_7/section_2/image50.png"  />

## 3. Action Calling

SpiderPi Pro has 15 built-in action groups which are stored in the path `/home/pi/spiderpi/action_groups/`. With PC software, you can check and call the built-in actions. You can follow the below steps to operate.

### 3.1 Operation steps

(1) According to the tutorial in "[Set Development Environment\1.VNC Installation and Connection]()", install VNC and remotely connect to Raspberry Pi system desktop.

(2) Double click<img src="../_static/media/chapter_7/section_3/image1.png" style="width:0.39306in;height:0.40347in" alt="loading" />and click "**Run**" in the pop-up window to enter the editing interface, as shown in the below figure.

<img class="common_img" src="../_static/media/chapter_7/section_3/image2.png"  alt="loading" />

(3) Next, click "**Open Action File**" to select the action group to run. Then click "**Open**".

<img class="common_img" src="../_static/media/chapter_7/section_3/image3.png"  />

<img class="common_img" src="../_static/media/chapter_7/section_3/image3.0.png"  />

(4) The file path and servo value of each action in this action group will be displayed in the action list.

<img class="common_img" src="../_static/media/chapter_7/section_3/image4.png"  />

(5) Click "**Run**" to run all the actions in the action list. If you want to make the robot repeat the action group, you can tick "**Loop**".

<img class="common_img" src="../_static/media/chapter_7/section_3/image5.png"  alt="loading" />

### 3.2 Import the external action group

If you want to call the external actions, you can follow these steps to operate. Take importing "**dance.d6a**" action group for example. Note: the action group file must end with "**.d6a**" suffix.

(1) Insert the U disk containing the action files into any USB interface on Raspberry Pi. And copy and paste the action group files to the system desktop.

<img class="common_img" src="../_static/media/chapter_7/section_3/image6.png"  />

(2) Then save the action group file to this path `/home/pi/spiderpi/action_groups/`.

<img class="common_img" src="../_static/media/chapter_7/section_3/image7.png"  />

(3) Next, double click PC software icon<img src="../_static/media/chapter_7/section_3/image1.png" style="width:0.39306in;height:0.40347in" alt="loading" />and click "Run"

(4) Click "**Open Action File**" and select the action group file to import, and then click "**Open**".

<img class="common_img" src="../_static/media/chapter_7/section_3/image8.png"  />

<img class="common_img" src="../_static/media/chapter_7/section_3/image8.0.png"  />

(5) At this time, the servo value and the running time of the imported action group are displayed on the action list.

<img class="common_img" src="../_static/media/chapter_7/section_3/image9.png"  />

## 4. Integrate Action Files

### 4.1 Project outcome

Integrating action files is to integrate two actions to form a new action group. And, we will integrate "wave" and "**go_forward_and_grip**" for example.

### 4.2 Start integrating

(1) Having connected to VNC, open SpiderPi PC software.

(2) Click "**Open action file**"and select "**wave.d6a**"file in the pop-up window, and click **"Open**".

<img class="common_img" src="../_static/media/chapter_7/section_4/image1.png"  />

<img class="common_img" src="../_static/media/chapter_7/section_4/image2.png"  />

(3) Then the parameters of this action group are displayed on the action list.

<img class="common_img" src="../_static/media/chapter_7/section_4/image3.png"  alt="loading" />

(4) Click "**Integrate file**" and select **"go_forward_and_grip**" action group, and then click "**Open**" again to integrate these two action groups.

<img class="common_img" src="../_static/media/chapter_7/section_4/image4.png"  />

<img class="common_img" src="../_static/media/chapter_7/section_4/image4.0.png"  />

<img class="common_img" src="../_static/media/chapter_7/section_4/image5.png"  alt="loading" />

(5) Click "**Run**" to execute the new integrated actions online.

<img class="common_img" src="../_static/media/chapter_7/section_4/image6.png"  />

(6) Click "**Save action file**" button and enter new action group name (such as "**wave_and_grip**" ) to save the new integrated action group for the future debugging.

<img class="common_img" src="../_static/media/chapter_7/section_4/image7.png"  />

<img class="common_img" src="../_static/media/chapter_7/section_4/image8.png"  />

## 5. Call Action Group Using Command

### 5.1 Goal

Besides importing the action groups of SpiderPi Pro using PC software, user can execute the command on the terminal to run action group.

:::{Note}
action group files must be saved in this directory `/home/pi/spiderpi/action_groups/`.
:::

Click-on <img src="../_static/media/chapter_7/section_5/image1.png" style="width:0.31458in;height:0.275in" /> and navigate to this folder `/home/pi/spiderpi/action_groups/` where all action files are saved here.

<img class="common_img" src="../_static/media/chapter_7/section_5/image2.png"  />

### 5.2 Call Action Group

(1) After accessing the system desktop using VNC, click-on <img src="../_static/media/chapter_7/section_5/image3.png" style="width:0.32292in;height:0.30208in" /> to open the terminal.

(2) Execute the command and press Enter to navigate to the folder where game programs are saved.

```bash
cd spiderpi/functions/
```

(3) Run the command  and press Enter to start the game.

```bash
python3 action_group_control_demo.py
```

At this time, SpiderPi Pro will execute "**stand**" action group, then execute "**go_forward**" action group twice. Once SpiderPi Pro completes running the action group, the program will be terminated automatically.

### 5.3 Change Action Group to be Called

**5.3.1 Call Individual Action**

User can modify the program to enable SpiderPi Pro to execute single action group. Detailed instructions are as below:

(1) After entering the robot system using VNC, click-on <img src="../_static/media/chapter_7/section_5/image3.png"  /> to open the terminal.

(2) Execute the command and press Enter to switch the directory where game programs are saved.

```bash
cd spiderpi/functions
```

(3) Execute the command  and press Enter to open the program file.

```bash
sudo vim action_group_control_demo.py
```

(4) Press "I" key to enter program editing mode.

<img class="common_img" src="../_static/media/chapter_7/section_5/image8.png"  />

(5) Locate the following mode.

<img class="common_img" src="../_static/media/chapter_7/section_5/image9.png"  />

(6) Use the function `AGC.run_action_group()` to call action groups saved in "/home/pi/spiderpi/action_groups/". Enter the action group name within the single quotation mark, then save the command. After that, you can call the action group using command.

The 28th line of code introduces an extra runtime parameter 'time=2,' indicating that it will run twice. In this section, we'll illustrate using the 27th line as an example, and initially, you can comment out the 28th line of code.

To do this, you can navigate the mouse cursor using the keyboard's arrow keys and add the '#' symbol at the beginning of line 28 to comment out that line of code. This will retain only the code for executing the 'stand_low' action group. In this configuration, the remaining 29th line of code will execute the action group once. If you wish to run the action group multiple times, you can comment out the 29th line and keep the 30th line of code.

<img class="common_img" src="../_static/media/chapter_7/section_5/image10.png"  />

(7) Enter the action group to be executed within the single quotation mark of the 29th line of code. Take executing "attack" action group as example.

<img class="common_img" src="../_static/media/chapter_7/section_5/image11.png"  />

:::{Note}
the action group files must be saved in the directory `/home/pi/spiderpi/action_groups/`. If you want to call the customized action group, you need to edit the action group first according to the file saved in "[Action Editing\2.Action Editing]()".
:::

<img class="common_img" src="../_static/media/chapter_7/section_5/image12.png"  />

(8) After modification, press `Esc` to exit the editing mode. Then input `:wq` and press `Enter` to save and close the program file.

```bash
:wq
```

(9) Execute the command `python3 action_group_control_demo.py` and press `Enter` to start the game. SpiderPi Pro will execute the action group `attack` once.

```bash
python3 action_group_control_demo.py
```

<img class="common_img" src="../_static/media/chapter_7/section_5/image14.png"  />

**5.3.2 Call Multiple Action Groups**

:::{Note}

The following operation is carried out based on the preceding operation.

:::

User can enable SpiderPi Pro to execute several action groups through copying multiple lines of codes. Take calling action groups "**left_move**" and "**kick**" as example.

(1) Repeat steps 1-3 provided in "[5.3.1 Call Individual Action]()" to open the program file. Please note that never enter the editing mode, otherwise you will fail to copy the codes. If you find you are in editing mode, press `Esc` key to exit this mode.

(2) Position the cursor just before the 29th line using the arrow keys, and then press 'yy' on the keyboard. To copy 2 lines, use '2yy,' with '2' indicating the number of lines to be copied. You can specify the desired number of lines to copy; for instance, use '5yy' to copy 5 lines.

(3) Them move to the end of the 30th line and press `p` to paste the code.

<img class="common_img" src="../_static/media/chapter_7/section_5/image15.png"  />

<img class="common_img" src="../_static/media/chapter_7/section_5/image16.png"  />

(4) Press `i` key to enter the editing mode, and change the number of the 29th and 31st lines respectively to "left_move" and "kick".

<img class="common_img" src="../_static/media/chapter_7/section_5/image17.png"  />

:::{Note}
action group files are saved in the directory `/home/pi/spiderpi/action_groups/` The name of action group entered in the program should be consistent with the action groups saved in the "ActionGroups" folder.
:::

(5) After modification, press `Esc` key to exit the editing mode. Input `:wq` and press Enter to save and close the program file.

```bash
:wq
```

(6) Execute the command `python3 action_group_control_demo.py` to start the game. SpiderPi Pro will execute the action groups "**left_move**" and "**kick**" in sequence.

```bash
python3 action_group_control_demo.py
```

<img class="common_img" src="../_static/media/chapter_7/section_5/image14.png"  />
