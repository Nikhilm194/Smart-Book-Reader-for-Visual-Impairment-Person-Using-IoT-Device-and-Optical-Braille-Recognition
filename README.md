# Smart-Book-Reader-for-Visual-Impairment-Person-Using-IoT-Device-and-Optical-Braille-Recognition
## Introduction
The ability to see is a profound gift, yet many visually impaired individuals face challenges in accessing written content. Braille, a widely used tactile reading and writing system, enables the visually impaired to learn effectively, but its adoption can be limited due to learning difficulties. The integration of IoT devices and deep learning has paved the way for innovative assistive technologies, such as a Smart Book Reader that converts Braille to speech. Deep learning, particularly Optical Braille Recognition(OBR) , excels in recognizing complex patterns and automating Braille script identification, offering accurate and user-friendly solutions. This transformative fusion enhances accessibility and empowers visually impaired individuals with new tools for learning and engagement.
![image alt](https://github.com/Nikhilm194/Smart-Book-Reader-for-Visual-Impairment-Person-Using-IoT-Device-and-Optical-Braille-Recognition/blob/main/Screenshot%202025-01-08%20192256.png)
## System Architecture 
The system architecture comprises essential components: a Power Supply providing 5V/2.5A to the Raspberry Pi, the core Raspberry Pi SBC with ARM CPU and GPU for processing and visuals, and an SD Card for OS, applications, and data storage. Optional peripherals include a Webcam for image/video capture, a Keyboard for user input, and Bluetooth for wireless voice output through speakers or headsets.
## Workflow
The workflow involves converting Braille text into voice output using IoT and machine learning. Images captured by a camera module undergo Pre-Processing, where irrelevant content is cropped, and the image is resized. Image Segmentation using K-Means clustering isolates the Braille script from other elements. Through Feature Extraction, essential patterns are identified for analysis. The OBR Module translates Braille dot patterns into text, which is then converted to voice using APIs. The process leverages OCR with the Tesseract library to recognize text and OpenCV to identify objects, enabling seamless text-to-speech conversion for visually impaired users.
## Tools Used 
3.3.1 Hardware Requirements:

Web Camera: Captures images for processing.

Raspberry Pi: Core processing unit for the system.

Bluetooth: Enables wireless audio output.

3.3.2 Software Requirements:

Python: Programming language for implementation.

OpenCV: Library for image processing.

Flask: Framework for web-based interaction.
## Conclusion
The Smart Book Reader is a transformative innovation for visually impaired individuals, eliminating the need to learn Braille and offering an accessible and efficient reading experience. By converting English text to audio through advanced image processing and deep learning, it ensures precision and reliability in text-to-audio conversion via the OBR module. This device fosters inclusivity and empowers visually impaired users to access knowledge with ease and independence.
## Future Scope
Expanding the system to support multiple languages.

Improving hardware to enhance real-time accuracy and usability
## Certifcate
![image alt](https://github.com/Nikhilm194/Smart-Book-Reader-for-Visual-Impairment-Person-Using-IoT-Device-and-Optical-Braille-Recognition/blob/main/IJSREM.jpg)
