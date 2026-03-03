# ScavengerAI - AI-Powered Scavenger Hunt
ScavengerAI is a mobile game for Android that utilizes real-time Computer Vision and Artificial Intelligence to transform the physical world into a dynamic playground.

The premise is straightforward: the AI assigns a mission (e.g., "Find a cup") and the player has a limited window of time to point the camera and prove they have located the object.

The app was release in Portuguese (Brazil). English version will be uploaded soon.

## Key Features
**Dynamic Missions Assignment:** At the start of each round, the game engine randomly selects a target object from a curated list of indoor items. This ensures a unique challenge every time the application is launched.

**Real-Time AI Vision Loop:** Once the game begins, the IA inference engine analyzes the camera feed at high frame rates. It continuously scans the environment, attempting to match physical objects with the assigned mission target. For this, there is a seamless integration with a pre-trained YOLO (You Only Look Once)[1] model (v11) for instantaneous recognition of object.

**Permissions:** The game needs access to the device's camera and storage, only. It runs offline, so no personal data are being collected for any purpose.

**Ads:** There is no ads in this game. But, if you are confortable to, you can donate! =)

## Installation and Gameplay
To test ScavengerAI on your device:

- Navigate to the Releases section of this repository.
- Download the app-release.apk file.
- On your Android device, enable "Install from unknown sources" in the settings.
- Launch the application, grant camera permissions, and begin the hunt.

**Note:** This project is a technical demonstration of on-device AI capabilities for mobile entertainment.
Furthermore, this app was designed for running on Android. 

## License
This project is protected under a Personal Use License. You are permitted to download, install, and share the official link to this repository. Modifications, reverse engineering, or commercial distribution are strictly prohibited. See the LICENSE.md file for full details.

## About the Developer
This project was developed as a technical portfolio piece to explore the boundaries of real-time image processing on mobile hardware.

LinkedIn: [https://www.linkedin.com/in/filipeolcosta/]
CV Lattes: [https://lattes.cnpq.br/9296763269153204] 
Contact: [olcostafilipe@gmail.com]
