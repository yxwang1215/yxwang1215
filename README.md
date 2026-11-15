<h1 align="center">Yuxuan Wang · 王宇轩</h1>

<p align="center">
  <strong>Efficient multimodal LLMs</strong> · <strong>supervised fine-tuning</strong> · <strong>KV-cache compression</strong>
</p>

<p align="center">
  Incoming Ph.D. at <a href="https://cs.pku.edu.cn/">Peking University</a> (2027), advised by <a href="https://yangtonghome.github.io/">Prof. Tong Yang</a><br>
  B.E. at Xidian University · Intern at <a href="https://ai.360.com/">360 Zhinao</a><br>
  Previously <a href="https://epic-lab.github.io/">EPIC Lab @ SJTU</a> and <a href="https://www.leaplab.ai/">LEAP Lab @ Tsinghua</a>
</p>

<p align="center">
  <a href="https://yxwang1215.top">Homepage</a> ·
  <a href="https://scholar.google.com/citations?user=UQgYoZ4AAAAJ&hl=en">Google Scholar</a> ·
  <a href="mailto:yxwang1215@gmail.com">Email</a> ·
  <a href="https://github.com/yxwang1215">GitHub</a>
</p>

I work on making multimodal and language models cheaper to train and run: which tokens to keep, which margins to preserve during fine-tuning, and which cache entries still carry the answer.

## Selected papers

### Efficient multimodal models

| Paper | Venue | Note |
| --- | --- | --- |
| **[AudioKV: KV Cache Eviction in Efficient Large Audio Language Models](https://arxiv.org/abs/2604.06694)** | ACM MM 2026 | Semantic-acoustic alignment and spectral score smoothing keep audio-critical cache entries. [Code](https://github.com/yxwang1215/Audio_kvcache) · [Poster](https://yxwang1215.top/posters/audiokv/) |
| **[Glance, then Select: Evidence-Tempered Visual Token Selection for Extremely Compressed Multimodal LLMs](https://yxwang1215.top/papers/glance-etd/)** | 2026 | A glance pass cuts encoder cost, then evidence-tempered diversity keeps answer tokens at a 5% budget. [Code](https://github.com/yxwang1215/Glance-ETD) |
| **[AudioMarathon: A Comprehensive Benchmark for Long-Context Audio Understanding and Efficiency](https://arxiv.org/abs/2510.07293)** | arXiv 2025 | Long-context audio understanding and efficiency across audio language models. [Code](https://github.com/DabDans/AudioMarathon) |

### LLM training

| Paper | Venue | Note |
| --- | --- | --- |
| **[Beyond Distribution Matching: Selective Margin Preservation for Supervised Fine-Tuning](https://arxiv.org/abs/2610.19685)** | arXiv 2026 | SRP-SFT keeps selected non-target logit margins, improving math reasoning and code generation. [Code](https://github.com/yxwang1215/SRP-SFT) · [Project](https://yxwang1215.top/papers/srp-sft/) |
| **[Efficient On-Policy Distillation for Language Models](https://www.preprints.org/manuscript/202610.2702)** | 2026 | A survey of on-policy distillation across data, rollout, supervision, systems, and deployment. |

### Diffusion language models

| Paper | Venue | Note |
| --- | --- | --- |
| **[Accelerating Diffusion Large Language Models with SlowFast](https://arxiv.org/abs/2506.10848)** | ICLR 2026 | Slow and fast sampling guided by token certainty, convergence, and position. [Code](https://github.com/LiangrunFlora/Slow-Fast-Sampling) |
| **[Thinking inside the Mask: In-place Prompting in Diffusion LLMs](https://arxiv.org/abs/2508.10736)** | arXiv 2025 | Reasoning embedded in masked positions, with confidence-aware early exit. [Code](https://github.com/Lueci4er/ICE) |
| **[Self Speculative Decoding for Diffusion Large Language Models](https://arxiv.org/abs/2510.04147)** | arXiv 2025 | Self-drafting and hierarchical verification accept multiple tokens per step. |

### Robotics and medical imaging

| Paper | Venue | Note |
| --- | --- | --- |
| **[UltraHiT: A Hierarchical Transformer Architecture for Generalizable Internal Carotid Artery Robotic Ultrasonography](https://arxiv.org/abs/2509.13832)** | ICRA 2026 | A hierarchical Transformer for generalizable internal-carotid robotic ultrasonography. [Project](https://yxwang1215.github.io/UltraHiT/) · [Code](https://github.com/LeapLabTHU/UltraHiT) |
| **[VA-Adapter: Adapting Ultrasound Foundation Model to Echocardiography Probe Guidance](https://arxiv.org/abs/2510.06809)** | MICCAI 2026 | A vision-action adapter for echocardiography probe guidance. [Code](https://github.com/LeapLabTHU/VA-Adapter) |

## More

Course notes and the full publication list are on the [homepage](https://yxwang1215.top).
