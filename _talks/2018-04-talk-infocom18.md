---
title: "LipPass: Lip Reading-based User Authentication Leveraging Acoustic Signals on Smartphones"
collection: talks
type: "Talk"
permalink: /talks/2018-04-talk-infocom18
venue: "Sensing, Recognition and Tracking 1"
date: 2018-04-18
location: "Honolulu, HI, USA"
---

To prevent users' privacy from leakage, more and more mobile devices employ biometric-based authentication approaches, such as fingerprint, face recognition, voiceprint authentications, etc., to enhance the privacy protection. However, these approaches are vulnerable to replay attacks. Although state-of-art solutions utilize liveness verification to combat the attacks, existing approaches are sensitive to ambient environments, such as ambient lights and surrounding audible noises. Towards this end, we explore liveness verification of user authentication leveraging users' lip movements, which are robust to noisy environments. In this paper, we propose a lip reading-based user authentication system, $LipPass$, which extracts unique behavioral characteristics of users' speaking lips leveraging build-in audio devices on smartphones for user authentication. We first investigate Doppler profiles of acoustic signals caused by users' speaking lips, and find that there are unique lip movement patterns for different individuals. To characterize the lip movements, we propose a deep learning-based method to extract efficient features from Doppler profiles, and employ Support Vector Machine and Support Vector Domain Description to construct binary classifiers and spoofer detectors for user identification and spoofer detection, respectively. Afterwards, we develop a binary tree-based authentication approach to accurately identify each individual leveraging these binary classifiers and spoofer detectors with respect to registered users.

[View presentation slide](http://lynnlilu.github.io/files/INFOCOM-simple.pdf)

