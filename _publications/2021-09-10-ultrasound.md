---
title: "Development and Evaluation of Intraoperative Ultrasound Segmentation with Negative Image Frames and Multiple Observer Labels"
collection: publications
permalink: /publications/2021-09-10-ultrasound
excerpt: 'This work shares practical experience dealing with variability during image segmentation for prostate cancer patients.'
date: 2021-09-10
venue: 'Simplifying Medical Ultrasound. ASMUS 2021. Lecture Notes in Computer Science'
paperurl: 'https://doi.org/10.1007/978-3-030-87583-1_3'
citation: 'Chalcroft L.F. et al. (2021) Development and Evaluation of Intraoperative Ultrasound Segmentation with Negative Image Frames and Multiple Observer Labels. In: Noble J.A., Aylward S., Grimwood A., Min Z., Lee SL., Hu Y. (eds) Simplifying Medical Ultrasound. ASMUS 2021. Lecture Notes in Computer Science, vol 12967. Springer, Cham.'
---

**Abstract.** When developing deep neural networks for segmenting intraoperative ultrasound images, several practical issues are encountered frequently, such as the presence of ultrasound frames that do not contain regions of interest and the high variance in ground-truth labels. In this study, we evaluate the utility of a pre-screening classification network prior to the segmentation network. Experimental results demonstrate that such a classifier, minimising frame classification errors, was able to directly impact the number of false positive and false negative frames. Importantly, the segmentation accuracy on the classifier-selected frames, that would be segmented, remains comparable to or better than those from standalone segmentation networks. Interestingly, the efficacy of the pre-screening classifier was affected by the sampling methods for training labels from multiple observers, a seemingly independent problem. We show experimentally that a previously proposed approach, combining random sampling and consensus labels, may need to be adapted to perform well in our application. Furthermore, this work aims to share practical experience in developing a machine learning application that assists highly variable interventional imaging for prostate cancer patients, to present robust and reproducible open-source implementations, and to report a set of comprehensive results and analysis comparing these practical, yet important, options in a real-world clinical application.

[Download our paper here.](https://www.springerprofessional.de/en/development-and-evaluation-of-intraoperative-ultrasound-segmenta/19688282)
