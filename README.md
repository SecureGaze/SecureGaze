# SecureGaze: Defending Mobile Gaze Estimation Against Backdoor Attacks

This repository contains the demo for the SenSys 2025 submission **SecureGaze: Defending Mobile Gaze Estimation Against Backdoor Attacks**. We will make the codes publicly available upon paper acceptance.

## Description
In the video, red and blue arrows represent the gaze directions estimated by the backdoored and the backdoor-mitigated gaze estimation models, respectively. The video shows the subject putting on and removing the physical trigger, i.e., the white tape. When the trigger is absent, both the red and blue arrows correctly reflect the subject's gaze directions. However, when the trigger is present, the red arrow points at the center of the screen, regardless of the actual gaze of the subject. By contrast, the blue arrow continues to correctly follow the subject's gaze. 

This video demonstrates that a simple physical item, such as a piece of white tap, can effectively activate the backdoor behavior, while our method can mitigate it.



## Real-time Video Demo

![Alt Text](https://github.com/SecureGaze/SecureGaze/blob/main/figures/PhysicalAttackDemo.gif)


