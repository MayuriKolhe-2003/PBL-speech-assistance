# Speech Assistance for Blind People

Speech Assistance for Blind People is a Python application that leverages the YOLO (You Only Look Once) object detection model and OpenCV to assist visually impaired individuals in navigating their surroundings. The application detects and recognizes objects in real-time and provides spoken descriptions to the user through a text-to-speech interface.

## Features

- **Real-time Object Detection:** The application uses YOLO to detect and recognize objects in the user's environment.
- **Text-to-Speech (TTS) Integration:** It provides audible descriptions of detected objects using TTS.
- **User-Friendly Interface:** Designed with simplicity in mind to ensure ease of use for visually impaired individuals.
- **Customizable Voice Output:** Users can configure the TTS voice and speech rate to suit their preferences.
- **Object Recognition:** In addition to detection, the application recognizes and identifies objects when possible.
- **Detect Humans:** Can spell the name of the person who is standing in front of you.
- **Voice Assistant:** Result is assisted to person through audio output.

# Steps
<ol>
  <li>Run the 01_face_dataset.py</li>
  - Add the unique id in the terminal(for ex: 1,2,3,...).<br>
  <li>Run the 02_face_training.py</li>
  - The faces generated in the dataset folder will be trained.<br>
  <li>Run 03_face_recognition.py</li>
  - add your name in the list (names = [none,"Shreyas"]) depending on the number of faces trained in the model.<br>
  - run the file, following output will be displayed on the screen.<br>
</ol>





# Output Screen

![Animated GIF-downsized_large](https://user-images.githubusercontent.com/42066122/115507607-f770e880-a299-11eb-9a98-2e481024c16e.gif)


