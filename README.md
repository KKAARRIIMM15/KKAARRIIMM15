# Hi there, I'm Karim 👋
### i am a developer graduated from AAST department of computer scince as major and software engineering as minor. My passion lies in deep learning, computer vision, Image processing, audio analysis, distributed system

## i've worked on a numper of projects in some areas.

### Hardware projects
- 🚑 (patient monitoring system)
  How it Works:
  IOT patient data transfer from Arduino remote sensors to Java server using MQTT protocol then Java server alerts trigger if vitals exceed safe limits.

  
- 🚦 Smart Traffic Light System
Use Case: Control and monitor traffic lights in different locations from a cloud-based system.

How it Works:

A Java-based cloud server sends traffic light signals (red, yellow, green) to multiple Raspberry Pi nodes.
The Raspberry Pi (Python-based) receives commands and controls actual traffic lights (LEDs or real traffic lights).
The Pi nodes send feedback (e.g., sensor data, traffic density) back to the cloud via gRPC bidirectional streaming.

### Audio Analysis projects
- •	Siamese Neural Network for speaker identity by calculating the similarity between the voice entered in the sign-up phase and the voice entered in the login phase then determine whether the two voices is identical or not using TensorFlow
- •	Covid cough detection by analyzing the audio signal then classify it using LSTM algorithm
- •	Emotion recognition by extracting the spectral features of the audio signal then encode them using multi head transformer then feed the encodings to fully connected layer for final classification using TensorFlow
