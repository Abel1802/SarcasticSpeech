## Abstract
Sarcastic speech synthesis, the ability to generate speech that conveys sarcasm, can have several significant implications in various contexts. This study presents a pioneering attempt to apply transfer learning techniques from a diverse speech style dataset to the challenging domain of sarcastic speech synthesis. The limited availability of specific sarcastic speech data poses significant challenges in capturing the expressive nature of sarcasm. By leveraging transfer learning, a pre-trained model is fine-tuned using a dataset encompassing various speech styles, including sarcastic speech. The experimental results indicate moderate performance improvements in sarcastic speech synthesis through transfer learning. Moving forward, future work will explore the application of multi-model approaches to enhance sarcastic speech synthesis, aiming to further enhance the expressive capabilities and naturalness of generated sarcastic speech.

## Original Speaker Samples new
<table style="width:100%">
  <tr>
    <td>
		<audio controls><source src="audio/1_60.wav" ></audio>
	</td>
	<td>
		<audio controls><source src="audio/1_60.wav" ></audio>
	</td>
	<td>
		<audio controls><source src="audio/1_60.wav" ></audio>
	</td>
  </tr>
</table>

## Original Speaker Samples
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

## Ground Truth for HiFi-GAN
<audio controls="controls">
    <source type="audio/wav" src="audio/1_60_generated_pre.wav"></source>
</audio>

<audio controls="controls">
    <source type="audio/wav" src="audio/2_2_generated_pre.wav"></source>
</audio>

<audio controls="controls">
    <source type="audio/wav" src="audio/2_3_generated_pre.wav"></source>
</audio>

## Ground Truth For Finetuned HiFi-GAN
<audio controls="controls">
    <source type="audio/wav" src="audio/1_60_generated_ft.wav"></source>
</audio>

<audio controls="controls">
    <source type="audio/wav" src="audio/2_2_generated_ft.wav"></source>
</audio>

<audio controls="controls">
    <source type="audio/wav" src="audio/2_3_generated_ft.wav"></source>
</audio>

## Finetuned Fastspeech2 & Finetuned HiFi-GAN
### Single-speaker
<audio controls="controls">
    <source type="audio/wav" src="audio/1_467_2.wav"></source>
</audio>

<audio controls="controls">
    <source type="audio/wav" src="audio/1_507_2.wav"></source>
</audio>

### Multi-Speaker
<audio controls="controls">
    <source type="audio/wav" src="audio/1_467_2_multi.wav"></source>
</audio>

<audio controls="controls">
    <source type="audio/wav" src="audio/1_507_2_multi.wav"></source>
</audio>

<audio controls="controls">
    <source type="audio/wav" src="audio/1_6427_2_multi.wav"></source>
</audio>






---
