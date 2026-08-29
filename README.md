<h1 align="center">Mohamed BAIHICH</h1>

<h3 align="center">Embedded Systems & IoT | Edge AI</h3>

<p align="center">
  Master d’Excellence Graduate in Computer Engineering & Embedded Systems
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mohamed-baihich/">
    <img src="https://img.shields.io/badge/LinkedIn-Mohamed%20BAIHICH-0A66C2?style=flat&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:hamdi.baihich@gmail.com">
    <img src="https://img.shields.io/badge/Email-hamdi.baihich%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://wokwi.com/makers/medbaihich">
    <img src="https://img.shields.io/badge/Wokwi-Embedded%20Labs-2C3454?style=flat"/>
  </a>
</p>

---

## 👨‍💻 About Me

I am a **Master d’Excellence graduate in Computer Engineering & Embedded Systems** with hands-on experience in **embedded systems, IoT, Edge AI, machine learning, backend development, and distributed systems**.

My work focuses on building complete systems that connect **hardware, edge computing, intelligent data processing, communication protocols, and backend services**.

For my final-year project at **AZURA / MARAISSA**, I designed and implemented an **Edge-IoT platform for intelligent tomato disease monitoring**, combining Raspberry Pi, TensorFlow Lite, MobileNetV2, FAISS, MQTT/RabbitMQ, Django/DRF, React, and Docker.

The AI pipeline was evaluated on **6,383 images across 15 classes**, achieving **98.7% accuracy for leaf/fruit routing**, while MobileNetV2 generated **1,280-dimensional embeddings** for similarity-based analysis.

---

## 🛠️ Core Technologies

### Programming

<p>
  <img src="https://skillicons.dev/icons?i=c,cpp,python,js" />
</p>

`C` · `C++` · `Python` · `JavaScript` · `Assembly` · `SQL`

### Embedded Systems & IoT

`ESP32` · `Raspberry Pi` · `ARM Cortex-M` · `RTOS` · `Arduino`

`MQTT` · `LoRaWAN` · `TLS` · `I2C` · `SPI` · `UART` · `RPC`

### Edge AI & Machine Learning

<p>
  <img src="https://skillicons.dev/icons?i=tensorflow" />
</p>

`TensorFlow` · `TensorFlow Lite` · `MobileNetV2` · `FAISS`

`Scikit-learn` · `Deep Learning` · `Machine Learning` · `Pandas` · `NumPy`

### Backend, Web & DevOps

<p>
  <img src="https://skillicons.dev/icons?i=django,react,docker,linux,git" />
</p>

`Django` · `Django REST Framework` · `React` · `RabbitMQ`

`Docker` · `Docker Compose` · `Node-RED` · `Git` · `Linux`

### Big Data & Cloud

`Apache Spark` · `Hadoop / HDFS` · `Kafka` · `MongoDB` · `AWS`

---

# 🚀 Featured Projects

## 🌱 Edge-IoT Tomato Disease Monitoring

**[View Repository](https://github.com/medbaihich/projet-tomate-monitoring)**

End-to-end **Edge-IoT and Edge AI platform** developed for intelligent monitoring of tomato diseases.

The system performs local image processing on a Raspberry Pi, extracts visual embeddings using MobileNetV2, routes images between fruit and leaf pipelines, performs similarity search with FAISS, and sends results to a complete supervision platform.

**Key results**

- Evaluated on **6,383 images**
- **15 visual classes**
- **98.7% leaf/fruit routing accuracy**
- **1,280-dimensional MobileNetV2 embeddings**
- End-to-end pipeline from image capture to dashboard alerts
- Vector-first architecture to reduce unnecessary transmission of raw images

**Tech Stack**

`Raspberry Pi` · `TensorFlow Lite` · `MobileNetV2` · `FAISS`

`MQTT` · `RabbitMQ` · `Django REST Framework` · `React` · `Docker`

---

## 🌲 Forest Fire Prediction & Real-Time Monitoring

**[View Repository](https://github.com/medbaihich/Fire-Forest_Prediction)**

End-to-end Big Data system for forest-fire risk prediction using historical weather data and simulated real-time IoT streams.

The architecture combines batch Machine Learning training with real-time stream processing.

**Model Performance**

- Accuracy: **~85.5%**
- ROC-AUC: **~0.928**

**Architecture**

`Historical Data → HDFS → Spark ML → Random Forest`

`IoT Simulation → Kafka → Spark Structured Streaming → MongoDB`

**Tech Stack**

`PySpark` · `Apache Spark` · `Kafka` · `Hadoop/HDFS`

`MongoDB` · `Random Forest` · `Docker`

---

## 🔐 IoT File Integrity Monitoring

**[View Repository](https://github.com/medbaihich/IoT_file_integrity_monitoring)**

Proof-of-concept security system running on ESP32 that continuously monitors critical files for unauthorized modifications.

Features include:

- SHA-256 integrity verification
- Real-time tampering detection
- Automatic file recovery
- Security event logging
- Visual hardware alerts
- Attack simulation

**Tech Stack**

`ESP32` · `MicroPython` · `SHA-256` · `Wokwi`

---

## 💡 Smart Building Light Control System

**[View Repository](https://github.com/medbaihich/Smart-Building-Light-Control-System)**

Smart building platform designed to manage lighting systems across buildings, floors, and zones.

Features include:

- Zone and lamp management
- Automatic lighting schedules
- Role-based permissions
- Energy-consumption analytics
- Activity logging
- Hardware communication through XML-RPC
- Simulation mode for testing without physical hardware

**Tech Stack**

`Python` · `Django` · `Django REST Framework`

`XML-RPC` · `Celery` · `JavaScript` · `PostgreSQL / SQLite`

---

## 🖼️ Deep Learning Image Retrieval

**[View Repository](https://github.com/medbaihich/Deep_Learning-image_retrieval)**

Content-based image retrieval engine using deep neural-network features instead of traditional pixel-based comparison.

The system extracts high-level visual representations from images and retrieves semantically similar images using nearest-neighbor search.

**Tech Stack**

`Python` · `CNN` · `Deep Features` · `k-NN` · `Turi Create`

---

## ☁️ IoT Weather Station

**[View Repository](https://github.com/sabri-abdelaaziz/station_meteo)**

Connected IoT system for environmental-data acquisition, visualization, and predictive analysis.

**Tech Stack**

`IoT` · `Sensors` · `Django` · `AWS` · `Machine Learning`

---

# 🤖 AI & Data Science Projects

| Project | Description | Domain |
|---|---|---|
| **[Product Sentiment Analysis](https://github.com/medbaihich/Analyzing-products-sentiment)** | Sentiment classification of Amazon product reviews using Logistic Regression and text features | NLP / ML |
| **[Music Recommendation System](https://github.com/medbaihich/Song-recommender)** | Popularity-based and item-similarity recommender with precision/recall evaluation | Recommender Systems |
| **[Image Classification with Deep Features](https://github.com/medbaihich/Image-Classification-With-Deep-Features)** | Image classification using transfer-learning-based deep features | Deep Learning |
| **[Document Retrieval](https://github.com/medbaihich/Document-retrieval)** | Information retrieval system based on TF-IDF and vector similarity | NLP / Information Retrieval |

---

# 🎓 Certifications

- **[Arm Cortex-M Architecture & Software Development Specialization](https://www.coursera.org/account/accomplishments/specialization/KHEZJXVXVOWT)** — ARM
- **[Hands-on Internet of Things Specialization](https://www.coursera.org/account/accomplishments/specialization/QTQRZFA3M1HX)** — University of Illinois
- **[Embedded Software & Hardware Architecture](https://www.coursera.org/account/accomplishments/verify/JRHS00CVFHDJ)** — University of Colorado Boulder
- **[Machine Learning Specialization](https://www.coursera.org/account/accomplishments/specialization/NRD0QAONCYQZ)** — University of Washington
- **[Embedding Sensors and Motors Specialization](https://www.coursera.org/account/accomplishments/specialization/T9PUB0K2TNXV)** — University of Colorado Boulder
- **[Introduction to Automotive Embedded Systems](https://www.coursera.org/account/accomplishments/verify/1UUVHIJ9Q7HN)** — Starweaver / Coursera

---

# 🔬 Embedded & IoT Labs

<details>

<summary><b>View Wokwi simulations</b></summary>

<br>

| Project | Description | Demo |
|---|---|---|
| 🌡️ IoT Environment Monitor | ESP32 monitors temperature, humidity, CO₂ and light while controlling actuators | [Open](https://wokwi.com/projects/397895913864522753) |
| 🔒 MQTT over TLS | ESP32 + MicroPython + DHT22 with secure MQTT communication | [Open](https://wokwi.com/projects/418744222552611841) |
| 📡 Raspberry Pi Pico MQTT | Pico publishes sensor measurements over MQTT | [Open](https://wokwi.com/projects/418715367337991169) |
| 📶 ESP32 IoT Monitor | Temperature and humidity telemetry over MQTT | [Open](https://wokwi.com/projects/418625273202124801) |
| 🔐 Password Lock | Keypad + LCD + Servo access-control system | [Open](https://wokwi.com/projects/388780209371716609) |
| 🎹 Electronic Piano | Embedded button matrix and buzzer exercise | [Open](https://wokwi.com/projects/387929782406976513) |

</details>

---

# 📚 Other Technical Work

- **[Real-Time Systems Labs](https://github.com/medbaihich/TP1_Prog.TempsReel)** — Practical exercises related to real-time programming.
- **[Python Labs](https://github.com/medbaihich/TravauxPratiques_python)** — Python programming exercises and experiments.

---

# 📫 Contact

<p align="center">

<a href="mailto:hamdi.baihich@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-hamdi.baihich%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<a href="https://www.linkedin.com/in/mohamed-baihich/">
  <img src="https://img.shields.io/badge/LinkedIn-Mohamed%20BAIHICH-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="https://wokwi.com/makers/medbaihich">
  <img src="https://img.shields.io/badge/Wokwi-Embedded%20Projects-2C3454?style=for-the-badge"/>
</a>

</p>
