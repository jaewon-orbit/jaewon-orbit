# Hi, I'm Jaewon

I build systems that connect software, simulation, and physical hardware.

My projects span remote actuator control, ROS–Unity integration, and simulation tooling. **I'm particularly interested in ADAS systems engineering and verification & validation.**

Python · C# · Unity · ROS · Hardware–Software Integration

## Selected Engineering Projects

### 1. [Life Switch](https://github.com/jaewon-orbit/life-switch)

An embedded system that lets me operate an existing lamp switch from my phone. I connected a browser interface, a FastAPI relay, ESP32, OpenRB-150, and a DYNAMIXEL motor without changing the lamp's wiring.

The first version needed a connected PC. That felt excessive for switching a lamp on and off, so I moved to ESP32-based control. I also addressed mismatches between the displayed state and motor position by requesting position on page load or browser reconnection and using position feedback after a button press, rather than polling continuously. The project taught me to adapt the hardware and communication approach to the actual job.

`Python` · `FastAPI` · `WebSocket` · `ESP32` · `DYNAMIXEL`  
[Demo](https://www.youtube.com/watch?v=OXimIOwr_dM)

### 2. [Unity ROS1 Pick-and-Place](https://github.com/jaewon-orbit/Unity-ROS1-Pick-and-Place-Tutorial)

A hands-on implementation of Unity Robotics Hub's pick-and-place tutorial. I set up ROS1 Noetic in Docker and connected it to Unity over TCP to run a simulated robot arm. The focus was understanding the ROS–Unity interface and keeping the ROS environment consistent.

`Unity` · `ROS1 Noetic` · `Docker` · `TCP`  
[Integration demo](https://www.youtube.com/watch?v=XwEW-qXYQpw) · [Motion planning demo](https://www.youtube.com/watch?v=53JapN59ZOc)

### 3. [Docking Scene](https://github.com/jaewon-orbit/Docking-Scene)

A Unity visualization for a university research project on recovering a fixed-wing UAV with a moving ground vehicle. I created the approach and docking sequence using target points, trigger events, and camera control. The video helped participating institutions and government stakeholders understand the overall concept as the project got underway.

`Unity` · `C#` · `Cinemachine`  
[Demo](https://www.youtube.com/watch?v=tNUVmWVUYQc)

### 4. [Synthetic Dataset Generation](https://github.com/jaewon-orbit/Synthetic-Dataset-Generation)

A Unity image-generation script built to help a friend collect training data for an object-rotation estimation project. It reads yaw, pitch, and roll values from a CSV, rotates a 3D object, and captures a 512×512 image for each pose. This let me generate many views automatically and publish the dataset on Hugging Face.

`Unity` · `C#` · `Synthetic Data`  
[Dataset](https://huggingface.co/datasets/coding-Jay/Synthetic-Datasets-Unity-CV) · [Demo](https://youtu.be/wjZhpO2m6Bk)

## Geospatial Analysis

### [Golden Time Blind Spots](https://github.com/jaewon-orbit/Golden-TIme-Blind-Spots)

During my Monash University internship, I led an analysis of areas beyond a four-minute ambulance coverage threshold in South Korea. The analysis classified about **45% of 18,801 small administrative areas** as outside that threshold. Maps incorporating population density highlighted areas near urban boundaries where additional ambulance coverage could be considered.

Working through the spatial queries taught me why SQL efficiency matters at scale and how to make the findings clear through maps.

`PostgreSQL` · `Spatial SQL` · `QGIS` · `Docker`

## Computer Vision

### [Smombie AR](https://github.com/jaewon-orbit/Smombie-AR)

An Android prototype that uses the phone camera to recognize surroundings such as stairs and crosswalks and display warnings while another app is open. My work focused on collecting images and training the classification model.

`Kotlin` · `PyTorch` · `ONNX Runtime`  
[Demo](https://www.youtube.com/watch?v=ECNi-IljLDc)

## Technical Skills

- **Programming:** Python, C#, SQL; C++/Qt and Kotlin in personal projects
- **Simulation & robotics:** Unity, ROS1, Gazebo, Docker
- **Hardware integration:** ESP32, OpenRB-150, DYNAMIXEL, UART, WebSocket
- **Data & tools:** PostgreSQL, QGIS, Linux

## Other Projects

<details>
<summary>Data analysis, applications, and earlier projects</summary>

- **[NYC Taxi Trend Analysis](https://github.com/jaewon-orbit/NYC_Taxi_Trend_Analysis-Demand_and_Destination_Prediction)** — Python notebooks exploring demand, destinations, and recorded tips in NYC taxi trip data.
- **[Assignment Notification](https://github.com/jaewon-orbit/assignment-notification)** — A university team project that groups assignments by submission status and makes midnight deadlines easier to understand.
- **[Tesla TO-DO List](https://github.com/jaewon-orbit/Tesla-TO-DO-List)** — A personal C++/Qt task-list project exploring a Tesla-style infotainment interface.
- **[Apple visionOS Demo](https://github.com/jaewon-orbit/Apple-Vison-OS-Demo)** — An early exploration of visionOS using the Xcode simulator.
- **[Virtual Campus](https://github.com/jaewon-orbit/Virtual-Campus)** — A team-built Roblox recreation of Gachon University's campus for its 2022 Metaverse Contest.
- **[TankBlitz](https://github.com/jaewon-orbit/TankBlitz)** — A Unity multiplayer tank game where I explored projectile motion and networked gameplay.
- **[Raiden 2D Shooting Game](https://github.com/jaewon-orbit/Raiden-Unity-2D-Shooting-Game)** — A Unity learning project covering object pooling, game states, and scoring.

</details>

## Contact

[Email](mailto:gjeus0707@gmail.com) · [Project videos](https://www.youtube.com/@jtotheone)
