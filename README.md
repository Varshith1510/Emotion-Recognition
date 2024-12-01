# Emotion Recognition from Audio Signals

## Objective

This project aims to develop a system for recognizing emotions from audio signals. The primary goal is to analyze and classify audio clips into various emotional categories, such as "happy," "sad," "angry," and others.

## Steps Taken

### Data Acquisition

- **TESS Dataset:** Downloaded the TESS (Toronto Emotional Speech Set) dataset from Kaggle, which includes audio clips labeled with emotions such as "happy," "sad," "angry," and more.

### Data Preprocessing

- **Data Organization:** Constructed a DataFrame to organize audio file paths and their corresponding emotion labels.
- **Visualization:** Visualized the emotion distribution in the dataset using count plots to gain insights into the balance of emotions.

### Feature Extraction & Exploration

- **Waveform and Spectrogram Visualization:** Developed custom functions to visualize audio waveforms and spectrograms. These visualizations provided valuable insights into how different emotions are represented in speech.

### Modeling with LSTM

- **LSTM Model:** Utilized an LSTM (Long Short-Term Memory) model to analyze sequential audio data. This model captures temporal dependencies crucial for accurate emotion recognition.
- **Training and Fine-Tuning:** Trained and fine-tuned the LSTM model to predict emotions from new audio inputs, achieving impressive accuracy.
