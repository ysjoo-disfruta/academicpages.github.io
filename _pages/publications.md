---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=Kwm6sq0AAAAJ}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
You can also find my papers on my [Google Scholar](https://scholar.google.com/citations?user=Kwm6sq0AAAAJ) profile.

***
- Avocodo: Generative adversarial network for artifact-free vocoder
[[paper](https://arxiv.org/abs/2206.13404)]
[[demo]([https://ryojerky.github.io/demo_vc-tts-ps/](https://nc-ai.github.io/speech/publications/Avocodo/index.html))]
[[code](https://github.com/ncsoft/avocodo)]  
  <small>Taejun Bak, Junmo Lee, Hanbin Bae, Jinhyeok Yang, Jae-Sung Bae, **Young-Sun Joo**</small>  
  <small>Proc. AAAI, 2023.</small>

- Enhancement of Pitch Controllability using Timbre-Preserving Pitch Augmentation in FastPitch
[[paper](https://www.isca-speech.org/archive/pdfs/interspeech_2022/bae22_interspeech.pdf)]
[[demo](https://nc-ai.github.io/speech/publications/vocgan-ps-fastpitch/index.html)]  
  <small>Hanbin Bae, **Young-Sun Joo**</small>  
  <small>Proc. INTERSPEECH, 2022.</small>
  
- Hierarchical and Multi-Scale Variational Autoencoder for Diverse and Natural Speech Synthesis
[[paper](https://www.isca-speech.org/archive/pdfs/interspeech_2022/bae22b_interspeech.pdf)]
[[demo](https://nc-ai.github.io/speech/publications/himuv-tts/index.html)]  
  <small>Jae-Sung Bae, Jinhyeok Yang, Tae-Jun Bak, **Young-Sun Joo**</small>  
  <small>Proc. INTERSPEECH, 2022.</small>

- Hierarchical Context-Aware Transformers for Non-Autoregressive Text to Speech
[[paper](https://www.isca-speech.org/archive/pdfs/interspeech_2021/bae21_interspeech.pdf)]
[[demo](https://nc-ai.github.io/speech/publications/hierarchical-transformers-tts/index.html)]  
  <small>Jae-Sung Bae, Tae-Jun Bak, **Young-Sun Joo**, Hoon-Young Cho</small>  
  <small>Proc. INTERSPEECH, 2021.</small>

- A Neural Text-to-Speech Model utilizing Broadcast Data Mixed with Background Music
[[paper](https://arxiv.org/pdf/2103.03049.pdf)]
[[demo](https://nc-ai.github.io/speech/publications/tts-with-bgm-data/index.html)]  
  <small>Hanbin Bae, Jae-Sung Bae, **Young-Sun Joo**, Young-Ik Kim, and Hoon-Young Cho</small>  
  <small>Proc. ICASSP, 2021.</small>

- Effective Emotion Transplantation in an End-to-End Text-to-Speech System
[[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9186605)]
[[demo](https://nc-ai.github.io/speech/publications/emotion-tts/)]  
  <small>**Young-Sun Joo**, Hanbin Bae, Young-Ik Kim, Hoon-Young Cho, Hong-Goo Kang</small>  
  <small>IEEE Access, 2020.</small>

- Speaking Speed Control of End-to-End Speech Synthesis using Sentence-Level Conditioning
[[paper](https://www.isca-speech.org/archive_v0/Interspeech_2020/pdfs/1361.pdf)]
[[demo](https://nc-ai.github.io/speech/publications/speed-controllable-tts/index.html)]
[[video](https://www.youtube.com/watch?v=WyDfc53Ez_A)]  
  <small>Jae-Sung Bae, Hanbin Bae, **Young-Sun Joo**, Junmo Lee, Gyeong-Hoon Lee, Hoon-Young Cho</small>  
  <small>Proc. INTERSPEECH, 2020.</small>

- A Study on Acoustic Parameter Selection Strategies to Improve Deep Learning-Based Speech Synthesis
[[paper](http://www.apsipa.org/proceedings/2019/pdfs/121.pdf)]  
  <small>Hyeonjoo Kang, **Young-Sun Joo**, Inseon Jang, Chunghyun Ahn, Hong-Goo Kang</small>  
  <small>Proc. APSIPA ASC, 2019.</small>
  
- Efficient Deep Neural Networks for Speech Synthesis using Bottleneck Features
[[paper](http://www.apsipa.org/proceedings_2016/HTML/paper2016/160.pdf)]  
  <small>**Young-Sun Joo**, Won-Suk Jun, Hong-Goo Kang</small>  
  <small>Proc. APSIPA ASC, 2016.</small>
  
- A pitch-synchronous speech analysis and synthesis method for DNN-SPSS system
[[paper](https://ieeexplore.ieee.org/abstract/document/7868589)]  
  <small>Jin-Seob Kim, **Young-Sun Joo**, Hong-Goo Kang, Inseon Jang, ChungHyun Ahn, Jeongil Seo</small>  
  <small>Proc. DSP, 2016.</small>
  
- Improved Time-Frequency Trajectory Excitation Modeling for a Statistical Parametric Speech Synthesis System
[[paper](https://ieeexplore.ieee.org/abstract/document/7178912)]  
  <small>Eunwoo Song, **Young-Sun Joo**, Hong-Goo Kang</small>  
  <small>Proc. ICASSP, 2015.</small>
  
- Enhancement of Spectral Clarity for HMM-based Text-to-Speech Systems
[[paper](https://ieeexplore.ieee.org/abstract/document/6639190)]  
  <small>**Young-Sun Joo**, Chi-Sang Jung, Hong-Goo Kang</small>  
  <small>Proc. ICASSP, 2013.</small>
  
- Waveform Interpolation-Based Speech Analysis/Synthesis for HMM-based TTS Systems
[[paper](https://ieeexplore.ieee.org/abstract/document/6319353)]  
  <small>Chi-Sang Jung, **Young-Sun Joo**, Hong-Goo Kang</small>  
  <small>IEEE Signal Processing Letters, 2012.</small>
