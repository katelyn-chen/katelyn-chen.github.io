---
layout: single
classes: wide
title: "Wheelchair Lift for Volkswagen ID. Buzz"
excerpt: "Skills: CAD, FEA, prototyping (3D printing/laser cutting), Arduino control, user-centered design"
header:
  image: /assets/images/volkswagen/170-solution.png
  teaser: assets/images/volkswagen/170-solution.png
sidebar:
  - title: "Role"
    text: "Mechanical Engineer, full ownership of the scissor lift and platform subsystem"
  - title: "Team Members"
    text: "Isabella Correa, Joseph Garcia, Chloe Ha, Khandaker Aqib"

  - title: "Responsibilities"
    text: "User research, hardware design, CAD & FEA analysis, prototyping, mechatronics design and electrical integration"   
  - title: "Skills"
    text: "CAD, FEA, prototyping (3D printing/laser cutting), Arduino control, user-centered design"
---
## Challenge
- Millions of individuals with mobility impairments face barriers to independent vehicle access
- Existing solutions (ramps, aftermarket lifts) are **costly, bulky, and hard to integrate** into production vehicles
- The Volkswagen ID Buzz has a battery pack in the car floor, limiting available integration space
- Goal: Design a **factory-integrated, ADA-compliant wheelchair entry system** for the Volkswagen ID. Buzz, enabling independent deployment without compromising aesthetics, car functionality, or safety

<p align="center">
  <img src="/assets/images/volkswagen/170-userinterview.png" alt="User Interview" width="500"><br>
  <em style="font-size:0.9em;">User interview to understand and test current market solutions</em>
</p>

## Action
- Designed an **automated 0º-90º-0º folding scissor lift platform integrated into the car door**
<p align="center">
  <img src="/assets/images/volkswagen/170-steps.png" alt="Theory of Operation" width="600"><br>
  <em style="font-size:0.9em;">Theory of operation for the wheelchair lift</em>
</p>
- **Platform & Scissor Lift Subsystem:** Designed a scissor lift system driven by a button-controlled motorized lead screw
  - Experimentally determined input torque requirement (20.6 Nm at 315 lbs load) to scope a 30 Nm right angle gearbox and motor system.
  - Conducted calculations validated with FEA to select a 0.19'' thick Aluminum 6061 platform to minimize weight and deflection (less than 3 degrees).
  - Dimensions are fully ADA-compliant at 50% scale

<p align="center">
  <img src="/assets/images/volkswagen/170-scissorlift.png" alt="Scissor Lift and Platform" width="600"><br>
  <em style="font-size:0.9em;">Scissor lift deploys from below the platform through a motorized lead screw mechanism</em>
</p>

- **Platform Stowing Subsystem:** Two linear actuators drive the 0º-90º-0º folding and unfolding motion of the platform
  - Prototyped door-to-platform connection through experimental testing to design a laser-cut steel tab, PLA wedge, and iron L-bracket assembly
  - Linear actuators hold the platform at the "levitated" 90º open position
<p align="center">
  <img src="/assets/images/volkswagen/170-fold.png" alt="Platform Stowing" width="600"><br>
  <em style="font-size:0.9em;">Platform unfolds and folds from 0º to 90º to 0º</em>
</p>
- Engineering Validation:  
  - Conducted FEA for stress, deflection, and factor of safety across components.  
  - Performed FMEA to identify and mitigate failure risks.  
  - Built and tested a 50% scale prototype mounted on a wooden vehicle frame.  

## Result
- Built **fully operational automated lift** supporting **300+ lbs** and adhering completely to strict ADA requirements at 50% scale
<p align="center">
  <video width="600" controls>
    <source src="/assets/images/volkswagen/170-video.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video><br>
  <em style="font-size:0.9em;">Demonstration of a person using the wheelchair lift</em>
</p>

- Demonstrated feasibility of a **factory-integrated and modular accessibility solution** for the Volkswagen ID. Buzz.  
- Future Work:  
  - Reinforce custom parts with higher-grade materials
  - Integrate automatic door-opening and safety barriers
  - Full-scale testing under real-world loading and durability conditions
- For more information about the project, read our full report here: [Stanford Libraries Archive](https://purl.stanford.edu/mf699hk2234)