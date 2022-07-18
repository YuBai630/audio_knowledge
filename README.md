# audio_knowledge
记录音频相关知识
### librosa相关
```python
mel_spectrogram = librosa.feature.melspectrogram(y=wavsignal, sr=16000, n_mels=256, n_fft=1024, win_length=400, hop_length=160)
```
采样率是16000，表示1s内采样16000次，那么通常一帧为25ms，即一帧采样 16000 * 0.025 = 400 个点，所以 `win_lehgth` = 400，`hop_lenght`=160
