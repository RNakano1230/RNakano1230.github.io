---
permalink: "/publications/"
title: "Publications"
author_profile: true
---

## Peer-reviewed Journals
{% include base_path %}
{% assign ordered_pages = site.publications | sort:"order_number" %}
<ol>
{% for post in ordered_pages%}
        <li>
            {% include archive-single.html %}
        </li>
{% endfor %}
</ol>

## Conference Proceedings (selected)
<ol>
    <li><strong>Nakano R.</strong> and Hirabayashi M., "Dimorphos' reshaping-induced
        orbital period change after the DART impact."
        <i>53rd Lunar and Planetary Science Conference</i>, The Woodlands, TX, 2022.
        </li>
    <li><strong>Nakano R.</strong> Taheri E., and Hirabayashi M., "Time-Optimal
        and Fuel-Optimal Trajectories for Asteroid Landing via Indirect Optimization."
        <i>AIAA SciTech Forum and Exposition</i>, San Diego, CA, 2022.
        </li>
    <li><strong>Nakano R.</strong> and Hirabayashi M., "Finite element
        thermophysical model for the Yarkovsky and YORP calculations,
        insensitive to small topographic effects."
        <i>AAS Division for Planetary Sciences Meeting</i>, virtual meeting, 2021.
        </li>
    <li><strong>Nakano R.</strong> and Hirabayashi M., "Investigation of
        the YORP effect on asteroid (162173) Ryugu – An application of FEM
        approach thermophysical model."
        <i>Europlanet Science Congress</i>, virtual meeting, 2021, EPSC2021-441.
        </li>
    <li><strong>Nakano R.</strong> and Hirabayashi M., "NASA/Double Asteroid
        Redirection Test: Orbital perturbation by the ejecta-collision driven
        reshaping of Didymos after the impact event.”
        <i>7th IAA Planetary Defense Conference</i>, virtual meeting, 2021.
        </li>
    <li><strong>Nakano R.</strong> and Hirabayashi M., "Finite Element Modeling
        Approach to Characterize Temperature Variations of
        Irregularly Shaped Bodies."
        <i>52nd Lunar and Planetary Science Conference</i>, virtual meeting, 2021.
        </li>
    <li><strong>Nakano R.</strong>, Hirabayashi M., and 10 authors,
        "Dimorphos' orbital perturbation induced by shape modification of
        Didymos after the DART impact."
        <i>American Geophysical Union Fall Meeting</i>, virtual meeting, 2020, NH037-0004.
        </li>
    <li><strong>Nakano R.</strong> and Hirabayashi M., "Mass-shedding Activities
        of Asteroid (3200) Phaethon Enhanced by Its Rotation - Implication to
        Asteroid Pairs."
        <i>Europlanet Science Congress</i>, virtual meeting, 2020, EPSC2020-540.
        </li>
    <li><strong>Nakano R.</strong> and Hirabayashi M., "Mass-shedding Activities
        of Asteroid (3200) Phaethon Enhanced by Its Rotation."
        <i>NASA Exploration Science Forum</i>, virtual meeting, 2020. <br>
        <strong>Student poster competition 1st place</strong>
        </li>
    <li><strong>Nakano R.</strong> and Xu K.G., "Development of a Metronome
        Thrust Stand for Miniature Electric Propulsion."
        <i>AIAA Propulsion and Energy Forum</i>, Cincinnati, OH, 2018.
        </li>
</ol>
