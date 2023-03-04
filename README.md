# UE_Windows_function

Invoke the functions specified by the function with the specified parameters. Refer to the plug-in documentation for the corresponding functions in Windows


# Reply to Question

> If you have any new feature requirements for windows Call, please leave me a message and I will join as soon as possible

# How To Use
1. Make sure that **Windows_function Plugin** is enabled in your plugin(Open the Plugin in Unreal Engine and select Windows_function Plugin)

2. Example of call

如图

# function declaration
## Call_Api(FString arg1_str1, FString arg1_str2,int arg_int1,int arg_int2,int arg_int3);

* Get the current running directory    Call_Api(,,,,1)
* Gets the execution file name         Call_Api(,,,,2)
* Read environment variables           Call_Api("environment variables name",,,,3)
