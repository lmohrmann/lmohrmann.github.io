---
layout: post
title: A joint CTA / KM3NeT analysis
feature-img: "assets/img/research_projects/ctakm3net/ctakm3net_banner.png"
img: "assets/img/research_projects/ctakm3net/ctakm3net_thumb.png"
order: 2
---

#### A joint gamma-ray and neutrino analysis with CTA and KM3NeT

Added: January 23, 2024.

Like [CTA]({% link _research_experiments/cta.md %}) is for gamma-ray astronomy, <a href="https://www.km3net.org" target="_blank">KM3NeT</a> is a major upcoming observatory for neutrino astronomy.
In a new <a href="https://doi.org/10.1140/epjc/s10052-023-12279-z" target="_blank">study appearing in the European Physical Journal C</a>, I have demonstrated with collaborators how one can jointly analyse data from these two facilities in a consistent manner.

The motivation for combining gamma-ray and neutrino data becomes clear when considering that these particles are produced simultaneously in many astrophysical environments.
In fact, whereever cosmic-ray nuclei are accelerated to very high energies, one expects joint production of gamma rays and neutrinos.
They arise from the decay of pions (and other particles) that are created when the cosmic rays undergo interactions with gas, we call this the "pion decay" (PD) scenario.
Gamma rays can also be produced in another way though, namely from accelerated electrons in a process called "inverse-Compton" (IC) scattering.
Crucially, no neutrinos are created in this scenario.

<div><img src="/assets/img/research_projects/ctakm3net/fit_fp_rxj1713.png" alt="Gamma-ray spectrum of RX J1713.7–3946" width="550" align="right" style="padding-top:1%;padding-left:2%;padding-right:2%;padding-bottom:2%"></div>

In our study, we have investigated how one can distinguish between these two scenarios (PD/IC), using several Galactic gamma-ray sources as example.
To do this, we have first fitted spectral models for both scenarios to published gamma-ray flux measurements.
The plot on the right shows this for the supernova remnant RX&nbsp;J1713.7–3946.
Evidently, both models give a decent description of the measured flux points, which already illustrates that it is difficult to distinguish between the PD and IC scenarios with gamma-ray data alone.

With "instrument response functions", which need to be derived from simulations, one can compute how a source corresponding to the fitted models would look like in the CTA and KM3NeT detectors.
We did this for both scenarios and all sources, generating 100 randomised "pseudo experiments" for each case.
We assumed 10 years of detector operation for KM3NeT, and an observation time of 200 hours for each source with CTA.

<div><img src="/assets/img/research_projects/ctakm3net/scan_RXJ1713_1.0.png" alt="Likelihood scan for PD scenario of RX J1713.7–3946" width="550" align="left" style="padding-top:1%;padding-left:2%;padding-right:2%;padding-bottom:2%"></div>

We then analysed these data sets using a combined likelihood analysis to constrain the "hadronic fraction" <i>f</i>, which is the fraction of the total gamma-ray emission that is due to the PD process.
This is shown on the left, again for RX&nbsp;J1713.7–3946, where the input scenario corresponds to <i>f=1</i>, that is, a pure PD scenario.
The quantity on the y-axis, ΔTS, indicates the confidence with which we can reject a certain fraction <i>f</i>.
As intuitively makes sense, the green curve – the result from our combined analysis – increases as this fraction deviates more and more from the input.
The green bands show the statistical spread: among our 100 simulated experiments, by chance some can differentiate between the scenarios better and some worse.

<div><img src="/assets/img/research_projects/ctakm3net/limit_all.png" alt="Credible intervals for hadronic fraction f" width="550" align="right" style="padding-top:1%;padding-left:2%;padding-right:2%;padding-bottom:2%"></div>

Finally, the plot on the right summarises the results we obtained, for all the sources we tested.
The blue and red bands show how the fractions <i>f</i> we obtain in the 100 pseudo experiments are distributed: 68% of the values fall within the broad band, and 90% within the narrow band.
The black intervals on the other hand display an average of the "credible intervals" that we derive from the likelihood analysis for each pseudo experiment.
The smaller these intervals, the better we can constrain the hadronic fraction <i>f</i> for this source.

Paper reference: European Physical Journal C __84__, 112 (2024)<br>
DOI: <a href="https://doi.org/10.1140/epjc/s10052-023-12279-z" target="_blank">10.1140/epjc/s10052-023-12279-z</a><br>
Pre-print: <a href="https://arxiv.org/abs/2309.03007" target="_blank">arXiv:2309.03007</a>
