---
title: "Dynamics modeling of binary asteroid systems"
collection: research
permalink: /research/F2BP
image1_F2BP: /images/research/binarySystem_traj.png
order_number: 2
date: 2001-01-01 00:00:00
---
---
The mutual dynamics of irregularly shaped gravitating bodies is different from the regular two-body dynamics because of complex gravity interactions. This is often known as the Full-Two Body Problem (F2BP). Modeling the mutual dynamics usually requires extensive simulation burden.

To study dynamics of binary asteroid systems, I developed a [F2BP simulation package](/software). This model uses a linear Finite Element Model (FEM) shape function and does not require order truncation for the mutual gravity computation. (More details: [Yu et al., 2019](https://link.springer.com/article/10.1007%2Fs10569-019-9930-4))

Using this package, I have been studying asteroid (65803) Didymos system, which is a target asteroid for NASA's [DART](https://dart.jhuapl.edu/) mission. For example, combining the knowledge from [structural analysis](/research/structuralAnalysis), I am investigating how shape deformation of Didymos (primary) or Dimorphos (secondary) could affect the mutual dynamics.

<p style="text-align:center">
    <img src="/images/research/Didymos_traj.gif" width="450"/><br>
    Didymos system's mutual orbit
</p>

Because FEM approaches are also used for other applications such as structural and [thermophysical](/research/thermophysicalModeling) analyses, this package can be combined with other FEM models to investigate complicated, coupled dynamical evolutions (e.g., [Binary-YORP effect](/research/BYORP)).

---
<font size="3"> Related publications:</font>
<font size="3">
    <ol>
        <li><strong>Nakano R.</strong> and Hirabayashi M., "NASA/Double Asteroid Redirection Test: Orbital perturbation by the ejecta-collision driven reshaping of Didymos after the impact event.” <i>7th IAA Planetary Defense Conference</i>, virtual meeting, 2021.
        </li>
        <li><strong>Nakano R.</strong>, Hirabayashi M., and 10 colleagues, "Dimorphos' orbital perturbation induced by shape modification of Didymos after the DART impact." <i>American Geophysical Union Fall Meeting</i>, virtual meeting, 2020, NH037-0004.
        </li>
    </ol>
</font>
