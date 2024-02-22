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

#### Original Samples
<p>
  <audio controls="controls">
    <source type="audio/wav" src="audio/1_60.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/1_70.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/1_105.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/1_175.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/2_627.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/2_626.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/2_623.wav"></source>
  </audio>
</p>

#### Denoise by voicefixer
<p>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/voicefixer_mode0/1_60.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/voicefixer_mode0/1_70.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/voicefixer_mode0/1_105.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/voicefixer_mode0/1_175.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/voicefixer_mode0/2_627.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/voicefixer_mode0/2_626.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/voicefixer_mode0/2_623.wav"></source>
  </audio>
</p>

#### Denoise by Davinci Resolve
<p>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/DavinciResolve/1_60.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/DavinciResolve/1_70.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/DavinciResolve/1_105.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/DavinciResolve/1_175.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/DavinciResolve/2_627.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/DavinciResolve/2_626.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/DavinciResolve/2_623.wav"></source>
  </audio>
</p>


### Finetuned FS2(MUStARD, w/o denosing)

### Finetuned FS2(MUStARD, w voicefixer)
<p>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_mode0_mustard/1_60_2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_mode0_mustard/1_70_2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_mode0_mustard/1_105_2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_mode0_mustard/1_175_2.wav"></source>
  </audio>
</p>

### Finetuned Fastspeech2(MUStARD, w DavinciResolve)
<p>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_davinci_mustard/1_60_2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_davinci_mustard/1_70_2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_davinci_mustard/1_105_2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_davinci_mustard/1_175_2.wav"></source>
  </audio>
</p>

## Without sarcasm labels

### Pre-trained on Friends TV

### Pre-trained on Friends TV(denoised by voicerfixer)

### Pre-trained on Friends TV(denoised by Davinci Resolve)

## With sarcasm labels

---
