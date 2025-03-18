<!-- # Audio Analysis

## Objective
- To perform beat tracking
- To estimate the tempo of music file. 
- To understand the music's structure.
- To find rhythmic patterns, melody patterns.
- To perform genre classification
- To discover song's keys and chords.
- To identify the mood of the song.  -->
🎵 Audio Analysis
🎯 Objective
This project aims to analyze audio files to extract meaningful musical insights. The key objectives include:

Beat Tracking – Identifying the beats in a track.
Tempo Estimation – Determining the speed of the music (BPM).
Musical Structure Analysis – Understanding the overall composition.
Pattern Recognition – Detecting rhythmic and melodic patterns.
Genre Classification – Categorizing music based on its features.
Key & Chord Detection – Discovering the song's musical keys and chord progressions.
Mood Identification – Analyzing the emotional tone of the song.

### Step 1: Install the libraries- Librosa, Numpy, Matplotlib
```bash
pip install librosa matplotlib numpy jupyter
```

### Step 2: Convert the audio to a waveform.

### Step 3: Extract the tempo using the in-built method library Librosa. Also extract the beats in the form of frames. 

### Step 4: Convert the beat frames to time. That is the occurence of beats with respect to time.

### Step 5: Here is the result-
<img width="803" alt="image" src="https://github.com/user-attachments/assets/0bf68eac-4bf1-49c3-8f3c-cfbc22453dc1" />

### Step 6: Plotting in different ways starting from the basic plot to making things as clear as possible.
<img width="1066" alt="image" src="https://github.com/user-attachments/assets/c98b8e91-e979-4e8f-9b3c-32ef0e700410" />

<img width="1123" alt="image" src="https://github.com/user-attachments/assets/4bdf3acf-b77c-4928-8943-1c3a58e4562d" />

<img width="662" alt="image" src="https://github.com/user-attachments/assets/b7a8b264-1186-4b69-a77d-1b8896aec9d1" />

### Step 7: Verification- As the tempo given by the library for the music file is 90.67 BPM. It would be a good idea to verify it. There are several ways for example analyse it using different methods like using a different library to achieve the same result or use a tool available to verify it. In some cases we can manually count the beats as well although thats really difficult. I went for the shortest and easiest one. I used multiple tools online to calculate BPM and they all gave similar results.

###### Vocal Remover-
<img width="1393" alt="image" src="https://github.com/user-attachments/assets/0b34d331-23b1-4803-8648-00fc07ca7653" />

###### Voice.ai-
<img width="1006" alt="image" src="https://github.com/user-attachments/assets/078c0b29-b130-4d11-8445-27767072919f" />

### Hence, we can say that the beats per minute are 90.6 in this music track.

