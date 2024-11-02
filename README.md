# Real-Time Visual Assistance for the Visually Impaired

A wearable device leveraging computer vision to assist visually impaired individuals. This system detects objects, reads text, and provides real-time audio feedback, helping users navigate their surroundings independently and safely.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Methodology](#methodology)
- [Tools and Technologies](#tools-and-technologies)
- [Setup and Installation](#setup-and-installation)
- [Future Enhancements](#future-enhancements)
- [Impact](#impact)
- [License](#license)

## Project Overview
The **Real-Time Visual Assistance for the Visually Impaired** project aims to create a wearable device that uses object detection, text recognition, and audio feedback to empower visually impaired individuals. By identifying obstacles, reading signs, and recognizing important objects, the device provides crucial information to help users navigate their environment confidently.

## Features
- **Object Detection**: Detects and identifies common obstacles, objects, and landmarks in real-time.
- **Text Recognition**: Reads and interprets text from signs, labels, and documents using Optical Character Recognition (OCR).
- **Audio Feedback**: Provides intuitive and real-time audio feedback to alert users about their surroundings and read out recognized text.

## Methodology
1. **Data Collection**:
   - Collect a diverse dataset of labeled images covering objects, street signs, and various text samples.
   - Ensure the dataset includes different environments and lighting conditions to improve model robustness.

2. **Model Development**:
   - **Object Detection**: Utilize models like YOLO or Faster R-CNN to detect objects and obstacles, providing spatial awareness.
   - **Text Recognition**: Use Tesseract OCR to extract text from captured images and translate it to audio.
   - **Audio Feedback**: Convert identified objects and text into audio output, informing users in real-time about their surroundings.

3. **User Interface**:
   - Design a simple, user-friendly interface to deliver audio cues and instructions.
   - Incorporate haptic feedback for additional tactile information about obstacle proximity.

4. **Testing and Evaluation**:
   - Conduct field testing with visually impaired individuals for real-world feedback.
   - Adjust and refine the model and interface based on user experience and accuracy metrics.

## Tools and Technologies
- **Programming Language**: Python
- **Computer Vision Libraries**: OpenCV, TensorFlow, Keras
- **OCR Library**: Tesseract OCR
- **Hardware**: Raspberry Pi or similar microcontroller, camera module, headphones or speakers for audio output

## Setup and Installation

1. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
2. **Connect hardware**: Attach a compatible camera module and audio output device (e.g., headphones or speaker) to the Raspberry Pi or microcontroller.

3. **Run the application**:
   ```bash
   python main.py
## Future Enhancements

- **GPS Integration**: Add GPS navigation to guide users through larger spaces and unfamiliar areas.
- **Improved Accuracy**: Incorporate more sophisticated models or larger datasets to enhance object detection and OCR reliability.
- **Multilingual Support**: Expand the OCR and audio output to support multiple languages.
- **Personalized Settings**: Allow users to customize audio feedback for specific objects or text.

## Impact

This project uses computer vision to make everyday tasks more accessible for visually impaired individuals. With real-time audio feedback, users can navigate public spaces, read signs, and identify obstacles independently. This system promotes inclusivity, safety, and confidence, helping users interact seamlessly with their surroundings.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
