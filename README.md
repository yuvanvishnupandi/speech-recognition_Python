# Python Speech Recognition


---

## 🧠 Features

This project provides clear, easy-to-use examples for:

- 🎙️ **Real-time Recognition**: Transcribe audio directly from a microphone.  
- 🎧 **Audio File Recognition**: Convert speech from short audio files into text.  
- 📂 **Long Audio File Processing**: Transcribe long audio files by intelligently splitting them into smaller chunks.

---

## ⚙️ Getting Started

Follow these instructions to get the project running on your local machine.

### 🔧 Prerequisites

Make sure you have **Python 3** and **pip** installed on your system.

### 🧩 Installation

1. **Clone the repository to your local machine:**

    ```bash
    git clone https://github.com/yuvanvishnupandi/speech-recognition_Python.git
    ```

2. **Navigate into the project directory:**

    ```bash
    cd speech-recognition_Python
    ```

3. **Install the required Python packages:**

    ```bash
    pip install pydub PyAudio SpeechRecognition
    ```

    > **Note:** Linux users may need to install `portaudio` separately:  
    > `sudo apt-get install libasound-dev portaudio19-dev libportaudio2 libportaudiocpp0`

---

## 🚀 How to Use

Each script is designed to be run directly from your terminal.

### 1️⃣ Recognize Speech from a Microphone

The `app.py` script listens to your microphone for a few seconds, captures the audio, and prints the transcribed text.

**Run the script:**

```bash
python app.py
