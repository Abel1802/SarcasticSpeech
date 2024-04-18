# SarcasticSpeech: Text To Speech For Sarcasm in Low-Resource Scenarios

## Abstract
Sarcastic speech synthesis, the ability to generate speech that conveys sarcasm, can have several significant implications in various contexts. This study presents a pioneering attempt to apply transfer learning techniques from a diverse speech style dataset to the challenging domain of sarcastic speech synthesis. The limited availability of specific sarcastic speech data poses significant challenges in capturing the expressive nature of sarcasm. By leveraging transfer learning, a pre-trained model is fine-tuned using a dataset encompassing various speech styles, including sarcastic speech. The experimental results indicate moderate performance improvements in sarcastic speech synthesis through transfer learning. Moving forward, future work will explore the application of multi-model approaches to enhance sarcastic speech synthesis, aiming to further enhance the expressive capabilities and naturalness of generated sarcastic speech.

## Original Speaker Samples
<style>
	audio {
		width: 200px;
	}
	td {
		text-align: center;
	}
</style>

<table>
  <tr>
    <td style="white-space:nowrap;">
		<audio controls><source src="audio/1_60.wav" ></audio>
	</td>
	<td style="white-space:nowrap;">
		<audio controls><source src="audio/1_70.wav" ></audio>
	</td>
	<td style="white-space:nowrap;">
		<audio controls><source src="audio/1_105.wav" ></audio>
	</td>
  </tr>
</table>

## Denoised Speaker Samples
<table>
  <tr>
    <td style="white-space:nowrap;">
		<audio controls><source src="audio/1_60_u.wav" ></audio>
	</td>
	<td style="white-space:nowrap;">
		<audio controls><source src="audio/1_70_u.wav" ></audio>
	</td>
	<td style="white-space:nowrap;">
		<audio controls><source src="audio/1_105_u.wav" ></audio>
	</td>
  </tr>
</table>

## Finetuned FastSpeech2 on Multi-Speakers
<table>
  <tr>
    <td style="white-space:nowrap;">
		<audio controls><source src="audio/1_60_2.wav" ></audio>
	</td>
	<td style="white-space:nowrap;">
		<audio controls><source src="audio/1_70_2.wav" ></audio>
	</td>
	<td style="white-space:nowrap;">
		<audio controls><source src="audio/1_105_2.wav" ></audio>
	</td>
  </tr>
</table>

---
## Multi-modal for SarcasticSpeech(To be continued...)
