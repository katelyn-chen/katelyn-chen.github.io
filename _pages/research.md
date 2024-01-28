---
permalink: /research/
entries_layout: grid
classes: wide

layout: single
title: "Undergraduate Research"
header:
  image: /assets/images/armlab/armlab-group-2.JPG
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
## Stanford Assistive Robotics and Manipulation Laboratory (ARMLab)
**Trajectory and Sway Prediction for Fall Prevention**

**Research Goals:**
*  "Develop a wearable sensor that can predict a person's path and their stability over the expected path, alerting them if there is a significant possibility they may fall or become unstable" ([Project Overview](https://arm.stanford.edu/research/smart-belt-human-motion-prediction-and-fall-prevention-wearable-sensor))
* Led by Monroe Kennedy III (PI) and Ken Wang (PhD researcher) in the [ARMLab](https://arm.stanford.edu)

**My Role:**
* Selected to participate in the Department of Mechanical Engineering 2023 Stanford Undergraduate Research Institute (SURI) as 1/30 undegraduate students for a 10 week research internship
* Continuing to work in the ARMLab during the school year! 

<!-- ![ARMLab Group Photo](/assets/images/armlab/armlab-group-2.jpg){:width="800"} -->

**My Work:**
* Developed an iOS application in Swift (programming language) that leverages the LiDAR sensor in iPhones to collect environment data and generate a depth panorama 
* Application demo (below) shows the generation of the depth panorama in real time as a person walks down a hallway. The FPS on the screen needs to be multiplied by the number of GPUs (6 for the iPhone 12 Pro that the testing was conducted on)

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/cSA3S8FV828?si=2mrDZ6AVUrMztgIU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

* The depth panorama is used as input to a VAE/LSTM trajectory and sway prediction model, which will eventually be deployed directly on the phone
* Currently working on deploying the PyTorch model in the iPhone and designing an ergonomic/aesthetically pleasing phone harness

![Research Poster](/assets/images/armlab/SURI_Poster.pdf){:width="800"}

**Research Presentations:**

* **SURI Poster Session, August 2023**: Presented summer research progress to Stanford mechanical engineering labs and the SURI cohort 

{% include gallery id="gallery-suri" %}

* **Innovation and Discovery Expo, October 2023**: Presented to biosciences, engineering, and medical researchers as part of the ARMLab demonstrational booth. The expo was hosted by Stanford Bio-X and Wu Tsai Human Performance Alliance.

{% include gallery id="gallery-wutsai" %}

<!-- 
---
title: Research
permalink: /research/
entries_layout: grid
classes: wide -->

<!-- ## Stanford Intelligent and Interactive Autonomous Systems Group (ILIAD)
**Dexterous Manipulation for Robot Assisted Feeding**

Research Purpose:
* Led by Dorsa Sadigh (PI) and Priya Sundaresan (PhD researcher) in [Stanford ILIAD](https://iliad.stanford.edu)

My Role:
* Selected for Paid Undergraduate Research Experience (PURE) during Spring 2023 in the Computer Science Department

My Work:
*  -->