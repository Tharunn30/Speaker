

---

# 🗣️ Speaker Diarization in Multilingual Scenarios  
![License](https://img.shields.io/github/license/Tharunn30/Speaker-Diarization-In-Multilingual-Scenarios?style=flat-square)  
![Contributions](https://img.shields.io/badge/Contributions-Welcome-brightgreen?style=flat-square)  
[![Stars](https://img.shields.io/github/stars/Tharunn30/Speaker-Diarization-In-Multilingual-Scenarios?style=social)](https://github.com/Tharunn30/Speaker-Diarization-In-Multilingual-Scenarios/stargazers)

**Speaker Diarization** refers to the process of partitioning an audio stream into homogeneous segments according to the speaker's identity. This project focuses on performing diarization in **multilingual scenarios**, where participants may switch between multiple languages during a conversation.

---

## 🔥 Key Features  
- **Multilingual Support:** Efficiently handles scenarios where speakers switch languages mid-conversation.  
- **Speaker Segmentation:** Identifies and separates speakers within audio streams.  
- **Language-Aware Diarization:** Improves accuracy by taking into account the language transitions.  
- **Pre-trained Models:** Leverages state-of-the-art models from **pyannote-audio** for diarization.  
- **Scalable Setup:** Easily handles long conversations with overlapping speakers.

---

## 📋 Table of Contents  
- [How It Works](#-how-it-works)  
- [Installation](#-installation)  
- [Usage](#-usage)  
- [Technologies Used](#-technologies-used)  
- [Contributing](#-contributing)  
- [License](#-license)

---

## ⚙️ How It Works  
1. **Audio Input:** Users provide an audio file (e.g., a meeting or podcast) as input.  
2. **Speaker Segmentation:** The audio is split into segments, each corresponding to a different speaker.  
3. **Language Detection (Optional):** Detects language changes to improve segmentation.  
4. **Diarization Output:** The system outputs timestamps of speaker segments, identifying "who spoke when" and in which language.

---

## 🛠️ Installation  

1. **Clone the Repository:**  
   ```bash
   git clone https://github.com/Tharunn30/Speaker-Diarization-In-Multilingual-Scenarios.git
   cd Speaker-Diarization-In-Multilingual-Scenarios
   ```

2. **Set Up Virtual Environment (Optional):**  
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies:**  
   Use the following command to install required packages:  
   ```bash
   pip install -r requirements.txt
   ```

4. **Download Pre-trained Models:**  
   Install **pyannote-audio** models by following [pyannote installation instructions](https://github.com/pyannote/pyannote-audio).

---

## 🚀 Usage  

1. **Prepare Input Audio:** Ensure the audio file is in **WAV** format.  
2. **Run the Diarization Script:**  
   ```bash
   python diarization.py --audio_file <path_to_audio_file>
   ```

3. **View Output:** The output will display speaker segments and timestamps. Optionally, results can be saved as a text file or JSON for further analysis.

Example output:  
```
Speaker 1: 00:00 - 00:25  
Speaker 2: 00:25 - 01:10  
Speaker 1: 01:10 - 01:45  
```

---

## 💻 Technologies Used  
- **Python**  
- **Pyannote-audio** for diarization models  
- **Librosa** for audio processing  
- **Scikit-learn** for clustering algorithms  
- **Pandas/Numpy** for data handling

---

## 🤝 Contributing  
Contributions are welcome! If you'd like to improve this project, follow these steps:  
1. Fork the repository.  
2. Create a new branch:  
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes:  
   ```bash
   git commit -m "Add new feature"
   ```
4. Push your changes:  
   ```bash
   git push origin feature/your-feature
   ```
5. Open a pull request!

---

## 📄 License  
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🌟 Support  
If you found this project helpful, please give it a ⭐ on [GitHub](https://github.com/Tharunn30/Speaker-Diarization-In-Multilingual-Scenarios)!

---

