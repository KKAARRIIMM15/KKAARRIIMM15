# Hi there, I'm Karim 👋
### i am a developer graduated from AAST department of computer scince as major and software engineering as minor. My passion lies in deep learning, computer vision, Image processing, audio analysis, distributed system

## i've worked on a numper of projects in some areas.

### Hardware Projects
- 🚑 (patient monitoring system)
  How it Works:
  IOT patient data transfers from Arduino remote sensors to Java server using MQTT protocol then Java server alerts trigger if vitals exceed safe limits.

  
- 🚦 Smart Traffic Light System
Use Case: Control and monitor traffic lights in different locations from a cloud-based system.
How it Works:
A Java-based cloud server sends traffic light signals (red, yellow, green) to multiple Raspberry Pi nodes.
The Raspberry Pi (Python-based) receives commands and controls actual traffic lights (LEDs or real traffic lights).
The Pi nodes send feedback (e.g., sensor data, traffic density) back to the cloud via gRPC bidirectional streaming.

### Audio Analysis Projects
- 🎙 Siamese Neural Network for speaker identity by calculating the similarity between the voice entered in the sign-up phase and the voice entered in the login phase then determine whether the two voices is identical or not using TensorFlow
- 📊 Covid cough detection by analyzing the audio signal then classify it using LSTM algorithm
- 😢 Emotion recognition by extracting the spectral features of the audio signal then encode them using multi head transformer then feed the encodings to fully connected layer for final classification using TensorFlow

### Computer Vision Projects
-	🧠 Cancer tumor detection of brain MRI using (YOLOv8) PyTorch
-	👤 Generative Adversarial Network (GAN) to generate faces of non-existent people using TensorFlow
-	💰 Egyptian currency detection to count the total amount of money appearing in the image or video frame by instance segmentation of each banknote paper using (Mask-RCNN) PyTorch
-	🧑👩👩‍🦳 Face gender and age prediction using (CNN) keras

  ### NLP Projects
  -	🚫 Natural Language Processing by reading twitter comments then determine the comments that violate the community guidelines to be deleted using TensorFlow

### Network Programming Projects
-	📶 Video calling between multiple clients using UDP protocol with AES encryption using java
1-	This project focus on synchronizing the video thread and audio thread together to ensure that speech aligns precisely with mouth movements, preventing any delay.
2-	The project also focus on how to serialize the high level data as image frame or audio samples to stream of bytes to be passed over network then deserialize it to its original form when it reaches the destination
-	🔍 Connection between java program and wireshark using pcap4j library for packet processing such as extracting the payload of HTTP or FTP for classifying the malicious packets or blocking any packet came from a specific source IP

### Data Compression Projects
-	🖼️ Implementing unsupervised machine learning algorithms from scratch for image compression such as hierarchy clustering and DBscan clustering

### Web Scraping Projects
•	🍔🍟 Web scraping(Automation) by scanning the meal order from the user then the program automatically visit the three websites (MacDonald’s, Burger King, Hardee’s) then extract the meal and its price from the three websites and then choose the most suitable price among them using java selenium library 

