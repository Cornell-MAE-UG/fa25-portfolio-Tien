---
layout: project
title: Analysis of a Heat Exchanger
description: Class Assignment
technologies: [N/A]
image: /assets/images/HE_schematic.jpg
---


For my Thermodynamics course, I designed and analyzed how a direct to chip (D2C) cooling system operates. D2C uses conduction to cool computer chips to enhance computing performance. Chip cooling is essential on any scale, from personal computers to AI data centers. 


![Heat Exchanger CV](/fa25-portfolio-Tien/assets/images/D2C_schem.jpeg)

Above is a simplified schematic of a D2C system. 
Components:
Working Fluid: The medium in which heat is transferred. I will be using water in my design.
Cold Plate: Absorbs heat dissipated by a chip through its thermally conductive plate to the working fluid that flows beneath it. I will be using McMaster-Carr Cold Plate 35035K121. 
Heat Exchanger: Re-cools the working fluid to continue heat transfer. I will be using McMaster-Carr Heat Exchanger 3771K14
Chip: I’m using the Intel Xeon Platinum 8180 CPU. I found the dimensions and thermal design power from https://www.intel.com/content/dam/www/public/us/en/documents/guides/xeon-scalable-thermal-guide.pdf



![Heat Exchanger Equations](/fa25-portfolio-Tien/assets/images/analysis.jpeg)

![Heat Exchanger Equations](/fa25-portfolio-Tien/assets/images/numerical.jpg)


I can change the Q_in by increasing the number of passes of the tube. This increases surface area for heat transfer across the tube.


