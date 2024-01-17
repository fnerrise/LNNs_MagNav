# Liquid Neural Networks (Liquid Time-Constant Networks) for Magnetic Navigation (MagNav)

This repository is the official implementation of our associated paper, **"Physics-Informed Calibration of Aeromagnetic
Compensation in Magnetic Navigation Systems using Liquid Time-Constant Networks"**, which was accepted to the NeurIPS 2023 Machine Learning and the Physical Sciences Workshop. Read the paper [here](<https://github.com/fnerrise/LNNs_MagNav/blob/main/SBAQ_LNN_MagNav_NeurIPS23_Paper.pdf>).

Our pipeline contributes the following:
(1) uses a physics-informed neural network, a Liquid Time-Constant network, to capture complex, nonlinear dynamics of airborne MagNav and to detect the weak magnetic anomaly signal from a noisy environment; 
(2) derives the coefficients of known magnetic effects from the airplane that can be used to update a T-L model and improve calibration accuracy.

<p align="center">
  <img width="809" alt="Physics-informed LTC for MagNav" src="https://github.com/fnerrise/LNNs_MagNav/blob/main/SBAQ_LNN_MagNav_NeurIPS23_Thumbnail.png">
</p>

> **Physics-Informed Calibration of Aeromagnetic Compensation in Magnetic Navigation Systems using Liquid Time-Constant Networks**
>
> [Favour Nerrise](mailto:fnerrise@stanford.edu)<sup>1,2</sup>, [Andrew (Sosa) Sosanya]()<sup>2</sup>, [Patrick Neary]()<sup>2</sup>
>
> <sup>1</sup>Department of Electrical Engineering, Stanford University, Stanford, CA, USA<br/>
> <sup>2</sup>SandboxAQ, Palo Alto, CA, USA<br/>
>
> **Abstract:** Magnetic navigation (MagNav) is a rising alternative to the Global Positioning System (GPS) and has proven useful for aircraft navigation. Traditional aircraft navigation systems, while effective, face limitations in precision and reliability in certain environments and against attacks. Airborne MagNav leverages the Earth's magnetic field to provide accurate positional information. However, external magnetic fields induced by aircraft electronics and Earth's large-scale magnetic fields disrupt the weaker signal of interest. We introduce a physics-informed approach using Tolles-Lawson coefficients for compensation and Liquid Time-Constant Networks (LTCs) to remove complex, noisy signals derived from the aircraft’s magnetic sources. Using real flight data with magnetometer measurements and aircraft measurements, we observe up to a 64\% reduction in aeromagnetic compensation error (RMSE nT), outperforming conventional models. This significant improvement underscores the potential of a physics-informed, machine learning approach for extracting clean, reliable, and accurate magnetic signals for MagNav positional estimation.

## Code
Coming soon!

## Acknowledgments
This work was completed at SandboxAQ\footnote{Solving global challenges with AI + Quantum for positive impact. More at \url{sandboxaq.com}.} as a part of the Residency Program. F.N. expresses her profound gratitude to her SandboxAQ team members and peers for their dedicated expertise, mentorship, and support in completing this work. F.N. is also thankful to her research advisors at Stanford University, founding research scientists at Liquid AI, and open-source MagNav-AI collaborators and partners for their scientific and technical contributions that inspired this work.  


## Citation
Coming soon!
```
