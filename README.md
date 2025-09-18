# BCI-Agent v1.0

Autonomous AI agent for **cell-type-specific neural decoding** (BCI-Agent v1.0).

Preprint: https://www.biorxiv.org/content/10.1101/2025.09.11.675660v1

BCI-Agent interprets extracellular spike waveforms as structured visual patterns. Leveraging vision–language models (VLMs) and LLM-based reasoning, it performs few-shot cell-type inference, validates predictions against molecular atlases for anatomical plausibility, aligns neural identities across sessions, and explains cell-type-specific dynamics during behavior. The agent can also generate analysis code and comprehensive reports, introducing a scalable path to interpretable BCI decoding.

## Code Availability
We are finalizing the code for end users, focusing on accessibility and ease of setup. **Coming soon!**

⭐ If you’re interested in following the development and helping us grow, consider starring this repository!

## Features
- **Training-Free Cell-Type Inference:** Repurposes pretrained VLMs as few-shot learners to classify neuronal subtypes directly from electrophysiological features—**no task-specific fine-tuning**; validated on optogenetically tagged datasets.
- **Atlas + Literature Validation:** Automatically cross-checks predictions against molecular atlases and synthesizes peer-reviewed evidence for transparent, biologically grounded explanations.
- **Stable Tracking & Manifold Decoding:** Aligns neuron identities across sessions and embeds molecular identities in low-dimensional neural manifolds to decode behavior over time.
- **Generalization Across Species & Modalities:** Robust to diverse recording setups (e.g., Neuropixels, flexible arrays) and applicable to rodent and human data with minimal supervision.

  Feel free to reach out: amarinllobet[at]g.[university name].edu; zuwan_lin[at]fas.[university name].edu
