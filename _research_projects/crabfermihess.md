---
layout: post
title: The size of the Crab Nebula measured with Fermi-LAT and H.E.S.S.
feature-img: "assets/img/research_projects/crabfermihess/crab_banner.png"
img: "assets/img/research_projects/crabfermihess/crab_thumb.png"
order: 1
---

#### A joint _Fermi_-LAT and H.E.S.S. analysis of the Crab Nebula

Added: March 22, 2024.

The Crab Nebula is _the_ most prominent source in the very-high-energy gamma-ray sky.
It was first detected in this regime by the Whipple telescope during 1986–1988, and has been studied in more detail ever since.
The bright gamma-ray emission is produced by high-energy electrons that are constantly being injected into the nebula by an energetic pulsar at its centre, through a process called inverse Compton scattering.
The same electrons also produce radiation at lower energies, in the form of synchrotron radiation emitted in the magnetic field that permeates the nebula.

Because of the complementary energy ranges that they cover, the [H.E.S.S.]({% link _research_experiments/hess.md %}) telescopes and the _Fermi_-LAT satellite experiment are both essential in studying the inverse-Compton component of the Crab Nebula.
In a new <a href="https://doi.org/10.1051/0004-6361/202348651" target="_blank">publication</a> by the H.E.S.S. Collaboration and members of the _Fermi_-LAT Collaboration, co-led by me, we present a new analysis of the Crab Nebula in which we combined data from both instruments.
This has been made possible by a software package called <a href="https://gammapy.org" target="_blank">Gammapy</a>, an openly developed analysis software tool for gamma-ray astronomy.

On the one hand, the combined analysis has allowed us to measure the spectrum of the entire inverse-Compton emission of the Crab Nebula through a single analysis.
The result of this is shown by the light blue, red, and dark blue flux points in the figure below.
The plot also shows measurements of the lower-energy synchrotron radiation, shown by the grey data points.
The lines display predictions of theoretical models of the emission that we have fitted to the data.

<div><img src="/assets/img/research_projects/crabfermihess/combined-spec-v2.png" alt="Spectral energy distribution of the Crab Nebula" width="1000" style="padding-top:1%;padding-left:5%;padding-right:5%;padding-bottom:2%"></div>

On the other hand, we have been able to measure the spatial extension (or size) of the nebula with both instruments in a combined fashion.
While the extension had already been measured by each of the experiments individually, our new analysis provides an energy-resolved measurement for the entire gamma-ray domain.
This is displayed in the left figure below: a clear trend of a decreasing size with increasing energy is evident.
The figure on the right shows this in a more illustrative way: overlaid on an optical (credit: NASA, ESA/Hubble) and X-ray (credit: NASA/CXC/SAO) image of the nebula, the circles indicate the extension measured with _Fermi_-LAT at low gamma-ray energies and with H.E.S.S. at high gamma-ray energies.

<div clear="both" overflow="hidden">
<img src="/assets/img/research_projects/crabfermihess/extensions-raw.png" alt="The size of the Crab Nebula at gamma-ray energies" width="480" float="left" style="padding-top:1%;padding-left:2%;padding-right:2%;padding-bottom:2%">
<img src="/assets/img/research_projects/crabfermihess/extensions-im.png" alt="Optical and X-ray image of the Crab Nebula, with the extension at gamma-ray energies indicated by circles" width="515" float="left" style="padding-top:1%;padding-left:2%;padding-right:2%;padding-bottom:2%">
</div>

Taken together with measurements of the spectrum and extension at lower energies (i.e. of the synchrotron component), these new measurements allow us to constrain how the electrons are distributed within the nebula, and how the magnetic field is structured.
This is shown in the two plots below, which show the spatial extension of the electron distribution and the radial profile of the magnetic field strength in the nebula, for three different models that we tested in our paper.
The "variable _B_-field model", depicted by the black lines, yields the best fit to our data.

<div clear="both" overflow="hidden">
<img src="/assets/img/research_projects/crabfermihess/electron-extensions.png" alt="Spatial extension of electrons in the Crab Nebula" width="500" float="left" style="padding-top:1%;padding-left:2%;padding-right:2%;padding-bottom:2%">
<img src="/assets/img/research_projects/crabfermihess/b-fields.png" alt="Structure of the magnetic field in the Crab Nebula" width="500" float="left" style="padding-top:1%;padding-left:2%;padding-right:2%;padding-bottom:2%">
</div>

Besides that, the analysis also serves as an example case for multi-instrument analyses with Gammapy – an approach that promises new insights for many other gamma-ray sources as well.

<!-- HESS J1809–193 has been selected as the <a href="https://www.mpi-hd.mpg.de/hfm/HESS/pages/home/som/2023/03" target="_blank">March 2023 H.E.S.S. Source of the Month</a>. -->

Paper reference: A&A (forthcoming)<!-- <b>672</b>, A103 (2023)-->.<br>
DOI: <a href="https://doi.org/10.1051/0004-6361/202348651" target="_blank">10.1051/0004-6361/202348651</a><br>
Pre-print: <a href="https://arxiv.org/abs/2403.12608" target="_blank">arXiv:2403.12608</a>
