## 12. The Properties of Stars

Stars and their properties:

- distances to stars
  - trigonometric parallax
- brightness, luminosity, and colours of stars
  - effect of distance on brightness...
  - the magnitude scale
- classification of spectra from stars
- the Hertzsprung-Russell (HR) diagram
  - or the colour-magnitude (CM) diagram
  - main-sequence, giant stars, white dwarfs
- chemical composition of stars (abundances)
- motions of stars
- groups of stars: binary stars and star clusters

### Distances to stars

- **Fundamental** distance determination is from stellar parallax.
  - The motion of the Earth around the Sun (once per year) causes an apparent motion of nearby stars relative to more distant "background" stars.
  - Stars appear to move in a loop around the sky once per year.
  - This "reflex" motion is called stellar parallax.
- **Trigonometric Parallax**
  - nearby stars will have a larger parallax
  - nearest stars have a parallax less than 1 arcsec
  - define a unit of distance: the **parsec** - objects that have parallax equals to 1.0 arcsec are at a distance of 1 parsec

```
parallax (radians) = 1.0 AU / distance
1 parsec = 206265 AU   =>   p (arcsec) = 1/d (pc)
                       =>   d = 1/p (arcsec)
```

### Brightness, luminosity, and colours of stars

- **Brightness is provisional to $1/d^2$**
  - The light is spread out over a larger area as it travels further from its source, therefore the energy of the light falling on any one square is less for squares further from the source.
  - $b = \frac{L}{4\pi d^2}$
- **Brightness versus Luminosity**
  - **Brightness**: total light energy is collected from an object: brighter => more light is collected.
    - <u>brightness depends on the distance</u> from the emitting object to the collecting detector.
    - brightness can also be affected if there is anything along the line of sight from emitter to collector that <u>blocks (absorbs or scatters)</u> some of the light.
  - **Luminosity**: total light **emitted** by the object = *intrinsic*
    - depends <u>only</u> on the properties of the emitting object
    - depends on surface emission properties and surface area
- **The magnitude system**
  - first defined bu Hipparcos (~100 BC) and refined by Ptolemy (~100 AD)
  - scale set for naked-eye stars: brightest are *first* magnitude, faintest stars visible - *sixth* magnitude
  - scale quantified by Herschel and Pogson (1856)
    - a *<u>first</u>* magnitude star is 1-- times brighter than a *<u>sixth</u>* magnitude star (i.e. is $m_1 - m_2 = 5$ then $b_2 / b_1$ = 100)
    - this logarithmic scale reflects how the eye responds: it converts <u>equal ratios of actual intensity</u> into <u>equal intervals of perceived intensity</u>.
  - ==NOTE: we will not do magnitude calculations for this course==
- **magnitude and distance: Absolute magnitude**
  - apparent (or observed) brightness depends on distance. We call the observed brightness the **apparent magnitude**
  - we define **absolute magnitude M** as the brightness (in magnitudes) that a star would have at distance d = 10 pc and it relates directly to the luminosity of the star.
- **The colours of Stars**
  - A star's "colour" is a direct measure of its temperature
    - red stars are cooler than blue stars (~BB, Wien's Law)
    - the reddest stars are probably a few $\times 10^3 K$
    - bluest stars are probably a few $\times 10^4 K$
  - also, there are processes that can change the colour of the light - especially: dust grains in interstellar space can "redden" starlight
  - we can measure the brightness in a particular range of wavelengths and compare - say brightness in blue vs. red
    - the measured brightness in two different wavelength ranges gives the colour of the object
    - simplistically: if a star is measured to be brighter in the blue (more energy) than in the red, then we say that the star is blue - it is hotter
    - we can quantify this => colour scale
- **BB spectra: reminder**
  - hotter sources are brighter (emit more energy) at all $\lambda$
  - Emission = $\sigma T^4$
  - $\lambda_{max} (nm) = 2900000/T (K)$
- **Measuring the colours of stars**
  - colour is the ratio of the brightnesses in two wavelengths - or the magnitude difference

### Classification of spectra from stars

- **Stars are nearly black bodies but not quite**
  - spectral lines cause a star's spectral hope to deviate slightly from BB curve - generally more in the red than blue
  - a star's spectrum tells us more about the star than just a surface temperature
- **Stellar Spectra**
  - three kinds of spectra (Lecture 5)
    - <u>continuous</u>: emission at all wavelengths (e.g. a blackbody) formed by hot solid to hot high pressure gas
    - <u>emission</u> line: each element, as a hot low pressure gas, emits at unique set of wavelengths (determined by the energy levels occupied electrons)
    - <u>absorption line</u>: each element, as a cool low pressure gas will absorb at a unique set of wavelengths  from a continuous spectrum
  - stars can produce all three kinds of spectra - but most produce an absorption (i.e. a continuous spectrum with absorption lines) spectrum
    - the wavelength patterns in the lines give the elements in the cooler outer layers of the star
    - the strengths of the lines tell us about the density and temperature where the lines are formed and also the amount of the elements present
- **Stellar spectra vs. Photometry**
  - Spectra
    - show detailed lines and line structure
    - can determine chemical abundances, rotation, magnetic field strength, radial velocity and more
    - spreads star's light out to see details => need bigger telesopes
  - Photometry
    - good estimates of temperature
    - chemical abundances - only very roughly
    - can use smaller telescopes, observe more stars

```
For big, large-scale surveys	=>	photometry good
For mroe detailed information	=>	spectra better
```

### The Hertzsprung-Russell (HR) diagram (29)

- **Absolute Magnitude vs. Spectral Type: the HR Diagram**
  - first plotted by Hertzsprung (1905) and Russell (1913) -> now called the HR diagram
  - <u>vertical axis</u>: **luminosity** (absolute brightness) -> $M_V$ absolute magnitude in $V$
  - <u>horizontal axis</u>: originally **spectral type** (now also **T**, **colour**)
- **Modern HR Diagram**
  - absolute magnitudes based on parallax distances from Hipparcos staellite
  - colours => density of points red highest
- **schematic HR diagram showing the main features**
  - not a scatter plot; large "empty" areas
  - most starts lie along a **main sequence** (MS)
  - MS is a **mass** sequence
  - other major regionsL giant, supergiant, white dwarf are different evolutionary stages with a wide range of amss
  - **radius lines "diagonal"**
- **HR Diagram: stellar L, T, R**
  - Remember: luminosity depends on both energy emitted/area and surface area
  - For a spherical BB: $L = 4\pi R^2 \times \sigma T^4$
  - stars are moderately good blackbodies
  - stars with same surface temperature (colour) but different luminosities must have different radii; also different densities.
  - 