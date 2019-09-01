# Digital-HealthCare

- Sign in to Amazon Sumerian with your AWS account
- Sumerian Basics: Creating a TV Room
- Scripting Basics tutorial
- Clone the SumerianARCoreStarter repository
- Download the ARCore app to your mobile device
## You also need the following:

- Basic knowledge of Android app development using Android Studio and Java
- An ARCore-capable Android device (a Google Pixel phone or Samsung Galaxy S7/S8 device)
- Basic familiarity with the Git version control system and GitHub


### Step 1: Start a New Project in Sumerian
- From the Dashboard, navigate to the scene templates.
- Choose the Augmented Reality scene template.
### Step 2: Add a Drone to the Scene
- We’ll add the Drone asset as a child of the ARAnchor entity that is already present in the scene.

### Choose Import Assets in the top menu bar.
In the asset library, search for and then select “Drone”.
Expand the Drone pack in the Assets panel, and then drag the Drone entity (the hexagon icon) onto the ARAnchor entity that already exists in the Entities panel.

### Step 3: Publish the Scene
We’ll publish the scene so that it’s accessible to the Android app.

In the top right corner, choose Publish.

If you want to host publicly, choose Create Public Link.

Make a note of the URLm, or click Copy. The Android app uses this URL to access the scene.