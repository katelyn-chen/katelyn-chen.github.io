---
layout: single
title: "Shape Optimized Hanging Bedside Shelf"
excerpt: "Skills: FEA, CAD, 3D Printing"
header:
  image: /assets/images/shelf/float-title-2.png
  teaser: assets/images/shelf/float-title-2.png
sidebar:
  - title: "Role"
    # image: http://placehold.it/350x250
    # image_alt: "logo"
    text: "Individual project"
  - title: "Responsibilities"
    text: "Design, prototype, conduct similuations, and print the final product"
  - title: "Skills"
    text: "Finite Element Analysis (FEA), CAD, algorithmic design, 3D printing"
# gallery-machine:
#   - url: /assets/images/shelf/cad-before.png # 1600 x 1068
#     image_path: assets/images/shelf/machine-1-th.jpg # 600 x 400
#   - url: /assets/images/shelf/machine-2.jpg
#     image_path: assets/images/shelf/machine-2-th.jpg
#   - url: /assets/images/shelf/machine-3.jpg
#     image_path: assets/images/shelf/machine-3-th.jpg
#   - url: /assets/images/sandcasting-4.jpg
#     image_path: assets/images/sandcasting-4-th.jpg
---

The goal of the project was to use algorithmic modeling tools to design a part unique to additive manufacturing that optimizes for weight without sacrificing performance.

![Final](/assets/images/shelf/demo.png){:width="800"}


## Ideation and Concept Sketches
* Mechanical Function: Hang over a surface and support weight without breaking
* User: Students living in dorms
* Use Case: People with lofted beds may find it difficult to turn off the light then navigate to their bed in the dark when going to sleep and also don’t have anywhere to place their phone around the bed, so the hanging bedside table can hold a night light, phone, and earbuds.

![Sketch](/assets/images/shelf/sketch.png){:width="800"}

## Force Analysis
Free body diagrams were used to determine the force that will be applied on the shelf.

![FBD](/assets/images/shelf/force.png){:width="800"}

## Prototyping (Algorithmic Modeling and Static Stress Simulation)
Three rounds of shape optimization was carried out before the first printed prototype:

![Shape Optimization Iteration](/assets/images/shelf/iterations.jpg){:width="800"}

Each promoted mesh had a mass ratio of around 40%. After the shape optimization, the design was updated to match the mesh. A static stress study is then used to verify the performance. These steps are repeated until the safety factor reaches ~5. 

![Printed Prototype](/assets/images/shelf/prototype.png){:width="800"}

## Final Design
The final design had a safety factor of 5 under normal use and 2 under improper use (20N applied directly to the surface) and the mass was 35% of the original design.

![CAD Before](/assets/images/shelf/cad-before.png){:width="800"}

![Stress Original](/assets/images/shelf/stress-og.png){:width="800"}

![Shape Optimization](/assets/images/shelf/shape-op.png){:width="800"}

![CAD After](/assets/images/shelf/cad-after.png){:width="800"}

![Stress Normal](/assets/images/shelf/stress-normal.png){:width="800"}

![Stress Improper](/assets/images/shelf/stress-improper.png){:width="800"}




