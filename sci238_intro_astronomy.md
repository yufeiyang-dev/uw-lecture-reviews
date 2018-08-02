## 12. The Properties of Stars [need simplify]

### Distances to stars (5)

#### Fundamental distance determination is from stellar parallax

- The motion of the Earth around the Sun (once per year) causes an apparent motion of nearby stars relative to more distant "background" stars.
- Stars appear to move in a loop around the sky once per year.
- This "reflex" motion is called stellar parallax.

#### Trigonometric Parallax

- nearby stars will have a larger parallax
- nearest stars have a parallax less than 1 arcsec
- define a unit of distance: the **parsec** - objects that have parallax equals to 1.0 arcsec are at a distance of 1 parsec

```
parallax (radians) = 1.0 AU / distance
1 parsec = 206265 AU   =>   p (arcsec) = 1/d (pc)
                       =>   d = 1/p (arcsec)
```

### Brightness, luminosity, and colours of stars (10)

#### Brightness is provisional to $1/d^2$

- The light is spread out over a larger area as it travels further from its source, therefore the energy of the light falling on any one square is less for squares further from the source.
- $b = \frac{L}{4\pi d^2}$

#### Brightness versus Luminosity

- **Brightness**: total light energy is collected from an object: brighter => more light is collected.
  - <u>brightness depends on the distance</u> from the emitting object to the collecting detector.
  - brightness can also be affected if there is anything along the line of sight from emitter to collector that <u>blocks (absorbs or scatters)</u> some of the light.

#### Luminosity**: total light **emitted by the object = *intrinsic*

- depends <u>only</u> on the properties of the emitting object
- depends on surface emission properties and surface area

#### The magnitude system

- first defined bu Hipparcos (~100 BC) and refined by Ptolemy (~100 AD)
- scale set for naked-eye stars: brightest are *first* magnitude, faintest stars visible - *sixth* magnitude
- scale quantified by Herschel and Pogson (1856)
  - a *<u>first</u>* magnitude star is 1-- times brighter than a *<u>sixth</u>* magnitude star (i.e. is $m_1 - m_2 = 5$ then $b_2 / b_1$ = 100)
  - this logarithmic scale reflects how the eye responds: it converts <u>equal ratios of actual intensity</u> into <u>equal intervals of perceived intensity</u>.
- ==NOTE: we will not do magnitude calculations for this course==

#### magnitude and distance: Absolute magnitude

- apparent (or observed) brightness depends on distance. We call the observed brightness the **apparent magnitude**
- we define **absolute magnitude M** as the brightness (in magnitudes) that a star would have at distance d = 10 pc and it relates directly to the luminosity of the star.

#### The colours of Stars

- A star's "colour" is a direct measure of its temperature
  - red stars are cooler than blue stars (~BB, Wien's Law)
  - the reddest stars are probably a few $\times 10^3 K$
  - bluest stars are probably a few $\times 10^4 K$
- also, there are processes that can change the colour of the light - especially: dust grains in interstellar space can "redden" starlight
- we can measure the brightness in a particular range of wavelengths and compare - say brightness in blue vs. red
  - the measured brightness in two different wavelength ranges gives the colour of the object
  - simplistically: if a star is measured to be brighter in the blue (more energy) than in the red, then we say that the star is blue - it is hotter
  - we can quantify this => colour scale

#### BB spectra: reminder

- hotter sources are brighter (emit more energy) at all $\lambda$
- Emission = $\sigma T^4$
- $\lambda_{max} (nm) = 2900000/T (K)$

#### Measuring the colours of stars

- colour is the ratio of the brightnesses in two wavelengths - or the magnitude difference

### Classification of spectra from stars (21)

#### Stars are nearly black bodies but not quite

- spectral lines cause a star's spectral hope to deviate slightly from BB curve - generally more in the red than blue
- a star's spectrum tells us more about the star than just a surface temperature

#### Stellar Spectra

- three kinds of spectra (Lecture 5)
  - <u>continuous</u>: emission at all wavelengths (e.g. a blackbody) formed by hot solid to hot high pressure gas
  - <u>emission</u> line: each element, as a hot low pressure gas, emits at unique set of wavelengths (determined by the energy levels occupied electrons)
  - <u>absorption line</u>: each element, as a cool low pressure gas will absorb at a unique set of wavelengths  from a continuous spectrum
- stars can produce all three kinds of spectra - but most produce an absorption (i.e. a continuous spectrum with absorption lines) spectrum
  - the wavelength patterns in the lines give the elements in the cooler outer layers of the star
  - the strengths of the lines tell us about the density and temperature where the lines are formed and also the amount of the elements present

#### Stellar spectra vs. Photometry

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

#### Absolute Magnitude vs. Spectral Type: the HR Diagram

- first plotted by Hertzsprung (1905) and Russell (1913) -> now called the HR diagram
- <u>vertical axis</u>: **luminosity** (absolute brightness) -> $M_V$ absolute magnitude in $V$
- <u>horizontal axis</u>: originally **spectral type** (now also **T**, **colour**)

#### Modern HR Diagram

- absolute magnitudes based on parallax distances from Hipparcos staellite
- colours => density of points red highest

#### schematic HR diagram showing the main features

- not a scatter plot; large "empty" areas
- most starts lie along a **main sequence** (MS)
- MS is a **mass** sequence
- other major regionsL giant, supergiant, white dwarf are different evolutionary stages with a wide range of amss
- **radius lines "diagonal"**

#### HR Diagram: stellar L, T, R

- Remember: luminosity depends on both energy emitted/area and surface area
- For a spherical BB: $L = 4\pi R^2 \times \sigma T^4$
- stars are moderately good blackbodies
- stars with same surface temperature (colour) but different luminosities must have different radii; also different densities.

#### nearby binary system Sirius A, B

- radius difference is real
- Sirius A: hot MS star with $R$~$2R_{Sun}$
- Sirius B: hot white dwarf star with $R$~$0.008R_{Sun}$

#### HR diagram of the nearest stars

- <u>sample bias = distance</u>
- nearest stars are mostly faint MS - low mass, less massive than the Sun
- a few white dwrfs
- a few brighter MS stars
- no massive MS stars, no giants or supergiants

#### HR diagram of the brightest stars

- <u>sample bias = apparent brightness</u>
- brightest stars are mostly luminous stars
- on MS all much more massive than the sun
- also giants, supergiants
- no intrinsically faint stars (i.e. low MS, WD)

#### What is the Main Sequence?

- The place where esters spend most of their lives
- The most massive stars are the most luminous (brightest), and hottest (blue)
- The lowest mass stars are faint, cool, and red
- Strs do not move (much) on the Main Sequence - they start close one spot on this diagram for most of their lives.

### Motions of stars (38)

#### Stellar Motions: all stars move

- measure components: radial velocity (Doppler shift) and "transverse" velocity (across the line of sight)
- can measure transverse velocity only if the star is moving fast and is close to us ("proper motion")
- without motion, gravity acting between all of the stars would bring them together
- motions of stars tell us something about the gravity acting on the stars - if there is more motion (higher velocities) then there is stronger gravity (more mass)
  - binary star orbits => stellar mass
  - internal motions of stars in clusters => cluster masses
  - motions of stars around the galaxy => galaxy mass
- statistical studies of the motions of stars are sued as well.

#### Radical versus transverse motion

- illustrated on page 39

### Groups of stars (41)

#### Binary Stars

- two (or more) stars in orbit around a common centre of mass.
- various possible cases:
  - <u>visual binary</u>: both stars visibly orbiting each other.
  - <u>astrometric binary</u>: only one star is visible - the one star moves around in the sky in a loop or wave.
  - <u>spectroscopic binary</u>: only one star is visible; it shows no visible motion, but from tis septum one can see a regular periodic motion from doppler shifts; sometimes only brighter star's spectrum is seen, sometimes both.
  - <u>eclipsing binary</u>: one star passes "in front" of the other, blocking some of the light reaching us and causing a change in the system's brightness

#### Visual Binaries

- **binary star systems**: can be used to measure the mass of the stars
- in a visual binary sytem the stars are resolved
- period determined from motion of one star about the other
- mass ratio from relative orbital scales
- **need to know distance to determine "true" masses**

#### Spectroscopic Binary System

- in a spectroscopic binary we observe periodic changes in spectral line wavelengths
- timescale => orbital period
- amplitude => orbital scale
- amplitude ratio => mass ratio

#### Eclipsing Binary System

- in an eclipsing binary we observe periodic changes brightness: eclipses
- timescale => orbital period
- eclipsing timing => ratio of radii
- eclipse depth + radius => temperature and luminosity ratios
- if also spectroscopic true radii + mass => densities
- **previous/other knowledge of distance not needed if system is both eclipsing and spectroscopic**

### Miscellaneous

- **≥ 90% of stars have mass < 1**$M_{Sun}$
- **Stellar radii can be as small as a planet to as big as Mars' orbit**
- **Are all strs on the Main Sequence the same mass?**
  - The most luminous stars are those with the most mass.
- The lifetimes of stars depend on (1) the amount of fuel (mass) and (2) the rate at which the star uses up that fuel (luminosity)
  - Result: the most massive stars have the shortest lives

### Summary (51)

- We can measure the brightness, colour, and spectra of any star that we can see
- To measure the mass of a star it must be in orbit around another star (binary star)
- However we <u>**assume**</u> that if two stars are identical in luminosity and spectra then they are identical in mass too.

## 16. Milky Way

### The interstellar medium (3)

- Looking out in some directions we see wide swaths of gas and dust: the interstellar medium

#### What is it made of?

- <u>hydrogen</u>: by far the most common element in the ISM; exists in three states
- <u>other elements</u> also found i the three states
- <u>other components</u> of ISM
  - cosmic rays
  - magnetic fields
  - DUST

#### Interstellar Dust

- only ~1%
- causes extinction (obscuration) of visible light
- reddens visible light by scattering the bluer photons more
- 10nm - 200 nm (0.01 - 0.2 μm)

#### Other Effects of Interstellar Dust

- severe depletion of gaseous C, N, O in dusty areas
- dust grains: chemical reactions
- dust grains are good infrared radiators

#### <u>Structures</u> in the Interstellar Medium

- <u>diffuse Interstellar Clouds</u>
- <u>molecular clouds</u>
- <u>diffuse "Intercloud" medium</u>
- HII regions: massive, hot, short-lived stars
- supernova remnants: only ~150 known in the Galaxy

#### <u>Molecular Clouds</u>

- The densest, coolest part of the ISM
- Measuring mass: most of the mass of the cloud is in hydrogen and helium gas ($H_2$)

#### The cosmic cycle of the elements

- stars are formed from interstellar gas
- stars convert elements to heavier elements
- when stars die they put some of this enriched gas back into the interstellar medium
- next generation of stars formed from more enriched material then previous generation
- the "metallicity" of the universe is constantly increasing.

### Distance measurements (23)

#### The Distance Scale in the Milky Way

- <u>trigonometric parallax</u>
- some <u>statistical techniques</u> good for larger distances (to a few kpc?)
- beyond ~1kpc, for "general" directions, we need to use "standard candles"
- <u>kinematic distances</u>
- "standard candles": objects whose intrinsic luminosity (absolute magnitude) is known.
- combination of `m, M` or `b, L => d`
- several "standard candles" but main ones are

#### The scale of the Milky Way

- observations of RRLyrae stars i globular clusters in out Galaxy led to the discovery that we (Earth, Sun) are not at the centre of the Galaxy
- this result was later strengthened by Main Sequence fitting of globular cluster CMDs
- current estimates is that we are 8 npc (24,000 light years) from the centre

#### disc vs. halo `<->` orbits

- Orbits (speed and distance) are set by mass!
- objects in the halo regularly pass through the disc

### The structure of the Galaxy (37)

#### Structure of the Milky Way Galaxy

- disk, bulge, halo $\rightarrow$ the largest scale structures in the Galaxy
- disk has "spiral arms" - bright, patchy features that spiral out from near the centre of the Galaxy to near the edge
- patchy because of other processes? Large explosions, "superbubbles"
- interstellar material concentrated in spiral arms, star formation too.
- shortest-lived stars are very very bright (high mass stars) and concentrated in arms too.

#### "rotation curve": What is it? What does  it tell us?

- a rotation curve is a plot of orbital velocity (rotation) vs distance from centre of mass of the orbit
  - need to measure both velocity and position of objects at various distances from centre of mass
  - note: $v_{orbit}$ drops rapidly as distance increases.

#### The Rotation Curve of the Milky Way

- "solid body" in innermost disc; but outside?

#### Mass of the Milky Way: from its rotation curve

- larger mass means a larger orbital velocity to travel in circular orbit at a given distance
- larger distance (for a fixed mass) requires a smaller velocity for a circular orbit
- rotation curve of Milky Way is nearly flat (at $v_{rot}$ 200 km/s) out to 20 kpc
- flat rotation curve implies $\bold{M_{MW} \geq 2 \times 10^{11} M_{Sun}}$ at Sun's distance from the centre
- studies of the rotation of objects in orbit around the Milky Way, at even larger distances, give masses another factor of 10x greater than this i.e. $\bold{M_{MW} \sim 2 \times 10^{12} M_{Sun}}$
- the total **visible** mass of the Milky Way is $\bold{\sim 1 \times 10^{11}M_{Sun}}$
- from orbits (gravity) we detect as much as 10 - 10x more mass than we see!

#### Dark Matter

- What is dark matter? (44)

#### Spiral Density Wave Model

- stars and gas pass through a wave where they slow down, temporarily, as they orbit around the Galaxy
- this area where the material moves more slowly will therefore have a greater density
- higher density material responds in a very non-linear fashion
- for example, the star formation process can begin

### The supermassive black hole at the centre (57)

#### The centre of the Milky Way

- there is evidence of a very massive object at the centre of out Galaxy
- thought to be a "supermassive black hole"

### Miscellaneous

- Interstellar gas often detected in stellar spectra (9)
- RRLyrae and Cepheid variable stars have well defined Period, Luminosity relations (26)
- solid body rotation curve (39)
- goatitional lenses tell us about mass we cannot see (45)

### Summary (60)

- Our Milky Way consists of
  - a halo containing most of the (dark) matter
  - a disk containing most of the visible structure (spiral arms, ISM), and
  - a small bulge around the centre
- A supermassive blackhole in the very centre

## 17. Galaxies

### Galaxy types (4)

#### Galaxies: classified by their morphology (appearance/shape)

- <u>spirals</u> (like our own)
  - nucleus, arms, bar...
- <u>ellipticals</u>
  - Elliptical galaxies classified by "ellipticity"
  - Elliptical galaxies very greatly in size and mass
- <u>lenticulars</u>
- <u>barred spiral</u>

#### The Winding Dilemma

- spiral arms (or any other features) in a differentially rotating disk will "wind up" in a few rotation periods. The arms should get very much tighter quickly.

#### Spiral Density Wave Model

- stars and gas pass through a wave where they slow down, temporarily, as they orbit around the Galaxy
- this area where the material moves more slowly will therefore have a greater density
- higher density material responds in a very non-linear fashion
- for example, the star formation process can begin

#### Properties of Galaxies

|                        | Spirals / Barred Spirals                                     | Lenticulars                                   | Ellipticals                           | Irregulars           |
| ---------------------- | ------------------------------------------------------------ | --------------------------------------------- | ------------------------------------- | -------------------- |
| Appearance             | flatteneddisk<br />bulge <br />spherical halo <br />spiral arms | disk<br />bulge<br />halo                     | no disk<br />ellipsoidal distribution | no obvious structure |
| Gas/Dust<br />(mass %) | in disk<br />3-10%                                           | little or none<br />0-1%                      | little or none<br />< 0.1%            | lots<br />10-20%     |
| stars                  | old in halo; <br />young and old in disk                     | old                                           | old                                   | young and old        |
| star formation         | in spiral arms                                               | none                                          | noen                                  | vigorous             |
| stellar motions        | circular orbits in disk;<br />random in halo                 | circular orb its in disk;<br />random in halo | random                                | random               |

### Extragalactic distance scale (27)

#### The Extragalactic Distance Scale

- <u>Cepheid Variable</u> Star (Period-Luminosity Law)
- <u>Hubble Law</u> - expansion of the Universe
- <u>Tulley-Fisher</u> (more massive galaxies are more luminous)
- Type Ia supernova

#### Galaxy radial velocity correlates with distance: $V = H_0d$

- Hubble observed that virtually all galaxies are moving away from out own Milky Way galaxy
- the distances between galaxies are increasing

#### The Hubble Law: $V = H_0d$

- measures the radial velocities of galaxies using the Doppler shift
- plot the distance to the galaxies versus their velocities
  - **Hubble's Constant:** $\bold{H_0}$

#### Using the Hubble Law to determine distance

- mesure the raidal velocity
- "invert" the equation: $\bold{d=v/H_0}$
- the galaxy radial velocity is often referred to as **redshift z**
- z is the fractional change in the measured wavelength: $\bold{z = \Delta\lambda / \lambda}$
  - z=1 is a **very large change in wavelength**

#### Supernovae (Type Ia)

- the mechanism producing supernovae is well understood - all white-dwarf/binary SN are close to identical...
- from intensive studies of many supernovae (extragalactic ones) the absolute brightness (the luminosity) of a given supernova can now be determined by plotting its light curve
- a new standard candle

### Peculiar and active galaxies (35)

#### Peculiar Galaxies

- tidal tail caused by dynamical interaction with another galaxy
- Starburst galaxy: star formation has been triggered by a merger  between two galaxies

#### Active Galaxies

- active galaxies are those teeth extremely high luminosity
  - usually most luminous at **radio** wavelengths
- most extreme are called **quasars**
  - extremely distant
    - **must be intrinsically very brght**
    - **we are looking at them far back in time**
- large radio structures are an obvious sign of an unusual, active galaxy
- sometimes there is no such radio structure, bu the galaxy may exhibit unusual spectral characteristics - especially a high luminosity in the infrared wavelengths
- active galaxies are often bright art many wavelengths

#### Many galaxies are strong radio sources

- plasma emitted from energetic galactic centre moves at nearly the speed of light
- Radio galaxies: double lobed structure, various scales and shapes

#### Quasars

- quasar spectra have both "thermal" and "non-thermal" components
- quasars are compact = very luminous **galactic nuclei**

#### AGN model

- supermassive black holes create radio jets via interaction between electrons and strong magnetic fields
- at the centre is an accretion disc surrounding a supermassive black hole
- the current model the central "engine" of an active galaxy

### galaxy clusters (53)

#### Galaxy Clusters

- galaxies are found in groups, clusters, superclusters
- deep images find very many galaxies in som edirections
- number of galaxies in the universe >> number of stars in the Milky Way
- Milky Way galaxy in a small group called "**The Local Group**"

#### Examples

- Hickson 67 - a small, compact galaxy group
- Abell 1185 - a rich galaxy cluster with < $10^2$ members

### Miscellaneous

- Stars and gas closer to centre move faster, creating density waves that can leard to star formation (19)
- Irregular galaxies have little symmetry, often include gas (25)

### Summary

- Most galaxies are "normal" (ellipticals, spirals, lenticulars, with or without a bar)
- The Hubble Law can be sued to get distances
- A small number of galaxies show wildly different characteristics
- Galaxies are often found in clusters

## 18. The Expanding Universe

### Galaxy masses (3)

#### galaxy masses

- rotation curve
- velocity dispersion
- mitions of galaxies in orbit around each other or in a cluster
- from measurements of the Doppler Shift we can measure the rate at which galaxies rotate. But the rotation rate is determined by the mass of the galaxy.
- other spiral galaxies have rotation curves much like the Milky Way's

#### Gravity

- Gravity from an extended object - the force of gravity from a spherical mass the same if the mass is mall or large (in volume)
- Gravity from an inside an exited object - the force of gravity from inside a spherical mass is zero!

#### Falt rotation curve `=>` mass increase with distance

$G\frac{mM_r}{r^2} = m\frac{v_r^2}{r}$

- $v^2/r$ = acceleration i ncrivular motion
- $v_r$ is circular velocity at distant $r$ from centre

$M_r = \frac{rv_r^2}{G}$

- Mass within a distance of r calculated from the measured circular velovity

#### Measuring the Mass of a Cluster

- There are three independent ways to measure galaxy cluster mass

#### 1. Galaxy Orbits

- Orbiting Galaxies

#### 2. Hot gas between galaxies - intraclyster medium

- Hot ($10^7-10^8K$) gas between galaxies emits X-rays
- from the X-ray spectrum, we can calculate the termperature
- temperature tells us the average speed of the gas particles
- again, we can estimate mass `->` the mass required to retain the hot gas

#### 3. Lensing

- the angle at which the light is bent depends the mass of the cluster
- all previous methods for finding mass depended on Newton's Law of Gravity

#### Gravitational Lensing

- The amount of lensing depends on the mass of the objects acting as a lends $\rightarrow$ another way to measure the mass
- **<u>Strong lensing</u>**: makes large distorted images. But needs good alignment
- **<u>Weak lensing</u>**: a more subtle effect, look for statistical effects - much more common, but harder to measure.

#### Mass-to-Light Ratio

- is the mass of a galaxy divided by its luminosity
- Within the orbit of the Sun, $M/L = 6 M_{Sun}/L_{Sun}$ for the Milky Way
- However, when we include the outer regions of galaxies
  - $M/L$ increase dramatically
- Thus we conclude that most matter in galaxies is not stars
  - The amount of $M/L$ over $6M_{Sun}/L_{Sun}$ is the amount of **dark matter**

#### Galaxy and Cluster Masses: dark matter

- The cluster masses which are measured by all three of these independent methods agree
- There are only two possible explanations for this
  - we do not understand gravity on galaxy and cluster sized scales
  - dark mattter

#### What is Dark Matter Made Of?

- dark matter *could* be made out of protons, neutrons & electrons (i.e. **baryonic matter**)
- some or all of dark matter could be made of particles which we have yet to discover (i.e. **non-baryonic matter**)
- **<u>dark matter</u> is found in the <u>halo</u> and far beyond the luminous regions of galaxies**

#### An Extraordinary Matter Candidate

- neutrinos
- what is there existed *massive* weakly interacting particles? WIMPs

### "look-back time" (32)

#### the Hubble Law: $v = H_0d$, redshift and time

- when we look at very distant objects we are also looking at them, as as they were when they emitted the light that we see now, and they are so far away that this light was emitted long ago `=>` **we are looking back in time.**

### Are we at the centre of the Universe? (34)

#### does the Hubble Law suggest we are at the centre of the Universe?

- No: a uniformly expanding Universe gives the same result (i.e. that more distant objects recede faster)
- but will the Universe continue to expand?
- gravity must act to slow the expansion. Is it enough to stop the expansion, and to cause the Universe to collapse again?

#### The scale of the Universe if growing

- Choose a useful scale (average distance between galaxies? Average size of voids between cosmic filaments? Average density of the Universe?)
  - **distance scales grow with time**
- **When did it start?** When was the distance scale at zero? It depends on how fast the Universe is  expanding.
- **The universe used to be much smaller. OR, Things used to be much closer together**

### The **Big Bang** and the age of the Universe (39)

#### What is the age of the Universe that we get from the Hubble constant?

- 

#### The expansion of the Universe

- Has the expansion been constant?
- There is mass in the Universe `->` there is gravity
- Gravity acts to pull things together
- If the expansion of the Universe pulls the galaxies apart then the galaxies can pull back - and gravity does the pulling
- So the **expansion should get slower in the future**, and the **expansion must have been faster in the past**.

#### The Big Bang

- we believe that the expansion of the Universe if being slowed by gravity

#### the Critical Density

- we have seen that gravitational attraction between galaxies can overcome the expansion of the Universe in **localized** regions
- we refer to the mass density required for this gravitational pull to equal the kinetic energy of the Universe as the **critical density**.
- the value of $H_0$ tells us the current kinetic energy of the Universe
- this line of reattach suggests the Universe will expand forever!

#### the Hubble constant and the Age of A "flat" Universe

- in an <u>empty</u> Universe the age is $1/H_0=13.8 \ Gy$ for $H_0=71 \ km/s \cdot Mpc$
- in a <u>flat</u> Universe (at critical density) the age is $2/3 \times 1/H_0 = 9.2$ billions years.

#### Does Gravity alone Influence the Expansion?

- recent observations of white dwarf supernovae in very distant galaxies (to $z \geq 1$) have yielded unexpected results.
- **there must be an, as yet unknown, force which repels the galaxies, a dark energy.**

### The future expansion of the Universe (57)

#### four Models for the Future of the Universe

1. **Recollapsing Universe**: the expansion will someday halt and reverse
2. **Critical Universe**: will not collapse, but will expand more slowly with time
3. **Coasting Universe**: will expand forever with little slowdown
4. **Accelerating Universe**: the expansion will accelerate with time (currently favoured)

### Miscellaneous

- Mass of luminous matter (mainly stars) is not enough to match rotation curve (9)
- Spectral line isthmus of a galaxy `->` rotation rate `->` mass (10)
- Expansion is a kind of "clock": masses that are far apart now were once much closer (37)

### Summary

- The Universe is rapidly expanding - it was smaller and denser in the past
- Measurements of the masses of galaxies and galaxy clusters show they have dark matter (extra mass)
- More mass will slow down the Universe's expansion
- The initial expansion must have been very fast - like an explosion! We call this beginning **the Big Bang**
- But recent observations (Type Ia supernovae) have shown that the universe's expansion is accelerating
- We do not know what causes this acceleration!
  - We call this "cause": **Dark Energy**

### Questions

- What does "flat" mean?