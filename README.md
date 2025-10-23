# Phone Check
POC Tool to detect if app is ran on an emulator

# Features
- [x] Detect Android Studio Emulator
- [x] List Detections

# How To Use

```Java
// Import the package
import com.reveny.emulatordetector.plugin.EmulatorDetection;

// Create a new EmulatorDetection object.
EmulatorDetection detection = new EmulatorDetection();

// Check whether is emulator or not
boolean status = detection.isDetected();    // True if running in emulator else false

// Get the detected result
String result = detection.getResult();   // Empty if status is false else gives all the detections
```


### To-Do List
- [ ] **Enhanced Emulator Detection**: Add more robust detection methods for various emulator environments, including less commonly used emulators.
- [ ] **Performance Optimizations**: Optimize the detection algorithms to minimize resource usage on the app.

If you’d like to contribute, please ensure that your code follows the project’s style.
