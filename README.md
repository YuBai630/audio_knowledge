# audio_knowledge
记录音频相关知识
### librosa相关
```python
mel_spectrogram = librosa.feature.melspectrogram(y=wavsignal, sr=16000, n_mels=256, n_fft=1024, win_length=400, hop_length=160)
```
