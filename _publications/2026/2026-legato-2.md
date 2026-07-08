---
title:          "LEGATO 2: Toward Multimodal Sheet Music Recognition and Understanding"
date:           2026-07-07 00:01:00 +0000
selected:       true
pub:            "arXiv preprint"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_date:       "2026"
# semantic_scholar_id: 5bec2a6df12e4cc6034490e400abecfc7ae090fb  # use this to retrieve citation count
abstract: >-
  We propose a novel pipeline, Legato 2, for extracting symbolic notation and semantic knowledge from images of sheet music. Legato 2 features the first large-scale neural model for optical music recognition (OMR) to operate sequentially on a system-by-system basis, following the horizontal lines of notation as they are read on the page, rather than treating the page as an undifferentiated image, enabling better scaling to arbitrarily long inputs. It is also the first OMR model capable of generating symbolic transcriptions that include embedded textual content, such as titles and annotations. The pipeline combines system-level segmentation with an autoregressive vision-LM to capture both local notation details and score structure. Across multiple datasets, Legato 2 consistently outperforms prior state of the art. We also show that symbolic transcriptions complement visual inputs for frontier language models, improving their interpretation of dense musical documents. Legato 2 establishes new state-of-the-art performance in both OMR and downstream sheet music understanding.
cover:          /assets/images/covers/legato2.png
authors:
  - "Guang Yang*"
  - "Brian Siyuan Zheng*"
  - Victoria Ebert
  - Noah A. Smith
links:
  Paper: https://arxiv.org/abs/2607.05769
---
