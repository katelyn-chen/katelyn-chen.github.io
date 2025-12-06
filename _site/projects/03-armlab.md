<!-- ---
layout: single
classes: wide
title: "Trajectory and Sway Prediction for Fall Prevention"
excerpt: "Skills: Swift, Python"
header:
  image: /assets/images/armlab/smartbelt.pdf
  teaser: assets/images/armlab/smartbelt.pdf
sidebar:
  - title: "Position"
    # image: http://placehold.it/350x250
    # image_alt: "logo"
    text: "Stanford ARMLab Researcher"
  - title: "Collaborators"
    text: "Ken Wang (PhD), Monroe Kennedy III (PI)"
  - title: "Responsibilities"
    text: "Develop an iOS application for data collection and depth panorama generation"
  - title: "Skills"
    text: "Swift, Python"

gallery-suri:
  - url: /assets/images/armlab/suri-1.jpg # 1600 x 1068
    image_path: assets/images/armlab/suri-1-th.jpg # 600 x 400
  - url: /assets/images/armlab/suri-2.jpg
    image_path: assets/images/armlab/suri-2-th.jpg
  - url: /assets/images/armlab/suri-3.jpg
    image_path: /assets/images/armlab/suri-3-th.jpg

gallery-wutsai:
  - url: /assets/images/armlab/wutsai-1.jpg # 1600 x 1068
    image_path: assets/images/armlab/wutsai-1-th.jpg # 600 x 400
  - url: /assets/images/armlab/wutsai-2.jpg
    image_path: assets/images/armlab/wutsai-2-th.jpg
  - url: /assets/images/armlab/wutsai-3.jpg
    image_path: /assets/images/armlab/wutsai-3-th.jpg
---

**Challenge**
* Conducted research with the [Stanford Assistive Robotics and Manipulation Laboratory (ARMLab)](https://arm.stanford.edu) to develop a wearable sensor that can predict a person's path and stability, then alert them of possibile falls in real time. 
  * Intended users are older individuals who are at higher risk of instability and falls.
* Prior data collection setup involved multiple pieces of hardware. I aimed to simplify the setup by reducing the number of parts while maintaining performance.
<!-- ![ARMLab Group Photo](/assets/images/armlab/armlab-group-2.jpg){:width="800"} -->

**Action**
<!-- * Selected to participate in the Department of Mechanical Engineering 2023 Stanford Undergraduate Research Institute (SURI) as 1 of 30 undegraduate students for a 10 week research internship -->
* Developed an iOS application in Swift (programming language) that leverages the LiDAR sensor in iPhones to collect environment data and generate a depth panorama 
  * The depth panorama is used as input to a VAE + LSTM trajectory and sway prediction model


**Result**
* Application demo (below) shows the generation of the depth panorama in real time as a person walks down a hallway. The FPS on the screen needs to be multiplied by the number of GPUs (6 for the iPhone 12 Pro that the testing was conducted on)

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/cSA3S8FV828?si=2mrDZ6AVUrMztgIU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

* PyTorch prediction model has been converted to CoreML and will eventually be deployed on the iPhone for an integrated data collection and prediction process

**Research Presentations**
* **SURI Poster Session, August 2023**: Presented summer research progress to Stanford mechanical engineering labs and the SURI cohort 
  {% include gallery id="gallery-suri" %}
* **Innovation and Discovery Expo, October 2023**: Presented to biosciences, engineering, and medical researchers as part of the ARMLab demonstrational booth. The expo was hosted by Stanford Bio-X and Wu Tsai Human Performance Alliance.
  {% include gallery id="gallery-wutsai" %}

![Research Poster](/assets/images/armlab/SURI_Poster.pdf){:width="800"} -->
