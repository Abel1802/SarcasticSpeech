## Experiment results for sarcastic TTS

## An overview of sarcastic speech synthesis
![An overview of SarcasticTTS](image/pipeline_sarcasticTTS.png)

### Update by Feb 23
- Denoised effect
    - [voicefixer](https://github.com/haoheliu/voicefixer)
    - [Davinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve/whatsnew)
    - Adobe
- Fine-tuned FastSpeech 2 on MUStARD(MUStARD++)
    - w/o denoise
    - w/ voicefixer
    - w/ Davinci Resolve
    - w/ Adobe
- Pre-trained FS2 on Friends
    - w/o denoise
    - w/ voicefixer


## Part 1. Denoised effect

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

#### Denoised by Adobe(from Xiyuan)
<p>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/mmsd_adobe/1_60.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/mmsd_adobe/1_70.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/mmsd_adobe/1_105.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/mmsd_adobe/1_175.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/mmsd_adobe/2_627.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/mmsd_adobe/2_626.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/mmsd_adobe/2_623.wav"></source>
  </audio>
</p>


## Part 2. Fined-tuned FS2 on MUStARD(MUSTARD++)

#### Finetuned FS2(MUStARD, w/o denoise)
<p>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_wo_denoising_mustard/1_60_2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_wo_denoising_mustard/1_70_2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_wo_denoising_mustard/1_105_2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_wo_denoising_mustard/1_175_2.wav"></source>
  </audio>
</p>

#### Finetuned FS2(MUStARD, w voicefixer)
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

#### Finetuned F2(MUStARD, w DavinciResolve)
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

#### Finetuned FS2(MUSTARD++, w Adobe)
<p>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_adobe_mmsd_pp/1_60_2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_adobe_mmsd_pp/1_70_2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_adobe_mmsd_pp/1_105_2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_adobe_mmsd_pp/1_175_2.wav"></source>
  </audio>
</p>

#### <u>Finetuned FS2(MUSTARD++(sarcastic), w Adobe)</u>
<p>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_adobe_mmsd_pp_1/1_60_2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_adobe_mmsd_pp_1/1_70_2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_adobe_mmsd_pp_1/1_105_2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_adobe_mmsd_pp_1/1_175_2.wav"></source>
  </audio>
</p>

#### <u>Finetuned FS2(MUSTARD++(non-sarcastic), w Adobe)</u>
<p>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_adobe_mmsd_pp_0/1_60_2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_adobe_mmsd_pp_0/1_70_2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_adobe_mmsd_pp_0/1_105_2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_adobe_mmsd_pp_0/1_175_2.wav"></source>
  </audio>
</p>

#### Pre-trained FS2(LibriTTS)
<p>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_libritts_800000/1_60_2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_libritts_800000/1_70_2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_libritts_800000/1_105_2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_libritts_800000/1_175_2.wav"></source>
  </audio>
</p>

## Part 3. Friends without sarcasm labels

| Spkear   | Amount |
|----------|--------|
| Chandler | 2566   |
| Joey     | 3018   |
| Monica   | 2598   |
| Phoebe   | 2642   |
| Rachel   | 2870   |
| Ross     | 2917   |
| Total    | 16611  |

#### Pre-trained on Friends TV(w/o denoise)
On test set (from back-translated text)
<p>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_wo_denoising_friends/1_60_2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_wo_denoising_friends/1_70_2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_wo_denoising_friends/1_105_2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_wo_denoising_friends/1_175_2.wav"></source>
  </audio>
</p>
On validation set(512)
<p>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_wo_denoising_friends/dia0_utt4.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_wo_denoising_friends/dia1_utt0.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_wo_denoising_friends/dia1_utt2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_wo_denoising_friends/dia4_utt3.wav"></source>
  </audio>
</p>

#### Pre-trained on Friends TV(denoised by voicerfixer)
On test set (from back-translated text, spk: Chandler)
<p>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_mode0_friends/1_60_2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_mode0_friends/1_70_2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_mode0_friends/1_105_2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_mode0_friends/1_175_2.wav"></source>
  </audio>
</p>
On test set (from back-translated text, spk: Rachel)
<p>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_mode0_friends/1_60_2_rachel.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_mode0_friends/1_70_2_rachel.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_mode0_friends/1_105_2_rachel.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_mode0_friends/1_175_2_rachel.wav"></source>
  </audio>
</p>
On validation set(512)
<p>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_mode0_friends/dia0_utt4.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_mode0_friends/dia1_utt0.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_mode0_friends/dia1_utt2.wav"></source>
  </audio>
  <audio controls="controls">
    <source type="audio/wav" src="audio/Feb-22/fs2_w_mode0_friends/dia4_utt3.wav"></source>
  </audio>
</p>


## Friends with sarcasm labels(update on May 10)

| <center> Methods </center> | <center> example1(non-sarcastic) </center>| <center> Example1 (sarcastic) </center> | <center> Example2(non-sarcastic)</center> | Example2(sarcastic) |
| -------------------- | ---------------------- | ------------------------- | -------------------------- |
| Fine-tuned FS2 | <audio src="audio/May-10/ft/1_60_0.wav" controls preload><audio> | <audio src="audio/May-10/ft/1_60_1.wav" controls preload><audio> | <audio src="audio/May-10/ft/1_70_0.wav" controls preload><audio> | <audio src="audio/May-10/ft/1_70_1.wav" controls preload><audio> |
| FS2 + Sarcasm Label| <audio src="audio/May-10/label/1_60_0.wav" controls preload><audio> | <audio src="audio/May-10/label/1_60_1.wav" controls preload><audio> | <audio src="audio/May-10/label/1_70_0.wav" controls preload><audio> | <audio src="audio/May-10/label/1_70_1.wav" controls preload><audio> |
| FS2 + ReferenceEncoder | <audio src="audio/May-10/reference/1_60_2.wav" controls preload><audio> | <audio src="audio/May-10/reference/1_60_20.wav" controls preload><audio> | <audio src="audio/May-10/reference/1_70_2.wav" controls preload><audio> | <audio src="audio/May-10/reference/1_70_20.wav" controls preload><audio> |


## MUSTARD\_Plus\_Plus in different sarcastic & emotional types(update on May 24)

| <center> Methods </center> | <center> example1 </center>| <center> Example2 </center>|
| -------------------- | ---------------------- |
Fine-tuned FS2(PRO) | <audio src="audio/May-24/fs2-pro/1_60_1.wav" controls preload><audio> | <audio src="audio/May-24/fs2-pro/1_70_1.wav" controls preload><audio> |
Fine-tuned FS2(ILL) | <audio src="audio/May-24/fs2-ill/1_60_1.wav" controls preload><audio> | <audio src="audio/May-24/fs2-ill/1_70_1.wav" controls preload><audio> |
Fine-tuned FS2(Neutral) | <audio src="audio/May-24/fs2-neutral/1_60_1.wav" controls preload><audio> | <audio src="audio/May-24/fs2-neutral/1_70_1.wav" controls preload><audio> |
Fine-tuned FS2(Happy) | <audio src="audio/May-24/fs2-happy/1_60_1.wav" controls preload><audio> | <audio src="audio/May-24/fs2-happy/1_70_1.wav" controls preload><audio> |


## MUSTARD\_Plus\_Plus with reference speech(update on June 07)

| <center> Methods </center> | <center> example1(reference1) </center>| <center> Example1(reference2) </center>|<center> Example1(reference3) </center>| <center> Example1(reference4) </center>| <center> example2(reference1) </center>| <center> Example2(reference2) </center>|<center> Example2(reference3) </center>| <center> Example2(reference4) </center>|
| -------------------- | ---------------------- |---------------------- |---------------------- | -------------------- | ---------------------- |---------------------- |---------------------- |
Fine-tuned FS2(w/o feedback) | <audio src="audio/June-7/ref_wo_fb/1_60_1.wav" controls preload><audio> | <audio src="audio/June-7/ref_wo_fb/1_60_2.wav" controls preload><audio> | <audio src="audio/June-7/ref_wo_fb/1_60_3.wav" controls preload><audio> | <audio src="audio/June-7/ref_wo_fb/1_60_20.wav" controls preload><audio> | <audio src="audio/June-7/ref_wo_fb/1_70_1.wav" controls preload><audio> | <audio src="audio/June-7/ref_wo_fb/1_70_2.wav" controls preload><audio>| <audio src="audio/June-7/ref_wo_fb/1_70_3.wav" controls preload><audio> | <audio src="audio/June-7/ref_wo_fb/1_70_20.wav" controls preload><audio>
Fine-tuned FS2(w/o feedback) | <audio src="audio/June-7/ref_w_fb/1_60_1.wav" controls preload><audio> | <audio src="audio/June-7/ref_w_fb/1_60_2.wav" controls preload><audio> | <audio src="audio/June-7/ref_w_fb/1_60_3.wav" controls preload><audio> | <audio src="audio/June-7/ref_w_fb/1_60_20.wav" controls preload><audio> | <audio src="audio/June-7/ref_w_fb/1_70_1.wav" controls preload><audio> | <audio src="audio/June-7/ref_w_fb/1_70_2.wav" controls preload><audio>| <audio src="audio/June-7/ref_w_fb/1_70_3.wav" controls preload><audio> | <audio src="audio/June-7/ref_w_fb/1_70_20.wav" controls preload><audio>


## Evaluate on unseen data, from tweet sarcastic texts(update on June-14)

- text1: size on the the toulouse team that pack be monstrous i cant see a welsh region ever win this money talk a they say,0
- text2: villainous pro tip change the device name on her bluetooth device so she doesnt forget u,0
- text3: if there one fictional place i could go christmas at hogwarts would be that place,0
- text4: i mean it a great cause theyre do it for but can we not have new xmas music thats well good,0
- text5: where do they get 1 22xg from without the pen,0
- text6: so the scottish government want people to get their booster shot so badly that the website doesnt even work,1
- text7: sometimes i lay in bed and think about how today will be the day i make my life well exercise drinking water eat healthy then i wake up,1
- text8: max verstappen be such a clean driver he never make dirty move when race,1
- text9: boris look so statesman like in that public address,1
- text10: wow the prime minister be so good at the tell the truth yet again he just cant stop tell the truth about brexit,1

| <center> text(from iSarcasm) </center> | <center> pretrain </center>| <center> FT </center>|<center> FT(sarcastic) </center>| <center> FT(bert) </center>| <center> FT(ref) </center>| <center> FT(feedback) </center>|<center> FT(2feedback) </center>|
| -------------------- | ---------------------- |---------------------- |---------------------- | -------------------- | ---------------------- |---------------------- |
text1 | <audio src="audio/June-14/pretrain/0_0.wav" controls preload><audio> | <audio src="audio/June-14/all/0_0.wav" controls preload><audio> | <audio src="audio/June-14/sarcastic/0_0.wav" controls preload><audio> | <audio src="audio/June-14/bert/0_0.wav" controls preload><audio> | <audio src="audio/June-14/ref/0_0.wav" controls preload><audio> | <audio src="audio/June-14/fb/0_0.wav" controls preload><audio>| <audio src="audio/June-14/fb2/0_0.wav" controls preload><audio> |
text2 | <audio src="audio/June-14/pretrain/1_0.wav" controls preload><audio> | <audio src="audio/June-14/all/1_0.wav" controls preload><audio> | <audio src="audio/June-14/sarcastic/1_0.wav" controls preload><audio> | <audio src="audio/June-14/bert/1_0.wav" controls preload><audio> | <audio src="audio/June-14/ref/1_0.wav" controls preload><audio> | <audio src="audio/June-14/fb/1_0.wav" controls preload><audio>| <audio src="audio/June-14/fb2/1_0.wav" controls preload><audio> |
text3 | <audio src="audio/June-14/pretrain/2_0.wav" controls preload><audio> | <audio src="audio/June-14/all/2_0.wav" controls preload><audio> | <audio src="audio/June-14/sarcastic/2_0.wav" controls preload><audio> | <audio src="audio/June-14/bert/2_0.wav" controls preload><audio> | <audio src="audio/June-14/ref/2_0.wav" controls preload><audio> | <audio src="audio/June-14/fb/2_0.wav" controls preload><audio>| <audio src="audio/June-14/fb2/2_0.wav" controls preload><audio> |
text4 | <audio src="audio/June-14/pretrain/3_0.wav" controls preload><audio> | <audio src="audio/June-14/all/3_0.wav" controls preload><audio> | <audio src="audio/June-14/sarcastic/3_0.wav" controls preload><audio> | <audio src="audio/June-14/bert/3_0.wav" controls preload><audio> | <audio src="audio/June-14/ref/3_0.wav" controls preload><audio> | <audio src="audio/June-14/fb/3_0.wav" controls preload><audio>| <audio src="audio/June-14/fb2/3_0.wav" controls preload><audio> |
text5 | <audio src="audio/June-14/pretrain/4_0.wav" controls preload><audio> | <audio src="audio/June-14/all/4_0.wav" controls preload><audio> | <audio src="audio/June-14/sarcastic/4_0.wav" controls preload><audio> | <audio src="audio/June-14/bert/4_0.wav" controls preload><audio> | <audio src="audio/June-14/ref/4_0.wav" controls preload><audio> | <audio src="audio/June-14/fb/4_0.wav" controls preload><audio>| <audio src="audio/June-14/fb2/4_0.wav" controls preload><audio> |
text6 | <audio src="audio/June-14/pretrain/0_1.wav" controls preload><audio> | <audio src="audio/June-14/all/0_1.wav" controls preload><audio> | <audio src="audio/June-14/sarcastic/0_1.wav" controls preload><audio> | <audio src="audio/June-14/bert/0_1.wav" controls preload><audio> | <audio src="audio/June-14/ref/0_1.wav" controls preload><audio> | <audio src="audio/June-14/fb/0_1.wav" controls preload><audio>| <audio src="audio/June-14/fb2/0_1.wav" controls preload><audio> |
text7 | <audio src="audio/June-14/pretrain/1_1.wav" controls preload><audio> | <audio src="audio/June-14/all/1_1.wav" controls preload><audio> | <audio src="audio/June-14/sarcastic/1_1.wav" controls preload><audio> | <audio src="audio/June-14/bert/1_1.wav" controls preload><audio> | <audio src="audio/June-14/ref/1_1.wav" controls preload><audio> | <audio src="audio/June-14/fb/1_1.wav" controls preload><audio>| <audio src="audio/June-14/fb2/1_1.wav" controls preload><audio> |
text8 | <audio src="audio/June-14/pretrain/2_1.wav" controls preload><audio> | <audio src="audio/June-14/all/2_1.wav" controls preload><audio> | <audio src="audio/June-14/sarcastic/2_1.wav" controls preload><audio> | <audio src="audio/June-14/bert/2_1.wav" controls preload><audio> | <audio src="audio/June-14/ref/2_1.wav" controls preload><audio> | <audio src="audio/June-14/fb/2_1.wav" controls preload><audio>| <audio src="audio/June-14/fb2/2_1.wav" controls preload><audio> |
text9 | <audio src="audio/June-14/pretrain/3_1.wav" controls preload><audio> | <audio src="audio/June-14/all/3_1.wav" controls preload><audio> | <audio src="audio/June-14/sarcastic/3_1.wav" controls preload><audio> | <audio src="audio/June-14/bert/3_1.wav" controls preload><audio> | <audio src="audio/June-14/ref/3_1.wav" controls preload><audio> | <audio src="audio/June-14/fb/3_1.wav" controls preload><audio>| <audio src="audio/June-14/fb2/3_1.wav" controls preload><audio> |
text10 | <audio src="audio/June-14/pretrain/4_1.wav" controls preload><audio> | <audio src="audio/June-14/all/4_1.wav" controls preload><audio> | <audio src="audio/June-14/sarcastic/4_1.wav" controls preload><audio> | <audio src="audio/June-14/bert/4_1.wav" controls preload><audio> | <audio src="audio/June-14/ref/4_1.wav" controls preload><audio> | <audio src="audio/June-14/fb/4_1.wav" controls preload><audio>| <audio src="audio/June-14/fb2/4_1.wav" controls preload><audio> |

---


## StyleSpeech on MUSTARD Plus Plus (update on June-28)

| <center> Methods </center> | <center> example1 </center> |
| -------------------- | -------------------- |
GroundTruth | <audio src="audio/Feb-22/mmsd_adobe/1_60.wav" controls preload><audio> |
Pre-trained FS2 | <audio src="audio/Feb-22/mmsd_adobe/1_60.wav" controls preload><audio> |
Fine-tuned FS2 | <audio src="audio/Feb-22/mmsd_adobe/1_60.wav" controls preload><audio> |
Pre-trained StyleSpeech | <audio src="audio/Feb-22/mmsd_adobe/1_60.wav" controls preload><audio> |
Fine-tuned StyleSpeech | <audio src="audio/Feb-22/mmsd_adobe/1_60.wav" controls preload><audio> |