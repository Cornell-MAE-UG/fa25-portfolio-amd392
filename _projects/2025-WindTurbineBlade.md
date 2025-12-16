---
layout: project
title: Wind Turbine Blade
description: Fluid Mechanics and CAD Project
technologies: [Autodesk Fusion, Wind Tunnel]
image: /assets/images/BladeDesign.jpg
---

Project Overview: We were tasked with designing the blades of a small-scale wind turbine, meant to operate at a fixed angular velocity. Our design constraints included that it must be less than 6 inches in length, compatible with a standard hub piece that was 1 inch in radius, and must operate below 2000 RPM.

Design Process: The primary objective of the design was to identify a blade geometry that maximizes power output at a fixed angular velocity by operating near the optimal tip speed ratio. This objective is addressed by selecting blade parameters that maximize the power coefficient while remaining within the torque and structural limitations. We chose to make our turbine blades the maximum length and start with the maximum chord length at the hub, then adjusted twist and taper based on a MATLAB model we developed to predict wind turbine blade performance. Our design used a linearly tapered chord length to ensure the structural stability of the blade, as well as linearly changing twist in order to adjust for the change in effective velocity vector as distance increases from the hub.

![Image of blade in wind tunnel]({{ "/assets/images/BladeTesting.jpg" | relative_url }}){: .inline-image-r style="width: 200px"}

Testing: We assessed the performance of our wind turbine blade design by obtaining as many power curves as possible in between the minimum flow velocity at which the blades start spinning and the point at which around the wind turbine blades are spinning at 1800 RPM with high torque already applied. We increased the wind tunnel frequency in 1 Hz intervals between power curves and made sure to only collect data points while increasing the torque break voltage (in 0.2 V increments) in order to account for hysteresis. As we approached our 2000 RPM limit, with increasing wind tunnel velocity, we made sure to increase the minimum torque break voltage so that the power curves would start at around 1800 RPM and decrease as we increased torque. 

![Power Curves]({{ "/assets/images/BladePowerCurves.jpg" | relative_url }}){: .inline-image-l}

My Contributions: While I also played a role in the design parameter selection process, my primary contribution was in the development of the experimental wind turbine blade testing protocol. Specifically, I wrote and revised the testing and safety procedures. Additionally, during wind turbine testing, I used the LabView interface to collect data points and control the magnetic torque break voltage.

