# TR102-Training-Diary
Daily Training Diary for TR-102 Internship by Kashish Gujral
## Day 1 – 25 June 2025 (Tuesday)

### ✅ Topics Covered:
- Introduction to Smart Fusion
- Definition, Benefits, Applications & Challenges of IoT
- Need and Future Scope of IoT
- Types of IoT and IoT Services
- Introduction to Arduino UNO Board
- Basics of Machine Learning
- Python Programming (General Concepts)

### Guided By:
Training Instructor (Classroom-Based)

### 📘 Concepts Learned:
- IoT = Internet of Things: A network of physical devices connected via the internet.
- IoT Benefits: Smart living, energy saving, automation.
- Challenges: Data privacy, scalability, security.
- Arduino UNO: Microcontroller board used for IoT projects.
- ML vs IoT: ML makes IoT smarter with decision-making.
- Python Basics: Print statements, variables, etc.

### 🔧 Tools / Platforms Discussed:
- SmartFusion Software (Introduction)
- Arduino UNO Board (Theory)
- Python (Beginner-level)

###  Reflections:
Today's session gave a good foundation of IoT and SmartFusion. I understood how sensors/devices work with microcontrollers like Arduino and how Python is essential for logic in IoT-based systems. Looking forward to practical implementation from tomorrow.

## 📅 Day 2 – 26 June 2025 (Wednesday)

### ✅ Topics Covered:
- IoT Architecture View – 7 Layered Model
- Sensors & Smart Sensors
- Actuators & Smart Actuators
- Robotic Systems & Smart Appliances
- Sensor-Actuator Pair Concept
- Walkwi Simulator Introduction
- Difference between Arduino, NodeMCU & Raspberry Pi
- Python (Basics)
- Pin Configuration of Sensors
- LED, DHT11 & PIR Sensor Connections with Arduino
- Installing Arduino IDE & Anaconda

### Guided By:
Training Instructor (Classroom-Based)

### 📘 Concepts Learned:
- Role & levels of IoT architecture
- How smart sensors/actuators function
- What makes a system “smart”
- Simulators are used to test virtual IoT connections
- Arduino Code: setup() runs once, loop() keeps reading sensors
- DHT11 reads humidity & temp, PIR detects motion
- Basic pin configuration & wiring logic

### 🔧 Tools / Platforms Used:
- Walkwi Simulator
- Arduino UNO
- Arduino IDE
- Anaconda (setup started)

###  Tasks Assigned:
- Code on simulator to read humidity & temperature using DHT11 + Arduino
- Install Anaconda
- Compare NodeMCU, Raspberry Pi, Arduino boards

###  Reflections:
Simulators helped me understand connections without hardware. Also started comparing microcontroller boards. Wiring and sensor logic is becoming more clear.

---

##  Day 3 – 27 June 2025 (Thursday)

### ✅ Topics Covered:
- Cloud Computing for IoT
- Traditional vs Distributed Computing
- Goals of Distributed Systems
- Client-Server Architecture
- Cluster Computing, Grid Computing & Utility Computing
- Cloud Computing Basics & Benefits
- Virtualization & Types of Virtualization
- Cloud Framework, Service Models (IaaS, PaaS, SaaS)
- Deployment Models (Public, Private, Hybrid, Community)
- Introduction to ThingSpeak & MATLAB
- Connecting ESP8266 (Wi-Fi Module) to Read DHT11 Sensor Data
- Sending Data to ThingSpeak Cloud via HTTP

###  Guided By:
Training Instructor (Classroom-Based)

### 📘 Concepts Learned:
- Cloud computing helps store & process IoT data remotely
- Distributed computing improves performance across devices
- ESP8266 is used to connect sensors with the internet
- DHT11 gives temp & humidity data; ThingSpeak helps visualize it
- Learned how to connect hardware to ThingSpeak via HTTP request
- Virtualization allows multiple OS on a single system

###  Tools / Platforms Used:
- ThingSpeak Cloud Platform
- ESP8266 Wi-Fi Module
- DHT11 Sensor
- MATLAB (linked with ThingSpeak)

###  Tasks & Assignments:
- 📌 Write difference between:
  - Google App Engine
  - Microsoft Azure
  - Amazon EC2
- 📌 Complete Wi-Fi based Temperature & Humidity Project
- 📌 Submit project report after holidays

### Reflections:
The cloud and IoT connection part was very new for me, but interesting. I understood how data from sensors can be stored and monitored online. Looking forward to completing the Wi-Fi-based mini project during the break.

## 📅 Day 4 – 30 June 2025 (Monday)

###  Topics Covered:
- Data Acquisition in IoT
- Interfacing ESP32 with DHT22 Sensor
- Reading Temp & Humidity using Arduino Code
- Connecting ESP32 to Wi-Fi in Wokwi Simulator
- Sending Data to ThingSpeak using HTTP GET Request
- Viewing Sensor Data on ThingSpeak (Graph View)

### 🧑‍🏫 Guided By:
Training Instructor

### 📘 Concepts Learned:
- Data acquisition means collecting sensor data for cloud use
- DHT22 is used for accurate temp & humidity readings
- ESP32 helps connect to Wi-Fi and send data to the cloud
- HTTP GET method used to push sensor values to ThingSpeak
- API keys are needed to write data securely to channels
- HTTP status code 200 = success → confirmed data upload

###  Tools / Platforms Used:
- Wokwi Simulator
- ESP32 + DHT22
- ThingSpeak Cloud
- Arduino IDE (Code logic)

###  Task Performed:
- Simulated ESP32 + DHT22 in Wokwi
- Wrote Arduino code to read sensor data
- Sent data to ThingSpeak using correct API key
- Verified output using HTTP response and live graph

###  Reflections:
Today's class was really practical. Sending real time data to Thingspeak felt like a proper IOT setup. It help me understand how cloud and sensor devices actually talk to each other.


##  Day 5 – 1 July 2025 (Tuesday)

###  Topics Covered:
- Overview of Photoresistor (LDR) and Light Detection
- Basics of Interfacing Servo Motor with Arduino
- Understanding Analog Input from LDR
- PWM (Pulse Width Modulation) for Servo Control
- Sending LDR & Servo Data to ThingSpeak Cloud

### Guided By:
Training Instructor

### 📘 Concepts Learned:
- LDR changes resistance based on light intensity
- Arduino reads analog signals to measure light levels
- Servo motor angle is controlled using PWM signals
- Interfacing both sensor and actuator in one circuit
- Data from LDR & servo can be uploaded to ThingSpeak using API key

### Tools / Platforms Used:
- Arduino UNO
- LDR Sensor
- Servo Motor
- ThingSpeak Cloud Platform
- Arduino IDE / Wokwi Simulator

###  Tasks Performed:
- Task 1: Detect light using photoresistor and send data to ThingSpeak
- Task 2: Interface servo motor, control angle, and send updates to ThingSpeak
- Observed output on ThingSpeak using HTTP response & graphs

### Reflections:
Today’s tasks helped me understand both input and output devices in IoT. Controlling servo based on LDR readings and seeing the result on ThingSpeak felt like a real-world automation example.

---

## Day 6 – 2 July 2025 (Wednesday)

###  Topics Covered:
- Data Preprocessing in Machine Learning
- Handling Missing Values (NaN)
- Data Scaling using MinMaxScaler
- Normalization Techniques
- Train-Test Split (80% train, 20% test)
- Python Libraries: Pandas, NumPy, Scikit-learn

### Guided By:
Training Instructor

### 📘 Concepts Learned:
- Missing values were handled using mean, median, and mode
- MinMaxScaler was used to scale features between 0 and 1
- Normalization helped bring data into the same scale
- Pandas makes it easy to clean and explore tabular data
- Learned how train-test split is used to separate data for ML models

### Tools / Platforms Used:
- Google Colab / Jupyter Notebook
- Python 3.x
- Libraries: pandas, numpy, sklearn

###  Tasks Performed:
- Created a CSV file `student_data.csv` with columns: Name, ID, Math, Science, English
- Inserted 5–10 rows with some missing (NaN) values
- Loaded CSV into Pandas DataFrame
- Counted missing values using `df.isnull().sum()`
- Filled missing values using:
  - Mean
  - Median
  - Mode
- Displayed updated dataset after cleaning
- Performed MinMax Scaling on numeric columns
- Applied normalization to bring data into 0–1 range

###  Reflections:
This was my first time working with real dataset cleaning. I liked how pandas made it easy to handle NaN values and scale features. It felt like real data science work.
