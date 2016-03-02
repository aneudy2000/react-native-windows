# Running the Playground App for React Native For UWP

This guide contains instructions for building the UWP code for React Native

## Supported Operating Systems

This setup has only been tested on Windows 10 so far.  

## Prerequisites

Assuming you have [Visual Studio 2015 Enterprise](\\products\PUBLIC\Products\Developers) installed, you will also need to have Windows 10 SDK installed. 

Clone this repo onto your local machine.
```
git clone https://github.com/CatalystCode/react-native.git
git checkout ReactWindows
git pull origin ReactWindows
cd react-native/ReactWindows/Playground
```

Build your environment :

- Open up the ReactNative solution file in Visual Studio Enterprise. The solution file can be found in {CWD}/ReactWindows/ReactNative.sln.
- If this is your first time using UWP, you will have to install the SDK. Right click on the solution file in the solution explorer and select the option labeled "Install Missing Components". You'll likely have to shutdown visual studio to continue the installation.
- You can start building the solution once all the packges are installed Build->Rebuild Solution. 

Run the Playground App:

- Set the Playground Project as your starter project in Visual Studio.
- Set the target in VS to Bundle. 
