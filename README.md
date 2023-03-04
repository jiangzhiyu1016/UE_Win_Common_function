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

* Get the current running directory    Call_Api(,,,,1)
* Gets the execution file name         Call_Api(,,,,2)
* Read environment variables           Call_Api("environment variables name",,,,3)

![image](https://user-images.githubusercontent.com/56686900/222879197-0df6e22e-8e1a-4da9-b2f4-d807b47ecdb3.png)

* Write environment variables           Call_Api("environment variables name","environment variables value",,,3)
* Gets the specified directory          Call_Api(,,int1,,4)
> int1=1    my documents dir
> 
> int1=2    my favorite dir
> 
> int1=3    my System desktop dir
> 
> int1=4    my system font dir
> 
> int1=5    my Start Menu group dir
> 
> int1=6    my Program menu group dir
> 
> int1=7    my Start menu Group dir
> 
> int1=8    my Program data directory dir
> 
> int1=9    my Windows installation directory
> 
> int1=10   my Windows system directory
> 
> int1=11   my Temporary file directory 



