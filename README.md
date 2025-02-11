# 🎵 Music Chord Extraction & Analysis using Python  

## 📌 Overview  
This project extracts **musical notes and chords** from an **MP3 file**, converts them into **Solfège notation**, and determines the **chords per second** using machine learning and music theory principles.  

---

## 📌 Features  
- ✅ **Convert MP3 to WAV** – Uses `pydub` to convert audio files for analysis.  
- ✅ **Extract Musical Notes** – Uses `librosa` and `pretty_midi` to detect pitch and melody.  
- ✅ **Convert to Solfège Notation** – Maps Western musical notes to Indian Swaras (`Sa, Re, Ga...`).  
- ✅ **Determine Chords Per Second** – Groups extracted notes into meaningful chords.  
- ✅ **Data Export & Analysis** – Converts results into a Pandas DataFrame for further analysis.  

---

## 🔧 Installation  

### 📦 Install Required Libraries  
Run the following command to install dependencies:  
```bash
pip install pydub pretty_midi librosa numpy matplotlib pandas
