## Abstract
Creating a naturalistic speech stimulus continuum (i.e., a series of stimuli equally spaced along a specific acoustic dimension between two given categories) is an indispensable component in categorical perception studies. A common method is to manually modify the key acoustic parameter of speech sounds, yet the generation process is time-consuming and the quality of synthetic speech is still unsatisfying. In this paper, we adopt an adversarial learning framework to separate the specific acoustic feature from other contents in speech signals and achieve controllable speech stimulus generation by sampling from the latent space of the key acoustic feature. Specifically, in a case study of tone continuum generation, an autoencoder was trained first to learn pitch-independent latent representations and disentangled representation of pitch separately using another auxiliary pitch predictor to regularize the latent representation. Then several latent representations between the two reference pitch representations of the continuum endpoints were sampled equidistantly. The decoder merged the pitch-independent content and a sampled latent representation to recompose an intermediate speech stimulus. Experiments on stimulus generation of tone continuum and formant continuum validate the effectiveness of our proposed method in both objective and subjective evaluations.


## Original Speaker Samples
<p>
  <audio controls="controls">
    <source type="audio/wav" src="audio/1_60.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/1_80.wav"></source>
  </audio>
</p>

## Ground Truth for HiFi-GAN

## Ground Truth For Finetuned HiFi-GAN

## Finetuned Fastspeech2 & Finetuned HiFi-GAN






---
