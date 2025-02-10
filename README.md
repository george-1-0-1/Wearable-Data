# Wearable-Data
Use of Wearable Devices to Collect and Analyze Swell Data for Further Research Application


## Methodology

Choosing the right wearable device is crucial for accurate data collection. We opt for a custom-built device with GSM network capabilities to ensure reliable communication and data transfer. This device is designed to capture not only heartbeat data but also SWELL data, including sleep patterns, exercise activities, and lifestyle factors. By selecting a device that meets these criteria, we can gather comprehensive information about an individual's physiological and lifestyle parameters.
Participants in the study are provided with the custom-built wearable device to wear continuously for a specified duration. Throughout this period, the device collects data at regular intervals, creating a detailed profile of the individual's health and lifestyle. By capturing both heartbeat and SWELL data, we gain insights into their cardiovascular health, sleep quality, physical activity levels, and more. This continuous monitoring allows us to track changes over time and identify trends that may impact well-being.

![image](https://github.com/user-attachments/assets/e0443369-afd2-4c19-b1fa-0df82c5a56b2)

Figure 1: Workflow Diagram

Once the data collection period is complete, the collected dataset needs to be transferred for further analysis. We offer two approaches for data transfer: participants can use the dedicated application provided by the wearable device to synchronize and transfer the data directly, or they can opt for a third-party application for secure storage and transfer. Both methods ensure the privacy and integrity of the collected data while facilitating its accessibility for analysis.

The collected dataset is then subjected to advanced data analysis techniques to extract meaningful insights. We employ a neural network classifier, specifically a Standard Feed-forward Neural Network with specific architecture details, to analyze the data based on our research objectives. This involves processing the data through multiple layers of neurons to identify patterns, correlations, and anomalies related to health and lifestyle factors. By leveraging machine learning algorithms and statistical analysis methods, we can uncover valuable insights that inform our understanding of individual health and well-being.

The insights gained from the data analysis phase are interpreted and applied in practical scenarios to improve health outcomes. We use the findings to tailor personalized healthcare interventions, recommend lifestyle modifications, and develop preventive strategies. Additionally, the analysis results contribute to the development of predictive models for early detection of health issues and the promotion of overall wellness. 

To ensure the reliability and accuracy of the proposed system, rigorous evaluation and validation processes are essential. We compare the data collected from the wearable device with established medical standards to verify its accuracy and consistency. Additionally, we conduct user surveys to assess the usability and effectiveness of the system from the participants' perspective. By systematically evaluating and validating the system, we can confidently deploy it in real-world settings and make informed decisions based on the insights derived from the data analysis.

## Wearable device 

The research paper introduces a novel approach to utilizing wearable devices for health monitoring and research purposes. Instead of relying on off-the-shelf products, we've developed a custom-made wearable device tailored specifically for our studies. 
This device incorporates a GSM module, allowing seamless communication over GSM networks for data transfer. This enables efficient and reliable transfer of collected data to a central repository or analysis model, regardless of the participant's location.
   
![image](https://github.com/user-attachments/assets/45e3974e-297d-4d3a-911e-7226ddaa14ae)
![image](https://github.com/user-attachments/assets/7ac908c7-0b64-45ae-bf72-548ccbbbe7d7)

Figure 2: Custom wearable device design

Participants in our study wear this device continuously for a specified period, allowing us to gather comprehensive data about their health and daily activities. The use of the custom-made device with a GSM module ensures that data can be securely transmitted in real-time, enhancing the timeliness and accuracy of our research findings.

Using advanced data analysis techniques, we examine the collected data to identify patterns, correlations, and trends related to individual well-being. Our approach emphasizes personalized healthcare interventions and lifestyle recommendations based on the insights gained from the analysis.

By leveraging this custom-made wearable device with a GSM module, we aim to advance the field of health monitoring and research, paving the way for more tailored and effective interventions to improve overall wellness.

## Model Training

The research employs a Standard Feed-forward Neural Network, a type of artificial intelligence model, to analyze SWELL (Sleep, Wellness, Exercise, Lifestyle, and Location) data collected from our custom wearable device. This neural network consists of three layers: an Input Layer with 34 neurons utilizing ReLU activation, a Hidden Layer with 10 neurons also using ReLU activation, and an Output Layer with 3 neurons employing softmax activation.

![image](https://github.com/user-attachments/assets/f85eb883-2a46-4ff9-ba4b-43483c5f74c3)
![image](https://github.com/user-attachments/assets/6b372fcc-6c49-4626-9053-d950474d01af)
 
Figure 3: Model Training, Accuracy and Loss Graph

This neural network architecture enables us to process and interpret the complex SWELL data efficiently. By feeding the data through multiple layers of neurons, the network can identify patterns and correlations within the dataset. The ReLU activation function ensures that the network can handle nonlinear relationships in the data, while the softmax activation function in the output layer produces probability distributions over the possible outcomes.

![image](https://github.com/user-attachments/assets/b56adf73-160e-4764-8e58-612555034b91)

Figure 4: Model Classification and Accuracy

One significant benefit of using this neural network model is its ability to achieve high accuracy in data analysis. In our research, the neural network has demonstrated an impressive accuracy rate of 96.35%. This level of accuracy indicates the effectiveness of the model in accurately classifying and interpreting the SWELL data, providing valuable insights into individuals' health and lifestyle patterns.

Overall, the Standard Feed-forward Neural Network serves as a powerful tool for analyzing SWELL data from wearable devices. Its ability to handle complex data and produce accurate results makes it instrumental in extracting meaningful insights that can inform personalized healthcare interventions and wellness strategies.
