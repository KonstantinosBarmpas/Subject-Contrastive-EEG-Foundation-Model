# **Subject-Aware Contrastive Learning for EEG Foundation Models**

## NeurIPS 2025 - Workshop on Learning from Time Series for Health (TS$H)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Published in <strong>NeurIPS 2025</strong> NeurIPS 2025 - Workshop on Learning from Time Series for Health (TS4H), 2025 - [Paper](https://openreview.net/pdf?id=MdgBATPjEu)

Authors: Antonis Karantonis*, <strong>Konstantinos Barmpas*</strong>, Dimitrios Adamos, Nikolaos Laskaris, Stefanos Zafeiriou and Yannis Panagakis

Visit: https://timeseries4health.github.io

---

Foundation models are beginning to reshape EEG representation learning, but existing approaches remain dominated by self-supervised reconstruction objectives. In this work, we introduce the first subject-aware contrastive EEG foundation model, leveraging subject identity as a natural supervisory signal. Building on a patch-based architecture inspired by recent Large Brainwave Foundation Models (LBMs), we pretrain a lightweight transformer encoder using contrastive learning, where positive pairs are drawn from different segments and sessions of the same subject. Unlike contrastive foundation models in other domains, which depend on augmentations to construct positive samples, our method relies on naturally occurring intra-subject variability across EEG sessions. We evaluate the model through both representation metrics (alignment, uniformity and smooth effective rank) and downstream tasks (under linear probing and full fine-tuning). Results show that our model produces well-structured representation spaces, achieving strong representation quality and competitive performance compared to other LBMs.

---
