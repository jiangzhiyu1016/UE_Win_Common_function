# UE_Windows_function

Invoke the functions specified by the function with the specified parameters. Refer to the plug-in documentation for the corresponding functions in Windows


# Reply to Question

> If you have any new feature requirements for windows Call, please leave me a message and I will join as soon as possible

# How To Use
1. Make sure that **Windows_function Plugin** is enabled in your plugin(Open the Plugin in Unreal Engine and select Windows_function Plugin)

2. Example of call

![image](https://user-images.githubusercontent.com/56686900/222879197-0df6e22e-8e1a-4da9-b2f4-d807b47ecdb3.png)


如图

# function declaration
## Call_Api(FString arg1_str1, FString arg1_str2,int arg_int1,int arg_int2,int arg_int3);


| Windows Action | Call args(str1,str2,int1,int2,int3) | detail |
| --- | --- | --- |
| Get the current running directory  | Call_Api(,,,,1) | Gets the running directory of the current software |
| Gets the execution file name  | Call_Api(,,,,2) | 
 |
| Read environment variables |  Call_Api("environment variables name",,,,3) | 
 |
| 
4. Write environment variables
 |  Call_Api("environment variables name","environment variables value",,,4) | 
 |
|  5.  Gets the specified directory | Call_Api(,,int1,,5) | int1=1 my documents dir
int1=2 my favorite dir
int1=3 my System desktop dir
int1=4 my system font dir
int1=5 my Start Menu group dir
int1=6 my Program menu group dir
int1=7 my Start menu Group dir
int1=8 my Program data directory dir
int1=9 my Windows installation directory
int1=10 my Windows system directory
int1=11 my Temporary file directory |
| 
6. Gets the number of CPU cores
 |  Call_Api(,,,,6) |  |
| 
7. Whether to display the mouse pointer
 |  true Call_Api(,,1,,7) 
False Call_Api(,,0,,7) |  |
| 
8. Gets the horizontal and vertical position of the mouse on the display(Return X&#124;Y) 
 | Call_Api(,,0,,8) |  |
| 
9. get the system interface scale dpi
 |  Call_Api(,,0,,9) |  |
| 
10. Lock or unlock keyboard and mouse input events for the current program
 |  true Call_Api(,,1,,10) 
False Call_Api(,,0,,10) |  |
| 
11. Returns the total amount of time in milliseconds since the computer system started.
 |  Call_Api(,,,,11) 
 |  |
| 
