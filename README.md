# Universal Speech Assessment Model

This repository aims to collect all available speech asessment models (with the github page) including speech quality and intelligibility prediction models.

## Speech Quality Prediction Models
We collect both human-based and objective-based speech quality prediction model. 

### 1. Human-based Speech Quality Prediction
The human-based speech quality prediction generally aims to predict mean opinion scores from several listeners. Nowadays, several benchmark datasets are interestingly designed for different speech processing applications; for example, in speech enhancement tasks, the speech assessment model aims to predict the quality of enhanced speech which has performed noise reduction to remove the noise parts.

### A. Task: Voice Conversion/ Text-to-Speech
- Dataset:  VCC2018 

  Available Model : 

  - MOSNet: Deep Learning based Objective Assessment for Voice Conversion <a href="https://github.com/lochenchou/MOSNet" target="_blank">[code]</a>
<a href="https://arxiv.org/abs/1904.08352" target="_blank">[paper]</a>

  - MBNet: MOS Prediction for Synthesized Speech with Mean-Bias Network <a href="https://github.com/sky1456723/Pytorch-MBNet" target="_blank">[code]</a>
<a href="https://arxiv.org/abs/2103.00110" target="_blank">[paper]</a>

  - Utilizing Self-supervised Representations for MOS Prediction <a href="https://github.com/s3prl/s3prl/tree/master/s3prl/downstream/mos_predictiont" target="_blank">[code]</a>
<a href="https://paperswithcode.com/paper/utilizing-self-supervised-representations-for" target="_blank">[paper]</a>

  - LDNet: Unified Listener Dependent Modeling in MOS Prediction for Synthetic Speech <a href="https://github.com/unilight/LDNet" target="_blank">[code]</a>
<a href="https://arxiv.org/pdf/2110.09103.pdf" target="_blank">[paper]</a>

- Dataset:  Blizzard Challenge

  Available Model: 

  - Deep Learning Based Assessment of Synthetic Speech Naturalness <a href="https://github.com/gabrielmittag/NISQA" target="_blank">[code]</a>
<a href="https://arxiv.org/pdf/2104.11673.pdf" target="_blank">[paper]</a>

- Dataset:  VoiceMOS Challenge

  Available Model:

  - Generalization Ability of MOS Prediction Networks <a href="https://github.com/nii-yamagishilab/mos-finetune-ssl/blob/main/VoiceMOS_baseline_README.md" target="_blank">[code]</a>
<a href="https://arxiv.org/abs/2110.02635" target="_blank">[paper]</a>

  - LDNet: Unified Listener Dependent Modeling in MOS Prediction for Synthetic Speech <a href="https://github.com/unilight/LDNet/blob/main/VoiceMOS_baseline_README.md" target="_blank">[code]</a>
<a href="https://arxiv.org/pdf/2110.09103.pdf" target="_blank">[paper]</a>

  - Deep Learning-based Non-Intrusive Multi-Objective Speech Assessment Model with Cross-Domain Features <a href="https://github.com/dhimasryan/MOSA-Net-Cross-Domain/blob/main/VoiceMOS_Baseline_README.md" target="_blank">[code]</a>
<a href="https://ieeexplore.ieee.org/document/9905733" target="_blank">[paper]</a>

  - UTMOS: UTokyo-SaruLab System for VoiceMOS Challenge 2022 <a href="https://github.com/sarulab-speech/UTMOS22" target="_blank">[code]</a>
<a href="https://arxiv.org/pdf/2204.02152" target="_blank">[paper]</a>

### B. Task: Speech Enhancement 

- Dataset:  TMHINT-QI

  Available Model:

  - Deep Learning-based Non-Intrusive Multi-Objective Speech Assessment Model with Cross-Domain Features <a href="https://github.com/dhimasryan/MOSA-Net-Cross-Domain" target="_blank">[code]</a>
<a href="https://ieeexplore.ieee.org/document/9905733" target="_blank">[paper]</a>

  - InQSS: a speech intelligibility and quality assessment model using a multi-task learning network <a href="https://github.com/yuwchen/InQSS" target="_blank">[code]</a>
<a href="https://arxiv.org/abs/2111.02585" target="_blank">[paper]</a>


### C. Task: Teleconference
- Dataset: NISQA Corpus

  Available Model:
  NISQA: 
  - A Deep CNN-Self-Attention Model for Multidimensional Speech Quality Prediction with Crowdsourced Datasets <a href="https://github.com/gabrielmittag/NISQA" target="_blank">[code]</a>
<a href="https://www.isca-speech.org/archive/pdfs/interspeech_2021/mittag21_interspeech.pdf" target="_blank">[paper]</a>  

- Dataset: ConferencingSpeech2022 Datasets

  Available Model:
  - ConferencingSpeech 2022 Challenge: Non-intrusive Objective Speech Quality
Assessment (NISQA) Challenge for Online Conferencing Applications <a href="https://github.com/ConferencingSpeech/ConferencingSpeech2022" target="_blank">[code]</a>
<a href="https://www.isca-speech.org/archive/pdfs/interspeech_2022/yi22b_interspeech.pdf" target="_blank">[paper]</a>

### 2. Objective-based Speech Quality Prediction
The objective-based-speech quality prediction uses signal-processing-based quality metrics as the ground truth label, for example, Perceptual Evaluation of Speech Quality (PESQ).

### A. Task: Speech Enhancement 
- Dataset: TIMIT Corpus

  Available Model:
  - Quality-Net: An End-to-End Non-intrusive Speech Quality Assessment Model
based on BLSTM <a href="https://github.com/JasonSWFu/Quality-Net" target="_blank">[code]</a>
<a href="https://arxiv.org/ftp/arxiv/papers/1808/1808.05344.pdf" target="_blank">[paper]</a>

- Dataset: WSJ Corpus

  Available Model:
  - Deep Learning-based Non-Intrusive Multi-Objective Speech Assessment Model with Cross-Domain Features <a href="https://github.com/dhimasryan/MOSA-Net-Cross-Domain/blob/main/VoiceMOS_Baseline_README.md" target="_blank">[code]</a>
<a href="https://ieeexplore.ieee.org/document/9905733" target="_blank">[paper]</a>

### B. Task: Hearing Aids
  HASA-NET: A NON-INTRUSIVE HEARING-AID SPEECH ASSESSMENT NETWORK
- Dataset: TIMIT Corpus

  Available Model:
  - HASA-net: A non-intrusive hearing-aid speech assessment network <a href="https://github.com/sophie091524/HASA-Net-A-non-intrusive-hearing-aid-speech-assessment-network" target="_blank">[code]</a>
<a href="https://arxiv.org/abs/2111.05691" target="_blank">[paper]</a>

## Speech Intelligibility Prediction Models
### 1. Human-based Speech Intelligibility Prediction
### A. Task: Speech Enhancement

- Dataset:  TMHINT-QI

  Available Model:

  - Deep Learning-based Non-Intrusive Multi-Objective Speech Assessment Model with Cross-Domain Features <a href="https://github.com/dhimasryan/MOSA-Net-Cross-Domain" target="_blank">[code]</a>
<a href="https://ieeexplore.ieee.org/document/9905733" target="_blank">[paper]</a>

  - InQSS: a speech intelligibility and quality assessment model using a multi-task learning network <a href="https://github.com/yuwchen/InQSS" target="_blank">[code]</a>
<a href="https://arxiv.org/abs/2111.02585" target="_blank">[paper]</a>

  - MTI-Net: A Multi-Target Speech Intelligibility Prediction Model <a href="https://github.com/dhimasryan/MOSA-Net-Cross-Domain" target="_blank">[code]</a>
<a href="https://arxiv.org/abs/2204.03310" target="_blank">[paper]</a>

### B. Task: Hearing Aids
- Dataset:  Clarity Challenge

  - The 1st Clarity Prediction Challenge: A machine learning challenge for hearing aid intelligibility prediction <a href=" https://github.com/claritychallenge/clarity_CC/tree/master/clarity_CPC1" target="_blank">[code]</a>
<a href="https://arxiv.org/pdf/2204.03305.pdf" target="_blank">[paper]</a>
  
  - MBI-Net: A Non-Intrusive Multi-Branched Speech Intelligibility Prediction
Model for Hearing Aids <a href="https://github.com/dhimasryan/MOSA-Net-Cross-Domain" target="_blank">[code]</a>
<a href="https://arxiv.org/pdf/2204.03305.pdf" target="_blank">[paper]</a>

### 2. Objective-based Speech Intelligibility Prediction
### A. Task: Speech Enhancement 

  - STOI-Net: A Deep Learning based Non-Intrusive Speech Intelligibility Assessment Model <a href="https://github.com/dhimasryan/STOI-Net" target="_blank">[code]</a>
<a href="https://arxiv.org/abs/2011.04292" target="_blank">[paper]</a>

## Open Source ASR Model
- <a href="https://pypi.org/project/SpeechRecognition/" target="_blank">Google API ASR</a>
- <a href="https://github.com/openai/whisper" target="_blank">Whisper OpenAI ASR</a>

We also create a <a href="https://github.com/speechassess/opensourceASR" target="_blank">repository</a> on how to use those mentioned ASR systems to generate the transcript. 
