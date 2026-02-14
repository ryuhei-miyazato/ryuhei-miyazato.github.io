---
title: 'Ensembling Multiple Hallucination Detectors Trained on VLLM Internal Representations'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Yuto Nakamizo
  - me
  - Hikaru Tanabe
  - Ryuta Yamakura
  - Kiori Hatanaka

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2025-08-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-08-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the KDD Cup Workshop at the 31st SIGKDD Conference on Knowledge Discovery and Data Mining (KDD2025)*
publication_short: In *KDD Cup workshop 2025 at KDD2025*

abstract: This paper presents the 5th place solution by our team, y3h2, for the Meta CRAG-MM Challenge at KDD Cup 2025. The CRAG-MM benchmark is a visual question answering (VQA) dataset focused on factual questions about images, including egocentric images. The competition was contested based on VQA accuracy, as judged by an LLM-based automatic evaluator. Since incorrect answers result in negative scores, our strategy focused on reducing hallucinations from the internal representations of the VLM. Specifically, we trained logistic regression-based hallucination detection models using both the hidden_state and the outputs of specific attention heads. We then employed an ensemble of these models. As a result, while our method sacrificed some correct answers, it significantly reduced hallucinations and allowed us to place among the top entries on the final leaderboard.


# Display this page in the Featured widget?
featured: true

# Custom links
links:
  - type: pdf
    url: "https://arxiv.org/pdf/2510.14330"
  - type: code
    url: https://gitlab.aicrowd.com/htanabe/meta-comprehensive-rag-benchmark-starter-kit

---

> [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
