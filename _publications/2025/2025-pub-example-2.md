---
title:          "PC-POCS sampler to reconstruct a low-dose computer tomography image consistent with both the prior and the measurements"
date:           2025-07-15 00:00:00 +0800
selected:       True
# pub:            "The Pacific Rim International Conference on Artificial Intelligence(PRICAI)"
pub_pre:        "Submitted to The IEEE International Conference on Bioinformatics and Biomedicine(BIBM)"
#pub_post:       'Under review.'
pub_date:       "2025"
abstract: >-
  Reconstructing medical images from partial measuremets is a critical inverse problem in Computer Tomography, essential for reducing radiation exposure while maintaining diagnostic accuracy, addressing challenges of small size and poor resolution in CT data. Existing solutions based on machine learning typically train a model to directly map measurements to medical images, relying on a training dataset of paired images and measurements synthesized using a fixed physical model of the measurement process; however, this approach greatly hinders generalization to unknown measurement processes. To address this issue, we propose a fully unsupervised technique for solving the inverse problem, leveraging score-based generative models to eliminate the need for paired data. Specifically, we first train a score-based generative model on clean conventional-dose medical images to capture their prior distribution. Then, given measurements and a physical model of the measurement process, we introduce a sampling method to reconstruct an image consistent with both the prior and the measurements. Empirically, we observe comparable or better performance to other sampling techniques in several medical imaging tasks in Computer Tomography, while demonstrating considerably better generalization to unknown measurement processes.

# cover:          /assets/images/covers/cover2.jpg
authors:
  - Yuchen Quan#
  - Yaru Xue

#links:
#  Paper: https://www.biorxiv.org
#  Code: https://github.com
#  Unsplash: https://unsplash.com/photos/orange-fruit-on-white-table-cloth-ISX_imp8t1o
---