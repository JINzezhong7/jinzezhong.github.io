---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am **Zezhong Jin**, a Ph.D. student in the Department of Electrical and Electronic Engineering at **The Hong Kong Polytechnic University**. My research focuses on robust speaker representation learning, generative models, speech large language models, automatic speech recognition (ASR), speech-to-speech translation, and speech emotion recognition.

I have worked as a research intern at **Microsoft Research Asia**, **Tencent**, and **Zoom**, where I explored speech large language models, speech-to-speech translation, online handwriting generation, acoustic modeling, handwriting recognition, and low-resource ASR. My work has appeared in venues and journals including **EMNLP**, **ICASSP**, **INTERSPEECH**, **APSIPA ASC**, **Neurocomputing**, and **IEEE/ACM TASLP**.

[[Google Scholar](https://scholar.google.com/citations?hl=zh-CN&user=PvJY5hEAAAAJ)] &nbsp; [[Email](mailto:zezhong.jin@connect.polyu.hk)]

# 🔥 News

- *2026.07*: Tutorial speaker for **Speech Large Language Models: Architectures, Efficient Adaptation, and Applications** at ICME 2026.
- *2026.01*: Started a research internship at **Tencent**, working on CR-CTC Conformer acoustic modeling and on-device handwriting recognition.
- *2025.11*: Completed a research internship at **Microsoft Research Asia**, focusing on LLM-driven speech-to-speech translation.
- *2025*: **TrInk: Ink Generation with Transformer Network** was accepted by **EMNLP 2025**.
- *2025*: **Denoising Student Features with Diffusion Models for Knowledge Distillation in Speaker Verification** was accepted by **ICASSP 2025**.
- *2024*: **Self-Supervised Learning with Multi-Head Multi-Mode Knowledge Distillation for Speaker Verification** was accepted by **INTERSPEECH 2024**.

# 📝 Selected Publications

- **TrInk: Ink Generation with Transformer Network**  
  **Z. Jin**, S. Desai, X. Chen, B. Fang, Z. Huang, Z. Li, C.-X. Gan, X. Tu, M.-W. Mak, Y. Lu, and S. Liu.  
  *EMNLP 2025*.

- **Uncertainty-Aware Multi-Head Multi-Mode Knowledge Distillation for Self-Supervised Speaker Verification**  
  **Z. Jin**, Y. Tu, Z. Li, M.-W. Mak, and K.-A. Lee.  
  *IEEE/ACM Transactions on Audio, Speech, and Language Processing*, 2025.

- **Denoising Student Features with Diffusion Models for Knowledge Distillation in Speaker Verification**  
  **Z. Jin**, Y. Tu, Z. Li, Z. Huang, C.-X. Gan, and M.-W. Mak.  
  *ICASSP 2025*, Hyderabad, India.

- **Adversarially Adaptive Temperatures for Decoupled Knowledge Distillation with Applications to Speaker Verification**  
  **Z. Jin**, Y. Tu, C.-X. Gan, and M.-W. Mak.  
  *Neurocomputing*, Elsevier, 2024.

- **JOSEPH: Phonetic-Aware Speaker Embedding for Far-Field Speaker Verification**  
  **Z. Jin**, Y. Tu, and M.-W. Mak.  
  *APSIPA ASC 2024*, Macau, China.

- **Self-Supervised Learning with Multi-Head Multi-Mode Knowledge Distillation for Speaker Verification**  
  **Z. Jin**, Y. Tu, and M.-W. Mak.  
  *INTERSPEECH 2024*, Kos Island, Greece.

- **W-GVKT: Within-Global-View Knowledge Transfer for Speaker Verification**  
  **Z. Jin**, Y. Tu, and M.-W. Mak.  
  *INTERSPEECH 2024*, Kos Island, Greece.

- **Voice Cloning-Based Data Augmentation for Speaker Recognition**  
  **Z. Jin**.  
  *NCMMSC 2023*, Suzhou, China.

- **Pseudo Label Refining for Semi-supervised Automatic Speech Recognition**  
  **Z. Jin** and R. Zhang.  
  *NCMMSC 2023*, Suzhou, China.

# 💼 Research Experience

**Tencent, Sogou Input Method** — Research Intern  
*Jan 2026 - May 2026*

- Improved acoustic modeling with a CR-CTC Conformer architecture.
- Explored Residual Attention, mHC, and Mixture-of-Experts modules for CR-CTC Conformer.
- Independently led the development and iteration of an on-device handwriting recognition module.
- Addressed mixed Chinese-English handwriting, cursive input, and deployment under strict mobile computation and memory constraints.
- Improved performance across 23 core handwriting-recognition test sets.

**Microsoft Research Asia, Multimedia Computing Group** — Research Intern  
*Jul 2025 - Nov 2025*

- Explored high-quality speech-to-speech translation using large language models.
- Proposed a parallel modeling strategy for jointly modeling speech and text.
- Designed a truncation mechanism for semantically redundant text tokens to improve inference efficiency.
- Built a prototype LLM-driven S2ST framework.

**Microsoft Research Asia, Multimedia Computing Group** — Research Intern  
*Nov 2024 - Jul 2025*

- Proposed **TrInk**, a Transformer-based online handwriting generation framework.
- Designed a Transformer encoder-decoder model with Gaussian masking and learnable positional encoding.
- Introduced encoder-decoder domain alignment for improved cross-modal modeling.
- Improved CER by 35.56% and WER by 29.66% over previous methods on IAM-OnDB.

**Zoom, Speech Group** — Research Intern  
*Apr 2022 - Aug 2022*

- Worked on ASR under limited labeled-data settings.
- Used wav2vec 2.0, pseudo-label filtering, and iterative fine-tuning.
- Achieved WERs of 4.97% and 10.25% on LibriSpeech clean and other sets, respectively.

# 🎓 Education

- *May 2023 - Present*, Ph.D. in Electrical and Electronic Engineering, Electronic Information (Artificial Intelligence), **The Hong Kong Polytechnic University**.
- *Aug 2021 - May 2023*, Research M.Phil. in Electrical and Electronic Engineering, Electronic Information (Artificial Intelligence), **The Hong Kong Polytechnic University**. GPA: 3.83/4.00.
- B.Eng. in Electronic Information, Software Engineering Track, **Hebei University**. GPA: 3.76/4.00.

# 🎖 Honors and Awards

- Outstanding Graduate, The Hong Kong Polytechnic University, 2023.
- Outstanding Thesis Award, The Hong Kong Polytechnic University, 2023.
- The Hong Kong Polytechnic University Scholarship, 2022.
- First-Class Scholarship, Hebei University, 2018, 2019, 2020.
- Reviewer for ICASSP 2024, 2025, and 2026.
- Reviewer for INTERSPEECH 2025.
- Reviewer for APSIPA 2025.

# 📚 Patents

- **ONLINE INK GENERATION USING A TRANSFORMER NETWORK**, Invention Patent, No. 505283-US01.
- **Electronic Information Protection Device**, Utility Model Patent, Patent No. ZL 2019 2 0216847.1.

# 💻 Skills

- **Programming:** Python, C++, CUDA programming.
- **Deep Learning:** PyTorch, TensorFlow.
- **Large Models:** Transformer architecture design, attention optimization, Mixture-of-Experts models, RLHF, TRL.
- **Model Optimization:** Quantization, knowledge distillation, model pruning, and parallel training.

# 💬 Talks

- *Jun 2024*, Self-Supervised Learning with Multi-Head Multi-Mode Knowledge Distillation for Speaker Verification, INTERSPEECH 2024 paper preview seminar.
- *Jun 2024*, W-GVKT: Within-Global-View Knowledge Transfer for Speaker Verification, INTERSPEECH 2024 paper preview seminar.
- *Mar 2025*, Denoising Student Features with Diffusion Models for Knowledge Distillation in Speaker Verification, ICASSP 2025 paper preview seminar.
- *Jul 2026*, Speech Large Language Models: Architectures, Efficient Adaptation, and Applications, ICME 2026 Tutorial.
