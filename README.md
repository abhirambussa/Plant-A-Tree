#PlantATree-AR App

##Overview

PlantATree-AR is an augmented reality (AR) application developed using ARCore. This app allows users to visualize different tree models in the real world using their Android devices.

##Prerequisites

Before running the PlantATree-AR app, ensure you have the following prerequisites installed:

* Android Studio
* ARCore supported Android device

###Getting Started

####Clone the Repository:

```
git clone https://github.com/abhirambussa/Plant-A-Tree.git
cd PlantATreeAR
```

####Open Project in Android Studio:

Open Android Studio and select "Open an existing Android Studio project." Navigate to the cloned PlantATreeAR directory and select it.

####Sync Gradle:

Android Studio will automatically prompt you to sync the project with Gradle. Click on "Sync Now" if not done automatically.

####Run the App:

* Connect your Android device to your computer.
* Make sure USB debugging is enabled on your device.
* Click on the "Run" button (green triangle) in Android Studio to install and run the app on your device.

####Explore AR Tree Models:

* Once the app is installed on your device, launch it.
* Point your device camera to a flat surface to enable AR tracking.
* Browse and select different tree models from the app interface.

####Interact with AR Trees:

* Tap on the screen to place the selected tree model in the real world.
* Use gestures to rotate and scale the tree model for a better viewing experience.

####Project Structure
The project is organized as follows:

* **app:** Contains the main application code.
    * src/main/java/com/ar/treeco/: Kotlin source files.

    * src/main/res: Resources such as layout files, images, and 3D model files.

* gradle: Gradle build files.
* gradle/wrapper: Contains the Gradle wrapper files.

* .gitignore: Specifies files and directories to be ignored by Git.

* README.md: Project documentation.
* plant_ar_video.mp4: Sample video demonstrating the app in action.

####Additional Notes

* The sample data directory contains 3D models of different trees, along with their textures.
* The raw directory under res contains 3D model files in SFB format.
* Customize the app by modifying code in the src directory and resources in the res directory.