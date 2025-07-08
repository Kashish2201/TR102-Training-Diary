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

---



##  Day 7 – 3 July 2025 (Thursday)

### Topics Covered:
- Basics of Data Visualization
- matplotlib: Line, Bar, Scatter, Histogram, Pie Chart
- Seaborn: Line Plot, Boxplot, Heatmap
- Tips Dataset (for practice)
- Real-Time Plotting with `plt.ion()`
- EDA (Exploratory Data Analysis) Introduction

###  Guided By:
Training Instructor

### 📘 Concepts Learned:
- `matplotlib.pyplot` is used for simple graphs
- Seaborn is built on matplotlib and gives better styling
- `sns.boxplot()`, `sns.heatmap()` used on `tips` dataset
- `plt.ion()` helps make live/real-time plots
- EDA helps understand data before using ML

###  Tools / Platforms Used:
- Kaggle Kernel
- Python 3.x
- Libraries: matplotlib, seaborn
- Dataset: `tips`

###  Tasks Performed:
- Plotted basic graphs using matplotlib
- Used seaborn for boxplot and heatmap
- Visualized real-time data using `plt.ion()` and `random` values
- Practiced on `tips` dataset
- Read EDA intro to prepare for next topic

### Reflections:
Today’s session was creative. I enjoyed learning how visuals can tell the story of data. Seaborn felt more user-friendly than matplotlib. I’m now curious about exploring EDA in detail.

---

## Day 8 – 4 July 2025 (Friday)

###  Topics Covered:
- Recap of Exploratory Data Analysis (EDA)
- Why EDA is important before Machine Learning
- Steps in EDA:
  - Data Types
  - Summary Stats
  - Missing Values
  - Correlation & Visuals
- Real-Time IoT Dashboard – Mini Project Introduction

###  Guided By:
Training Instructor

### 📘 Concepts Learned:
- EDA helps to understand patterns, data quality, and relationships
- Before applying ML, data must be cleaned and explored properly
- IoT Dashboard Project: Sensor → ESP32 → ThingSpeak → Web Page
- Flow of real-time data from sensor to graph via cloud
- Custom dashboards can be built using HTML + JS

###  Tools / Platforms Discussed:
- ESP32 Board
- Wokwi Simulator
- ThingSpeak Cloud
- HTML / JavaScript

###  Tasks Assigned:
- Prepare overview of EDA with key steps
- Study the Real-Time IoT Dashboard project flow
- Understand the architecture: Sensor → WiFi → Cloud → Dashboard
- Sketch or refer to flowchart showing how data moves in the system

###  Reflections:
Today’s session gave me better clarity on both data analysis and real-time IoT systems. I found the dashboard idea interesting, and I look forward to building it practically.

---

## Day 9 – 7 July 2025 (Monday)

###  Topics Covered:
- Introduction to Machine Learning
- Traditional Programming vs. Machine Learning
- AI vs ML vs Deep Learning
- Training vs Testing Phase
- Types of ML:
  - Supervised Learning (Classification, Regression)
  - Unsupervised Learning (Clustering, Association)
  - Reinforcement Learning (Reward-based Learning)
- ML Algorithms:
  - Linear & Logistic Regression
  - Decision Tree, Random Forest, SVM
  - K-Means, K-NN, Hierarchical Clustering, PCA
  - Apriori Algorithm
  - Basics of Neural Networks

###  Guided By:
Training Instructor

### 📘 Concepts Learned:
- ML models learn from data and improve over time
- Supervised learning uses labeled data; Unsupervised does not
- Reinforcement learning is based on reward-feedback loop
- Regression predicts values; classification predicts categories
- Clustering helps in grouping similar data points
- Neural networks are the base of deep learning models

###  Tools / Platforms Used:
- Google Colab / Jupyter Notebook
- Python 3.x
- Libraries: pandas, sklearn, numpy, matplotlib

###  Tasks Performed:
- Wrote differences between Supervised, Unsupervised, and Reinforcement Learning
- Practiced Linear Regression with a sample dataset
- Calculated Mean Squared Error (MSE)
- Understood residuals and plotted regression line

###  Reflections:
Today gave me a solid understanding of how ML works and the variety of algorithms available. The hands-on with regression helped me understand error metrics and prediction accuracy.

---

##  Day 10 – 8 July 2025 (Tuesday)

###  Topics Covered:
- K-Means Clustering Algorithm (Unsupervised Learning)
- Smart City Case Study – Ludhiana
- Online Learning in ML
- Semi-Supervised Learning

###  Guided By:
Training Instructor

### 📘 Concepts Learned:
- K-Means groups similar data without labels
- Centroids are updated until convergence is reached
- K-Means used in customer segmentation, zone classification, etc.
- Online Learning is for continuous data (used in fraud detection, recommender systems)
- Semi-Supervised Learning uses both labeled and unlabeled data
- ML can be applied to real-world smart city problems

###  Tools / Platforms Used:
- Google Colab / Python
- Libraries: sklearn, matplotlib, seaborn, pandas

###  Tasks Performed:
- Implemented K-Means Clustering on sample unlabeled dataset
- Visualized how data points were grouped into clusters
- Observed how centroids change with each iteration
- Discussed how ML could help Ludhiana with traffic, pollution, waste, etc.

###  Case Study: Smart City – Ludhiana
- Issues found: Traffic, pollution, semi-automated waste system
- Discussed use of K-Means to classify city zones for improvement

###  Reflections:
Learning clustering through K-Means was easy to follow and fun to visualize. The Ludhiana Smart City case helped me see how ML can be useful in urban planning and real problems.
