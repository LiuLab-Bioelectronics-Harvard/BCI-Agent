# BCI-Agent

**BCI-Agent** is a general-purpose AI agent designed to perform **cell-type-aware neural decoding** and interpretation for brain-computer interfaces (BCIs).  

Understanding neural population activity during behavior remains a fundamental challenge in neuroscience and neuroengineering. Modern recording technologies provide millisecond-scale access to hundreds of neurons simultaneously, yet interpreting these signals across time and subjects is limited by two critical factors: the inability to track individual neurons reliably across sessions and the lack of molecular identity information in extracellular recordings.

**BCI-Agent** addresses these challenges by leveraging **vision-language models (VLMs)** — pretrained on large-scale general visual and language data — to interpret electrophysiological signals (e.g., spike waveforms) as structured visual patterns. BCI-Agent integrates:

- **Few-shot cell-type classification** from waveform feature images  
- **Multimodal reasoning and literature-grounded explanations**  
- **Validation against molecular atlases** for anatomical plausibility  
- **Interpretation of cell-type-specific dynamics** during behavior  

Despite never being trained on neuroscience data, the system recognizes neuronal cell-type patterns using few-shot visual prompts, and produces biologically plausible insights into long-term neural dynamics. We demonstrate its utility in:

- Multi-session spike sorting and neural trajectory analysis  
- Cell-type inference with anatomical validation  
- Functional decoding of motor learning through cell-type-specific dynamics  

BCI-Agent enables interpretable BCI decoding at the level of consistent, biologically grounded neural populations, laying the foundation for **scalable, cell-type-aware, and explainable neurotechnologies**.

---

## 🔬 Explore the Agent-Army

BCI-Agent is part of a broader suite of intelligent neuroscience tools developed by the Liu Lab:

- 🧠 [SpikeAgent](https://github.com/LiuLab-Bioelectronics-Harvard/SpikeAgent): Automated spike sorting and cell-type inference  
- 🧬 [STAgent](https://github.com/LiuLab-Bioelectronics-Harvard/STAgent): Spatial transcriptomics-based analysis for neural data  
- 🐭 [BehaveAgent](https://github.com/LiuLab-Bioelectronics-Harvard/BehaveAgent): Automates behavior analysis from video without manual intervention across species and experimental paradigms.

---

Stay tuned for the full BCI-Agent release — including code, documentation, and datasets!
