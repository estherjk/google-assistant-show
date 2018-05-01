# google-assistant-show

Using the Android Things Kit to create "Google Assistant Show," a touch screen interface for Google Assistant.

## Hardware setup

This project uses the following components:

* [NXP i.MX7D Starter Kit](https://androidthings.withgoogle.com/#!/kits/pico-pro-maker-kit)
* [Mini USB Microphone](https://www.adafruit.com/product/3367)
* Speaker with 3.5 mm audio jack
    * *Note: The NXP i.MX7D Starter Kit does not have USB audio support. See this [page](https://developer.android.com/things/hardware/) for more info.*

## Creating credentials

See this [section](https://github.com/androidthings/sample-googleassistant#run-the-sample) on how to create the credentials for the Google Assistant API using a Python environment.

## Project structure

This project uses several files (`.java`) and a module (`grpc`) from the [androidthings/sample-googleassistant](https://github.com/androidthings/sample-googleassistant) repository:

```
.  
+-- app  
│   +-- ...  
│   +-- src/main/java/com/drejkim/androidthings/googleassistantshow  
│       +-- BoardDefaults.java  
│       +-- Credentials.java  
│       +-- EmbeddedAssistant.java  
│       +-- ...  
|   +-- ...    
+-- grpc
+-- ...  
```

These files make it easier to interface with the board and the Google Assistant API.

## Running the project

* Open Android Studio and choose **Import project** from the welcome screen.
* Navigate to this project's directory.
* Click Open. The project will take a few moments to import and build.
* Select **Run → Run 'app'** from the menu, or click the **Run** icon in the toolbar. 

## References

* [androidthings/sample-googleassistant](https://github.com/androidthings/sample-googleassistant)
* [Android Things Assistant](https://codelabs.developers.google.com/codelabs/androidthings-assistant/index.html?index=..%2F..%2Findex#0)
* [Android Things: Adding Google Assistant](https://code.tutsplus.com/tutorials/android-things-adding-google-assistant--cms-27690)