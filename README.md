**FOR VISUAL ANALYSIS;**

*Tools to be used:*

- PLC: To control the production line and sensors (including cameras).
- Optical Cameras: To take images of products or the production process.
- Python and OpenCV: To process and analyse images.
  

*System Components and Functions:*

**1- Optical Cameras:** Continuously takes images from the production line.

**2-Image Processing Software (Python/OpenCV):** Processes incoming images, checks that products are the correct size and shape, detects colour errors or other visual defects.

**3-PLC:** Using the information from the cameras and image processing software, it controls the machines on the production line, rejects faulty products and stops or changes the settings of the production line when necessary.


**Visual Capture:**

- Cameras capture images of products at set intervals or continuously.
  
**Visual Processing:**

- Images are analysed according to certain criteria (e.g. size, shape, colour, etc.).
  
- Quality control tests are performed for each product using Python and OpenCV.
  
- Signals are generated for defective products.

**PLC Control:**

- The PLC acts according to the signals from the image processing software.
  
- It activates separator mechanisms to separate defective products.
  
- If necessary, it adjusts or stops the speed of the production line.
  
**Reporting and Monitoring:**

- The system logs production data and quality control results.
  
- It generates reports on production efficiency and quality level.

**FOR SOUND ANALYSIS;**
- Python software is suitable for sound analysis and library access is the most advantageous.

- A few of the libraries to be used here are ‘libros and matplotlib’.

- With this library; sound is loaded, motion times and duration are taken and sound is output.



**DATA COLLECTION and PREPROCESSING;**
- **Sensor Integration:** Continuously collecting data from sensors to measure current and voltage. These sensors can provide real-time data streaming.
  
- **Data Cleaning and Normalisation:** Cleaning and normalisation of the collected data is important for the correct operation of the AI model. Cleaning noises, missing data and normalising different scales is done at this stage.


**Feature Engineering;** 
- **Feature Extraction:** It is ensured that the model learns better by extracting time and frequency based features from current and voltage data. For example, maximum, minimum and average values, fluctuations and peak values.

 **Model Training;**
 - **Anomaly Detection and Prediction Model:** Using machine learning or deep learning techniques, models are developed that detect unexpected changes in current and voltage or potential faults. For example, an LSTM (Long Short-Term Memory) network can be used to learn trends and patterns in time series data.

**Decision Making and Warning System;**
- **Automatic Alerts:** The model automatically sends alerts when it detects changes above set thresholds. This is critical for protecting equipment and optimising maintenance schedules.

- **Continuous Learning:** The model is continuously updated and refined with new data, making it more accurate and reliable over time.

**Integration and Visualisation;**
- **Dashboard Integration:** Analysis results are visualised in a way that decision makers and technicians can easily access and understand. These dashboards provide real-time data monitoring and control.

**Technology and Tools;**
- **Artificial Intelligence Frameworks:** Artificial intelligence and machine learning libraries such as TensorFlow, PyTorch.

- **Data Flow Management:** Real-time data flow management systems such as Apache Kafka, RabbitMQ.

- **Dashboard Tools:** Real-time data visualisation tools such as Grafana, Kibana.

