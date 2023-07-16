---
title: "A Semantic-guided and Knowledge-based Generative Framework for Orthodontic Visual Outcome Preview"
collection: publications
permalink: /publication/2023-MICCAI-Orthodontic-Preview-Framework
excerpt: 'A semantic-guided and knowledge-based generative framework to predict the visual outcome of orthodontic treatment from a single frontal photo.'
date: '2023'
venue: 'Medical Image Computing and Computer Assisted Intervention–MICCAI 2023: 26th International Conference'
paperurl: 'http://sjtuzhou.github.io/files/2023-MICCAI-Orthodontic-Preview-Framework.pdf'
citation: 'Y. Chen and X. Chen, "A Semantic-guided and Knowledge-based Generative Framework for Orthodontic Visual Outcome Preview", in Medical Image Computing and Computer Assisted Intervention–MICCAI 2023: 26th International Conference, 2023.'
---
Orthodontic treatment typically lasts for two years, and its outcome cannot be predicted intuitively in advance. In this paper, we propose a semantic-guided and knowledge-based generative framework to predict the visual outcome of orthodontic treatment from a single frontal photo. The framework involves four steps. Firstly, we perform tooth semantic segmentation and mouth cavity segmentation and extract category-specific teeth contours from frontal images. Secondly, we deform the established tooth-row templates to match the projected contours with the detected ones to reconstruct 3D teeth models. Thirdly, we apply a teeth alignment algorithm to simulate the orthodontic treatment. Finally, we train a semantic-guided generative adversarial network to predict the visual outcome of teeth alignment. Quantitative tests are conducted to evaluate the proposed framework, and the results are as follows: the tooth semantic segmentation model achieves a mean intersection of union of 0.834 for the anterior teeth, the average symmetric surface distance error of our 3D teeth reconstruction method is 0.626 mm on the test cases, and the image generation model has an average Fréchet inception distance of 6.847 over all the test images. These evaluation results demonstrate the practicality of our framework in orthodontics.

[Download paper here](http://sjtuzhou.github.io/files/2023-MICCAI-Orthodontic-Preview-Framework.pdf)
