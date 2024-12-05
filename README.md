# Object Detection with Audio Narration

![Platform](https://img.shields.io/badge/Platform-Python-green.svg)  
![Framework](https://img.shields.io/badge/Framework-Gradio-blue.svg)  
![Status](https://img.shields.io/badge/Status-In_Development-yellow.svg)

### A Python-based application that combines object detection and text-to-speech to generate annotated images and audio descriptions for detected objects in input images.

---

## Table of Contents
- About  
- Features  
- Screenshots  
- Tech Stack  
- Getting Started  
- Installation  
- Usage  
- Project Structure  
- Contact  

---

## About  
This project uses machine learning pipelines to perform object detection on images and generates audio descriptions of the detected objects. It integrates the **DETR object-detection model** and **VITS text-to-speech** model to provide visual and auditory feedback for enhanced accessibility.

---

## Features  
- **Object Detection**: Identifies objects in images and highlights them with bounding boxes.  
- **Text-to-Speech Narration**: Converts detected objects into natural language and narrates the content.  
- **Interactive Interface**: Uses Gradio to provide an easy-to-use interface for image input and result visualization.  
- **Customizable Font**: Allows for custom font selection when drawing bounding boxes and annotations.

---

## Screenshots  
| Input Image | Processed Image with Bounding Boxes |  
|-------------|------------------------------------|  
| _Include screenshots here_ |

---

## Tech Stack  
- **Python**: Programming language for the application.  
- **Gradio**: Framework for creating a user-friendly web interface.  
- **Transformers**: Pre-trained models for object detection and text-to-speech.  
- **PIL**: Used for image processing and annotation.  
- **Scipy**: Handles audio file creation and saving.

---

## Getting Started  

### Prerequisites  
- Python 3.8 or above.  
- Git.  

---

## Installation  

1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/YourUsername/ObjectDetectionAudioNarration
   ```  

2. **Navigate to the Project Directory**:  
   ```bash
   cd ObjectDetectionAudioNarration
   ```  

3. **Install Dependencies**:  
   ```bash
   pip install -r requirements.txt
   ```  

4. **Download Required Models**:  
   The `transformers` library will automatically download the required models during runtime. Ensure your internet connection is active.

---

## Usage  

1. **Run the Application**:  
   ```bash
   python app.py
   ```  

2. **Use the Web Interface**:  
   - Upload an image in the provided Gradio interface.  
   - View the processed image with bounding boxes and listen to the generated audio.  

---

## Project Structure  
- **app.py**: Main application script containing the Gradio interface and function definitions.  
- **requirements.txt**: List of required Python packages.  
- **models/**: Pre-trained models for object detection and text-to-speech (auto-downloaded).  
- **utils/**: Utility functions for image annotation and audio generation.  

---

## Contact  

- **Developer**: Subhangee  
- **Email**: aradhya81702002@example.com  
- **GitHub**: [GitHub Profile](https://github.com/SubhangeeG)  
- **LinkedIn**: [LinkedIn Profile](https://www.linkedin.com/in/subhangee-rai-3103b2257)

---
