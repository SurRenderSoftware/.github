# SurRender software client interface

The SurRender software is a powerful image renderer developed by the Image Processing Advanced Studies team of Airbus Defence & Space.
It is specially designed for space applications such as vision-based navigation (planetary approach and landing, in orbit rendezvous, etc.). 
It uses raytracing (CPU) or openGL (GPU) and it is highly optimized for space simulations (sparse scenes, reflections and shadows, large distance dynamics, huge datasets). 
Users can input various data at standard formats (Digital Elevation Models, images, meshes), and configure models for various properties such as materials and sensors (shutter type, noises, integration time, etc.). SurRender simulations aim at physical representativeness as needed for the development and validation of  computer vision algorithms.

# Licence
The *SurRender server* (rendering engine) in a commercial software owned by Airbus Defence & Space SAS (France). 
Potential users are invited to contact surrender.software@airbus.com to enquiry about our licensing options (commercial, academic, student, ...)

This GitHub project offers access to the *SurRender client* (user API) and to a collection of demonstrations scripts.

This project is licensed under the Apache License Version 2.0 of January 2004. See the LICENSE file for details.
(C) 2019 Airbus copyright all rights reserved

## References
Information about the software is available at <https://www.airbus.com/en/products-services/space/exploration/moon#surrender>, and in two conference articles: https://arxiv.org/abs/1810.01423 and https://arxiv.org/abs/2106.11322v1
Documentation provided with the software include a User Manual and developer documentation (Doxygen).
