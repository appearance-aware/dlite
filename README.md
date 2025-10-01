# ∂LITE: Differentiable Lighting-Informed Trajectory Evaluation for On-Orbit Inspection

[![Project Page](https://img.shields.io/badge/Project-Page-blue)](https://appearance-aware.github.io/dlite-iac/)
[![IAC 2025](https://img.shields.io/badge/IAC-2025-green)](https://www.iafastro.org/events/iac/iac-2025/)

This repository contains the project website for **∂LITE**, an end-to-end differentiable simulation pipeline for on-orbit inspection operations.

## Abstract

Visual inspection of space-borne assets is of increasing interest to spacecraft operators looking to plan maintenance, characterise damage, and extend the life of high-value satellites in orbit. The environment of Low Earth Orbit (LEO) presents unique challenges when planning inspection operations that maximise visibility, information, and data quality.

Specular reflection of sunrays from spacecraft bodies, self-shadowing, and dynamic lighting in LEO significantly impact the quality of data captured throughout an orbit. This is exacerbated by the relative motion between spacecraft, which typically introduces variable imaging distances and attitudes during inspection. Planning inspection trajectories via simulation is a common approach. However, the ability to design and optimise an inspection trajectory specifically for the resulting quality of imaging data in proximity operations remains largely unexplored.

In this work, we present **∂LITE**, an end-to-end differentiable simulation pipeline for on-orbit inspection operations. We leverage state-of-the-art differentiable rendering tools and a custom orbit propagator to enable end-to-end optimisation of orbital parameters based on visual measurements. ∂LITE enables us to optimise for non-obvious trajectories, vastly improving the quality and usefulness of attained data. To our knowledge, our differentiable inspection-planning pipeline is the first of its kind and provides new insights into modern computational approaches to spacecraft mission planning.

## Citation

If you find ∂LITE useful for your research, please cite:

```bibtex
@article{naylor2025dlite,
  author = {Naylor, Jack and Mishra, Raghav and Barbara, Nicholas and Dansereau, Donald G.},
  title = {$\partial${LITE}: Differentiable Lighting-Informed Trajectory Evaluation for On-Orbit Inspection},
  journal = {IAF 76th International Astronautical Congress (IAC) Space Operations Symposium},
  organization = {International Astronautical Federation},
  year = {2025},
}
```

## Authors

- **Jack Naylor** - *Australian Centre for Robotics, University of Sydney* - [jack.naylor@sydney.edu.au](mailto:jack.naylor@sydney.edu.au)
- **Raghav Mishra** - *University of Sydney & ARIAM Hub* - [raghav.mishra@sydney.edu.au](mailto:raghav.mishra@sydney.edu.au)
- **Nicholas H. Barbara** - *Australian Centre for Robotics, University of Sydney* - [nicholas.barbara@sydney.edu.au](mailto:nicholas.barbara@sydney.edu.au)
- **Donald G. Dansereau** - *University of Sydney & ARIAM Hub* - [donald.dansereau@sydney.edu.au](mailto:donald.dansereau@sydney.edu.au)

## Affiliations

1. **Australian Centre for Robotics and School of Aerospace, Mechanical and Mechatronic Engineering**, The University of Sydney, NSW, 2006, Australia
2. **Australian Robotic Inspection and Asset Management (ARIAM) Hub**, The University of Sydney, NSW, 2006, Australia

*Corresponding Author: Jack Naylor

## Acknowledgments

The authors gratefully acknowledge support from the NSW Space Research Network to present this work. This research was supported in part through the NVIDIA Academic Grant Program. This work was supported in part by the ARC Research Hub in Intelligent Robotic Systems for Real-Time Asset Management (IH210100030).

## License

This project website is based on the [Nerfies](https://github.com/nerfies/nerfies.github.io) template and is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a>
