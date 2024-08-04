---
title:          "Equilibrated Diffusion: Frequency-aware Textual Embedding for Equilibrated Image Customization"
date:           2024-07-20
selected:       true
pub:            "ACM Multimedia (ACMMM)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2024"

abstract: >-
  Image customization involves learning the subject from provided concept images and generating it within textual contexts, typically yielding alterations of attributes such as style or background. Prevailing methods primarily rely on fine-tuning technique, wherein a unified latent embedding is employed to characterize various concept attributes. However, the attribute entanglement renders customized result challenging to mitigate the influence of subject-irrelevant attributes (e.g., style and background). To overcome these issues, we propose Equilibrated Diffusion, an innovative method that achieves equilibrated image customization by decoupling entangled concept attributes from a frequency-aware perspective, thus harmonizing textual and visual consistency. Unlike conventional approaches that employ a shared latent embedding and tuning process to learn concept, our Equilibrated Diffusion draws inspiration from the correlation between high- and low-frequency components with image style and content, decomposing concept accordingly in the frequency domain. Through independently optimizing concept embeddings in the frequency domain, the denoising model not only enriches its comprehension of style attribute irrelevant to subject identity but also inherently augments its aptitude for accommodating novel stylized descriptions. Furthermore, by combining different frequency embeddings, our model retains the spatially original customization capability. We further design a diffusion process guided by subject masks to alleviate the influence of background attribute, thereby strengthening text alignment. To ensure subject-related information consistency, Residual Reference Attention (RRA) is incorporated into the denoising model of spatial attention computation, effectively preserving structural details. Experimental results demonstrate that Equilibrated Diffusion surpasses other competitors with better subject consistency while closely adhering to text descriptions, thus validating the superiority of our approach.
cover:          /assets/images/covers/cover_eqdiff.jpg
authors:
  - Liyuan Ma
  - Xueji Fang
  - Guojun Qi
# links:
  Code: https://github.com/luost26/academic-homepage
  Unsplash: https://unsplash.com/photos/sliced-in-half-pineapple--_PLJZmHZzk
---
