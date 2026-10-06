# Hello World iOS App using SwiftUI

## Aim

Create your first **Hello World iOS application using SwiftUI**.

## Description

This practical demonstrates how to create a basic iOS application using **Xcode, Swift, and SwiftUI**. The application displays **"Hello, world!"** on the screen and can be executed using the iOS Simulator.

## Technologies Used

* **Language:** Swift
* **UI Framework:** SwiftUI
* **IDE:** Xcode
* **Platform:** iOS
* **Simulator:** iOS Simulator

## Project Setup

While creating the project in Xcode:

* Select **iOS → App**
* App Name: `hello world`
* Interface: **SwiftUI**
* Language: **Swift**
* Core Data: Not selected
* Unit Testing: Not selected
* Git Repository: Enabled

## Project Structure

The basic project contains two main Swift files:

```text
hello_world/
├── hello_worldApp.swift
└── ContentView.swift
```

### hello_worldApp.swift

This file defines the main application and launches `ContentView` using `WindowGroup`.

### ContentView.swift

This file contains the main UI of the application. The `Text` view displays:

```swift
Text("Hello, world!")
    .padding()
```

## Running the App

The application can be run without a physical iPhone by selecting an **iOS Simulator** in Xcode and pressing the **Play** button. Xcode builds the project and runs it on the selected simulator.

## SwiftUI Preview

SwiftUI also provides a preview feature that allows the UI to be viewed without running the complete application on a simulator. Changes made to the code can be reflected in the preview immediately.

## Key Concepts

* Creating an iOS project in Xcode
* Swift programming language
* SwiftUI framework
* `App` and `View` structures
* `WindowGroup`
* `Text` view
* iOS Simulator
* SwiftUI Preview

## Conclusion

This practical provides a basic introduction to **iOS application development using SwiftUI**. It demonstrates project creation, SwiftUI views, running an application in the simulator, and using SwiftUI Preview.
