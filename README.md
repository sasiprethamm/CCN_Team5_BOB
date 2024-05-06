# ITCS 6166: Computer Comm & Networks - Project
### Group Number: 5

#### Group Members:
- Madhavi Badugu
- Nikitha Basavanna
- Sasi Pretham Nakka
- Manas Penmetsa

## Project Overview
This project aims to investigate the role of AI, specifically generative AI and reinforcement learning, in enhancing networking performance. The focus is on using minimal network bandwidth for high-quality video streaming services. Please see section 3 for execution instructions for running our applications.

## Project Deliverables

### 1. Selected Paper/Topic
**Title:** BoB: Bandwidth Prediction for Real-Time Communications Using Heuristic and Reinforcement Learning  
**Repository:** [BoB GitHub Repository](https://github.com/NUStreaming/BoB)

------------------------------------------------------------------------------------------------

### 2. Inference Codes Execution / Replicated Results
**Objective:** Replicate results using the inference codes from the selected paper.  
**Minimum Requirement:** Successful execution of test/inference codes.  
**Demonstration Video:** [Test/Inference Codes Execution](https://www.youtube.com/watch?v=WBudCzzKtZk)

[![YouTube Video](https://img.youtube.com/vi/fXW81C41r4k/0.jpg)](https://www.youtube.com/watch?v=WBudCzzKtZk)

#### Execution Instructions:
1. Clone the BoB repository from GitHub. [BoB GitHub Repository](https://github.com/NUStreaming/BoB)
2. Install the required dependencies.
3. Navigate to the environment folder.
4. Run 'make all' command in terminal.
5. Run the 'run_with_tc' script by entering ./run_with_tc.sh in Terminal.
6. Review the output for consistency with the results reported in the paper.

------------------------------------------------------------------------------------------------

### 3. Video Streaming Application
**Objective:** Build a video streaming application with sender and receiver, using the WebRTC real-time networking protocol.

**Overview:** Our project includes a mobile (Folder: Android Mobile App) and desktop application (Folder: Desktop App). Please see below specific execution instructions for each application.

**Demonstration Video:** [Android App Execution](https://www.youtube.com/watch?v=O5xuMMcvR8U)

[![YouTube Video](https://img.youtube.com/vi/fI6-y4lLvTM/0.jpg)](https://www.youtube.com/watch?v=O5xuMMcvR8U)

#### Android Application Execution Instructions:
- **Setup Instructions**:
1. Clone the project repository
2. Ensure Android Studio is installed with the required SDKs and emulators.
3. Ensure IntelliJ IDEA is installed.
4. Open the server project found in the 'Video-Streaming-App-backend' folder using IntelliJ IDEA.
5. Find the 'Application.kt' file and run using the green run button (shown below),
6. Open the android project found in the 'Video-Streaming-App' folder using Android Studio.
7. Add your local IP address in the `local.properties` file as `SIGNALING_SERVER_IP_ADDRESS`.
8. Build and run the application on your Android device or emulator. (Need two devices to test, or one emulator and one real android device)

<img width="835" alt="image" src="https://github.com/sasiprethamm/proj_today/assets/143413924/bb83e5f1-c0cc-424c-9655-9fce78c5e1fa">

<img width="1089" alt="image" src="https://github.com/sasiprethamm/proj_today/assets/143413924/8e916e32-326b-4311-b75f-7e3734f2478b">

<img width="1283" alt="image" src="https://github.com/sasiprethamm/proj_today/assets/143413924/514d23b5-72fd-4f49-8686-9e6641128d4d">

------------------------------------------------------------------------------------------------

**Demonstration Video:** [Desktop App Execution](https://www.youtube.com/watch?v=WBudCzzKtZk)

[![YouTube Video](https://img.youtube.com/vi/I88tBa0Dz1g&t=1s/0.jpg)](https://www.youtube.com/watch?v=WBudCzzKtZk)

#### Desktop Application Execution Instructions:
- **Setup Instructions**:
1. Clone the project repository
2. Make sure you have Node.js and npm installed on your machine.
3. To run the server - Enter npm run devStart in Terminal
4. Open other terminal 
5. Run the peerserver peer js --port 3001
6. Open your browser and go to http://localhost:3000.
7. Copy the URL which has a room ID appended at the end
8. Copy and open it in other window

<img width="1470" alt="image" src="https://github.com/sasiprethamm/proj_today/assets/143413924/6b3db899-147d-47c7-a71d-493826a60698">


------------------------------------------------------------------------------------------------
### References and Resources
**Description:** See below references used in building our applications.
- **WebRTC GitHub Repo**: [GetStream/webrtc-android](https://github.com/GetStream/webrtc-android)
- **Article Reference**: "Building a Video Chat App: WebRTC in Jetpack Compose" [Reference](https://getstream.io/blog/webrtc-on-android/)
