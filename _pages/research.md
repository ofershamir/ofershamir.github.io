---
permalink: /research/
title: "Research"
author_profile: true
---

<p class="research-introduction">
  My research lies at the intersection of atmospheric and climate dynamics,
  geophysical fluid dynamics, and applied mathematics. I use analytic theory,
  observations, stochastic and statistical methods, and numerical models of
  varying complexity to investigate how organized variability arises and how
  faithfully it is represented. A recurring aim is to make assumptions about
  complex geophysical systems explicit and testable, whether those assumptions
  concern wave structure, model approximation, statistical homogeneity, random
  variability, or data-driven parameterization.
</p>

<nav class="research-index" aria-label="Research themes">
  <a href="#waves-on-the-sphere">
    Waves, instabilities, and forced dynamics on the sphere
  </a>
  <a href="#organized-atmospheric-variability">
    Organized atmospheric variability
  </a>
  <a href="#climate-model-development">
    Climate model development and evaluation
  </a>
  <a href="#beyond-state-distributions">
    Beyond state distributions
  </a>
</nav>

<section class="research-theme" id="waves-on-the-sphere">
  <div class="research-heading" markdown="1">

## Waves, instabilities, and forced dynamics on the sphere

  </div>

  <figure class="research-figure research-figure--transparent">
    <img
      src="/assets/images/research-waves-1.png"
      alt="Atmospheric wave structures on the sphere"
    >
    <figcaption>
      As the Reynolds number increases (to the right), the vorticity becomes more intermittent, with a small number of intense vortex cores emerging from a weaker filamentary background.
    </figcaption>
  </figure>

  <div class="research-copy" markdown="1">

Waves and instabilities provide a fundamental framework for understanding atmospheric and oceanic motion, but familiar theories often rely on local approximations, asymptotic limits, or restricted parameter regimes. My research has developed and used global solutions of the shallow-water equations to examine how these structures behave on the rotating spherical Earth. This work includes classifying planetary-wave solutions, deriving asymptotic approximations, quantifying the stability of zonal jets across dynamical approximations, and extending the Matsuno–Gill framework beyond its conventional regime. Together, these studies establish when familiar descriptions remain valid, identify where they fail, and reveal how spherical geometry and divergent dynamics alter atmospheric responses.

<!-- [Related publications](/publications/) -->

  </div>

  <a href="#" class="research-back-to-top">↑ Top</a>
</section>

<section class="research-theme" id="organized-atmospheric-variability">
  <div class="research-heading" markdown="1">

## Organized atmospheric variability

  </div>

  <figure class="research-figure research-figure--transparent">
    <img
      src="/assets/images/research-spectra-2.png"
      alt="Tropical wavenumber-frequency spectrum"
    >
    <figcaption>
      Tropical wavenumber–frequency spectrum, adapted from Wheeler and Kiladis (1999).
    </figcaption>
  </figure>

  <div class="research-copy" markdown="1">

Atmospheric spectra contain recognizable waves and other organized structures embedded in a broad background of variability across spatial and temporal scales. Interpreting these spectra requires determining which features reflect distinct dynamics and which can arise from turbulence or random fluctuations. Across this work, I have examined several sources of atmospheric organization. I have shown how nonlinear wave interactions generate large-scale tropical variability and contribute to the observed concentration of power near theoretical wave modes. I have also established a pervasive preference for meridionally symmetric variability and investigated its origins in forcing, nonlinear interactions, eigenstructures, and the statistics of random fields. Extending this inquiry to stochastic variability, I have developed a physics-based model of Earth’s infrared background that provides an objective null hypothesis for identifying organized signals in outgoing longwave radiation.

  </div>

  <figure class="research-figure research-figure--transparent research-figure--secondary">
    <img
      src="/assets/images/research-spectra.png"
      alt="Angular power spectrum of global-scale outgoing longwave radiation"
    >
    <figcaption>
      Angular power spectrum of global-scale outgoing longwave radiation.
    </figcaption>
  </figure>

  <!-- [Related publications](/publications/) -->

  <a href="#" class="research-back-to-top">↑ Top</a>
</section>

<section class="research-theme" id="climate-model-development">
  <div class="research-heading" markdown="1">

## Climate model development and evaluation

  </div>

  <div class="research-copy" markdown="1">

Climate models represent interacting processes across a wide range of scales, making it essential to determine whether an apparently realistic simulation is produced by the correct dynamics. My research has addressed this problem through quantitative model tests, model hierarchies, and controlled perturbation experiments. I developed spectral shallow-water solvers based on physically relevant wave eigenfunctions and analytic test cases that provide demanding quantitative evaluations of global dynamical cores. Another focus of this research is whether data-driven gravity-wave parameterizations trained in one environment remain reliable when coupled to a biased model or applied under a different climate.

<!-- This question forms part of my broader interest in the representation of gravity-wave forcing and the quasi-biennial oscillation in climate models. -->

The figures below show how optimal transport can correct biases in gravity-wave source distributions, allowing the expected QBO amplitude and period to be recovered.

  </div>

  <div class="research-figure-pair">
    <figure class="research-figure research-figure--transparent research-figure--paired">
      <div class="research-figure__media">
        <img
          src="/assets/images/research-models-1.png"
          alt="Observed, biased, and optimally corrected gravity-wave source distributions"
        >
      </div>
      <figcaption>
        Optimal-transport correction of biased gravity-wave source distributions.
      </figcaption>
    </figure>
    <figure class="research-figure research-figure--transparent research-figure--paired">
      <div class="research-figure__media">
        <img
          src="/assets/images/research-models-2.png"
          alt="QBO simulations with biased and corrected gravity-wave sources"
        >
      </div>
      <figcaption>
        QBO simulations with biased and corrected gravity-wave sources.
      </figcaption>
    </figure>
  </div>

  <!-- [Related publications](/publications/) -->

  <a href="#" class="research-back-to-top">↑ Top</a>
</section>

<section class="research-theme" id="beyond-state-distributions">
  <div class="research-heading" markdown="1">

## Beyond state distributions

  </div>

  <div class="research-copy" markdown="1">

Conventional statistical descriptions of climate variability emphasize which states occur and how frequently they occur, providing only a partial account of the underlying dynamics. For example, a state distribution may indicate distinct cold and warm climate regimes while revealing little about the dynamics connecting them. My emerging research explores how data-driven methods can characterize climate state space more fully by recovering information about both its structure and its evolution. I am investigating whether this broader perspective can reveal dynamical model biases that remain hidden when observations and simulations are compared using conventional climate statistics alone.

  </div>

  <figure class="research-figure research-figure--square">
    <img
      src="/assets/images/research-probability.jpg"
      alt="Conceptual climate state space with cold and warm regimes connected by directional pathways"
    >
    <figcaption>
      Conceptual illustration of climate-state occupancy and dynamical evolution.
      State distributions identify frequently occupied regimes, while the
      pathways between them contain additional dynamical information.
    </figcaption>
  </figure>

  <a href="#" class="research-back-to-top">↑ Top</a>
</section>
