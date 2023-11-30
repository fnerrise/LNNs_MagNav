# Liquid Neural Networks (Liquid Time-Constant Networks) for Magnetic Navigation (MagNav)

This repository is the official implementation of our associated paper, **"Physics-Informed Calibration of Aeromagnetic
Compensation in Magnetic Navigation Systems using Liquid Time-Constant Networks"**, which was accepted to the NeurIPS 2023 Machine Learning and the Physical Sciences Workshop. Pre-print link is coming soon (see attached PDF for now). 

Our pipeline contributes the following:
1) A physics-informed Liquid Time-Constant network that integrates Tolles-Lawson compensation coefficients to better learn higher-order, nonlinear dynamics of airborne MagNav.
2) Determines additive correction to classical Tolles-Lawson coefficients of known magnetic effects from the airplane that can be used to detect the target, weak magnetic anomaly signal from a noisy environment.

<p align="center">
  <img width="809" alt="Physics-informed LTC for MagNav" src=" ">
</p>

> **Physics-Informed Calibration of Aeromagnetic Compensation in Magnetic Navigation Systems using Liquid Time-Constant Networks**
>
> [Favour Nerrise](mailto:fnerrise@stanford.edu)<sup>1,2</sup>, [Sosa Sosanya]()<sup>2</sup>, [Patrick Neary]()<sup>2</sup>
>
> <sup>1</sup>Department of Electrical Engineering, Stanford University, Stanford, CA, USA<br/>
> <sup>2</sup>SandboxAQ, Palo Alto, CA, USA<br/>
>
> **Abstract:** Magnetic navigation (MagNav) is a rising Global Positioning System (GPS) alternative that has proven useful for aircraft navigation. Traditional aircraft navigation systems, while effective, face limitations in precision and reliability in certain environments. Airborne MagNav leverages the Earth's magnetic field to provide accurate positional information. However, external magnetic fields induced by aircraft electronics and Earth's large-scale magnetic fields disrupt the weaker signal of interest. We introduce a physics-informed approach using Tolles-Lawson coefficients for compensation and Liquid Time-Constant Networks (LTCs) to remove complex, noisy signals derived from the aircraft’s own magnetic sources. Using real flight data with magnetometer measurements and aircraft measurements, we observe up to a 64\% reduction in aeromagnetic compensation error (RMSE nT), outperforming conventional models. This significant improvement underscores the potential of LTCs for extracting clean, reliable, and accurate magnetic signals for MagNav positional estimation.

## Code
Coming soon!

## Acknowledgments
This work was completed at SandboxAQ as a part of a Residency Program. F.N. expresses her profound gratitude to her team members, fellow residents, and mentors at SandboxAQ for their dedicated expertise and guidance in supporting this work. 


## Citation
Coming soon!
```
