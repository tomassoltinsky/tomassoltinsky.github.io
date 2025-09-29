---
layout: archive
title: "What is my research about?"
permalink: /research/
author_profile: true
redirect_from:

---

Epoch of Reionization and Cosmic Dawn, 21-cm cosmology, Ly$$\alpha$$ forest,  <br/>
cosmological simulations, intergalactic medium, supermassive black holes

{% include base_path %}

## 21-cm forest in the late reionization models

<video width="900" height="450" controls loop="" muted="" autoplay="">
  <source src="https://github.com/tomassoltinsky/tomassoltinsky.github.io/raw/master/images/21-cm_animation.mp4">
</video>

The 21-cm forest signal is a series of absorption features in the spectra of distant radio-loud sources, such as quasars, arising from neutral hydrogen structures between the observer and the source (the bottom panel in the animation above and the top left panel in the figure below). As the light emitted from such sources travels through the universe, it redshifts (its wavelength becomes longer). Some photons redshift to the wavelength of $$\sim21.11\,\rm cm$$ (blue vertical stripe) and might encouter cold and neutral hydrogen gas which absorbs some of these 21-cm photons. This leaves an absorption feature in the spectrum of the background source. The rest of the light travels further and different set of photons redshifts to the 21-cm wavelength and gets absorbed by the neutral hydrogen gas. The amount of the photons that gets absorbed depends on various things, including the density (the top panel) of the Intergalactic medium (IGM) and its ionization (the second panel) and thermal (the third panel) state.

![21cmforest_P1D_schematic](/images/21cmforest_P1D_schematic.png)

The reionization, is the last phase transition of our universe, when the light emitted by the first stars and galaxies turned the universe from neutral to ionized. The whole processes was initiated $$\sim13.5$$ billion years ago and lasted for $$\sim1$$ billion years. It can be described with a creation of ionization bubbles around the galaxies which then expanded and overlapped until they filled in the whole universe. Given that the 21-cm forest is sensitive to how neutral and how warm the IGM is, the 21-cm forest can be used to explore how the reionization has progressed. Towards the end of reionization the 21-cm signal is expected to be diminished because the neutral hydrogen, which is needed for this signal, is depleted. Fortunately, recent observations seem to suggest that the reionization was completed significantly later. This will make the observations of the 21-cm forest signal easier in the future. In my research I model the 21-cm forest signal in this late-reionization scenario using cosmological simulations like the Sherwood-relics simulation suite or 21cmFAST to see how plausible the detection of this signal is with both already operational and future telescopes and explore the potential of such observations to constrain the IGM properties during the reionization. You can find more in [Šoltinský et al. 2021](https://tomassoltinsky.github.io//publication/Soltinsky_2021_file).

Besides the above mentioned advancements on the theoretical front in this field, the prospects of detecting the 21-cm forest have improvement thanks to the observational efforts too. Particularly, the number of identified radio-loud quasars at high redshift has increased significantly in recent years (see my [EoR page](https://tomassoltinsky.github.io//eor/) where I keep track of this). Furthermore, statistical observables of the 21-cm forest have been developed in this decade which decrease the observational requirements for the detection of this signal. For instance, the 1D power spectrum of the 21-cm forest is shown as the solid orange curve in the bottom left panel of the figure above. Note that at low $$k$$ (i.e. large scales), the signal is above the noise limit (dashed fuchsia curves) which means that the signal might be detectable with the upgraded Giant Metrewave Radio Telescope (uGMRT) and/or Square Kilometre Array (SKA) telescopes. In the right panel I show how such observations can constrain the ionization and thermal state of the cold and neutral IGM, which is still largely unexplored. For more details see [Šoltinský et al. 2025](https://tomassoltinsky.github.io//publication/Soltinsky_2025_file).

We have also applied machine learning techniques to improve our parameter inference from the 21-cm forest signal in [Patil et al. 2025](https://tomassoltinsky.github.io//publication/Patil_2025_file). Particularly, we combined U-net (CNN) denoising autoencoder and XGBoost regression. This way we acquire a) tighter constraints on the thermal and ionization state of the IGM and b) decrease the observational requirements for detecting the signal.

## 21-cm forest in close proximity to quasar

<video width="900" height="450" controls loop="" muted="" autoplay="">
  <source src="https://github.com/tomassoltinsky/tomassoltinsky.github.io/raw/master/images/near-zones.mp4">
</video>

I also study how the radiation from the host quasar affects its surroundings and the 21-cm forest close to it (blue curve in the bottom panel of the above animation). Quasars are extremely bright nuclei of galaxies whose engines are accreting supermassive black holes. Their effect has been researched extensively for an analogous signal, Ly$$\alpha$$ forest (green curve in the bottom panel) which is also a series of absorption features in the spectra of quasar arising from neutral hydrogen, but due to a different transition in the neutral hydrogen atom. Hence, instead of being observed in radio, it appears in the UV, optical and infrared spectrum. In the top panel, which shows the neutral hydrogen fraction of the IGM, one can see how UV photons sourced by the quasar (which is located on the left) ionize the IGM close to the quasar. The ionization front propagates throught the IGM and this this is mimicked by the Ly$$\alpha$$ forest. In the middle panel the temperature of the gas is shown. The temperature follows the ionization front too, but there is also a tail of higher temperature beyond the ionisation front. This is driven by the X-ray photons. This tail of higher temperature suppresses the 21-cm forest signal. Given these differences between the 21-cm and Ly$$\alpha$$ forest, particularly if their extent is dictated by X-rays or UV photons, they can be complimentary in studies of the accreting supermassive black holes. More details can be found in [Šoltinský et al. 2023](https://tomassoltinsky.github.io//publication/Soltinsky_2023_file).
