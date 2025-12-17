---
layout: project
title: Wind Turbine Blade Design Project
description: Advanced CAD Project
technologies: [Autodesk Fusion, MATLAB programming, LABView ]
image: /assets/images/radio-machine-cad.jpg
---
Project overview: What you were asked to design and why

For a class, we were asked to design and test a small scale wind turbine, intended to be operated at a fixed rotation rate. Our turbine was modelled with code written in MATLAB, and tested over a range of wind speeds in a wind tunnel.

Our design choices were informed by our choice to optimize our turbine for maximum expected power output. Our choice of airfoil was NACA 4412, due to it's high lift to drag ratio, which would assist in maximizing the useful component of the force produced by the blades. The pitch was found by calculating the necessary distribution to allow the blade to operate at it's optimal AOA for our chosen rotation speed and the mostly likely windspeeds. The taper and length of the blade were then chosen to satisfy the maximum power and torque output constraints set by our testing equipment.

Power curves for our turbine were obtained by testing in a wind tunnel and taking data at several wind speeds. At each speed, the resisting torque of a torque brake was steadily increased until from free-spinning until the turbine ceased rotating. The rotation speed and applied torque data was collected during this process, and analyzing this data allowed us to see how the blade's power output varied across wind speed and rotation rate, as well as its power vs. wind speed curve design rotation rate. 

I directly worked on much of the design, modelling and analysis of our blades, and also assisted in experimental data collection and analysis.

![Shaded rendering of earlier version]({{ "/assets/images/radio-machine.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}


![Photo of old radio]({{ "/assets/images/old-radio.jpg" | relative_url }}){: .inline-image-l}
