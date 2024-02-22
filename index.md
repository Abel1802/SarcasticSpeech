## Experiment results for sarcastic TTS

## Pipleline for sarcastic speech synthesis
![An overview of SarcasticTTS](image/pipeline_sarcasticTTS.png)

### Update by Feb 22
- Denoised effect
    - voicefixer
    - Davinci Resolve
- Fine-tuned FastSpeech 2 on MUStARD
    - w/o denoise
    - w/ voicefixer
    - w/ Davinci Resolve
- Pre-trained FS2 on Friends
    - w/o denoise
    - w/ voicefixer

### Original Samples
<p>
  <audio controls="controls">
    <source type="audio/wav" src="audio/1_60.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/1_80.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/1_70.wav"></source>
  </audio>
</p>

### Denoise by voicefixer

### Denoise by Davinci Resolve

### Finetuned Fastspeech2(on MUStARD)

### Finetuned Fastspeech2(on denoised MUStARD, voicefixer)

### Finetuned Fastspeech2(on denoised MUStARD, Davinci Resolve)

## Without sarcasm labels

### Pre-trained on Friends TV

### Pre-trained on Friends TV(denoised by voicerfixer)

### Pre-trained on Friends TV(denoised by Davinci Resolve)

## With sarcasm labels

---
