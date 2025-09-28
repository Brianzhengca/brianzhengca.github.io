---
title:          "Broken Tokens? Your Language Model can Secretly Handle Non-Canonical Tokenizations"
date:           2025-09-18 00:01:00 +0800
selected:       true
pub:            "Conference on Neural Information Processing Systems (NeurIPS)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight (Top 3%)</span>'
pub_date:       "2025"
# semantic_scholar_id: 5bec2a6df12e4cc6034490e400abecfc7ae090fb  # use this to retrieve citation count
abstract: >-
  Modern tokenizers employ deterministic algorithms to map text into a single “canonical” token sequence, yet the same string can be encoded as many noncanonical tokenizations using the tokenizer vocabulary. In this work, we investigate the robustness of LMs to text encoded with non-canonical tokenizations entirely unseen during training. Surprisingly, when evaluated across 20 benchmarks, we find that instruction-tuned models retain up to 93.4% of their original performance when given a randomly sampled tokenization, and 90.8% with character-level tokenization. We see that overall stronger models tend to be more robust, and robustness diminishes as the tokenization departs farther from the canonical form. Motivated by these results, we then identify settings where non-canonical tokenization schemes can improve performance, finding that character-level segmentation improves string manipulation and code understanding tasks by up to +14%, and right-aligned digit grouping enhances large-number arithmetic by +33%. Finally, we investigate the source of this robustness, finding that it arises in the instructiontuning phase. We show that while both base and post-trained models grasp the semantics of non-canonical tokenizations (perceiving them as containing misspellings), base models try to mimic the imagined mistakes and degenerate into nonsensical output, while post-trained models are committed to fluent responses. Overall, our findings suggest that models are less tied to their tokenizer than previously believed, and demonstrate the promise of intervening on tokenization at inference time to boost performance.
cover:          /assets/images/covers/cover3.jpg
authors:
  - Your Name
  - James Wang
  - Some Other Name
  - John Doe
links:
  Code: https://github.com/luost26/academic-homepage
  Unsplash: https://unsplash.com/photos/sliced-in-half-pineapple--_PLJZmHZzk
---
