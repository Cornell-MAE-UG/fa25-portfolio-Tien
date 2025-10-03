---
layout: project
title: Actuator Optimization
description: Homework Project in MAE 2020 Statics
technologies: 
image: /assets/images/actuator-cases.png
---

For my Statics homework, I had to design an optimal design with one actuator, one rigid bar, three pins, and a 2D 150cm by 50cm design space that would raise the heaviest weight with the greatest height change. From a provided list of actuators, I chose the IMA55 RN05 because it had the greatest thrust force of 35.81kN. 

I started my design by thinking of how to support the heaviest weight without considering height change. I knew that if I just placed a weight on a vertical bar, there would be no weight limit. 

After, I considered a "limiting" case caused by the actuator. I knew that based on the drawing above, the initial case would tell me the maximum weight I could support.

I then collected my givens, variables, and assumptions to create parametrizations of height change and maximum supported weighted. 

![Some calculations and descriptions]({{ "/assets/images/actuator-parametrization" | relative_url }}){: .inline-image-l}