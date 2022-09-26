# bijay123
At first make sure that your terminal is in Ros2 Distro.
after that lets source our file start installing turtlesim.


```
sudo update
sudo apt install ros-foxy-turtlesim
```
![1](https://user-images.githubusercontent.com/58104378/192177264-3656d303-1f32-4ddd-9e3a-00a8fc7775ef.png)

now lets check the list of installed packages:
```
ros2 pkg executables turtlesim
```
![2](https://user-images.githubusercontent.com/58104378/192178383-71e18c5a-b971-418c-a6e1-05c5666d5e11.png)

**2**
**Starting Turtlesim**:
```
ros2 run turtlesim turtlesim_node
```
![3](https://user-images.githubusercontent.com/58104378/192178662-1b7d02d8-1c78-4f27-91fa-16eed6d57dbf.png)

A message from the node will pop up in the terminal.

![4](https://user-images.githubusercontent.com/58104378/192178879-2aca2290-08f6-4906-86c0-d9bd96ea2de2.png)

**3**
Open new terminal
after making sure your terminal is Ros2 Distro, run a new node to control your turtle in 1st node.
```
ros2 run turtlesim turtle_teleop_key
```
![5](https://user-images.githubusercontent.com/58104378/192179203-f579115b-e9d9-4d55-9a20-3d9d4ab4a8ea.png)
you can use keys to control your turtle.

**4. Installing RQT**
open new terminal and install RQT
```
sudo apt update
sudo apt install ~nros-foxy-rqt*
```
use
```
rqt
```
to run rqt

**After that**- Select: Plugins>Services>Service Caller
![7](https://user-images.githubusercontent.com/58104378/192179631-fb8fdd88-24cb-46ee-b036-7970f25c25c4.png)

**^-Scenarios** lets try spawn service
under the service field lets try spawn
it will create another turtle in the turtlesim window.
![Screenshot 2022-09-26 102358](https://user-images.githubusercontent.com/58104378/192180017-121f9e89-057f-4f58-ac52-f17ec3b9c296.png)

![Screenshot 2022-09-26 102421](https://user-images.githubusercontent.com/58104378/192180060-d926ba85-9b19-4f7d-8036-ba86c93a35e8.png)

**Lets try absolute service**
![Screenshot 2022-09-26 102528](https://user-images.githubusercontent.com/58104378/192180191-0e5bdd80-e315-4478-a69b-46a3e0b9fda1.png)

![Screenshot 2022-09-26 102552](https://user-images.githubusercontent.com/58104378/192180222-2badd3b8-c0cd-414e-99e8-b4f4bf0cba5a.png)

**Stop Simulation**
you can enter Ctrl+c to stop simulation.
