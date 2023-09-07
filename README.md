# Sloan-Digital-Sky-Survey---DR18
Data on Celestial Objects from the Sloan Digital Sky Survey - Data Release 18

This dataset consists of 100,000 observations from the Data Release (DR) 18 of the Sloan Digital Sky Survey (SDSS). Each observation is described by 42 features and 1 class column classifying the observation as either:

a STAR
a GALAXY
a QSO (Quasi-Stellar Object) or a Quasar.
You can read more about the features below:

Objid, Specobjid - Object Identifiers
ra - J2000 Right Ascension
dec - J2000 Declination
redshift - Final Redshift of the celestial object
u, g, r, i, and z - better of DeV/Exp magnitude fit for u, g, r, i, and z. u, g, r, i, and z correspond to the five photometric bands namely ultraviolet band, green band, red band, infrared band, and near infrared band respectively.
run - Run number
rerun - Rerun number
camcol - Camera column
field - Field number
The run number refers to a specific period in which the SDSS observes a part of the sky. SDSS is divided into several runs, each lasting for a certain amount of time, which are then combined to cover an extensive portion of the sky. The rerun number refers to the reprocessing of the data obtained.

In each run, multiple charge-coupled device (CCD) cameras are arranged into a column which are responsible for imaging a specific portion of the sky. camcol refers to the camera column number which imaged a specific observation. A field is a specific portion of the sky that is imaged during a single exposure of the telescope. The entire sky is divided into a portion of fields and the field number column refers to the field or portion of the sky from which an observation was obtained.

plate - Plate number
fiberID - Optical Fiber ID
A number of physical glass plates are mounted on the telescope, each containing a number of optical fibers corresponding to a specific position in the sky. When light hits these optical fibers, it is sent to spectrographs for analysis. plate number and fiberID refer to the number of the plate and the ID of the optical fiber responsible for gathering light from the celestial object respectively.

mjd - Modified Julian Date
Modified Julian Date represents the number of days that have passed since midnight Nov. 17, 1858. It is used in SDSS to keep track of the time of each observation.

petroRad_u, petroRad_g, petroRad_r, petroRad_i, and petroRad_z - Petrosian Radii for the five photometric bands u (ultraviolet), g (green), r (red), i (infrared), and z (near-infrared) respectively.
The petrosian radius is a measure of the size of a galaxy, and it is calculated using the petrosian flux profile. The petrosian flux profile measures how the brightness of an object varies with distance from its center. The petrosian radius is defined as the distance from the galaxy's center where the ratio of the local surface brightness to the average surface brightness reaches a certain predefined value. The local surface brightness refers to the brightness of a specific small region or pixel on the surface of an extended object. It is a measure of how much light is detected from that particular region. The average surface brightness, on the other hand, represents the mean or average brightness measured over the entire surface of the extended object. It is the total amount of light received from the object divided by its total area.

These parameters help in characterizing the properties of celestial objects, especially when studying their morphologies, sizes, and how they evolve over time.

petroFlux_u, petroFlux_g, petroFlux_r, petroFlux_i, and petroFlux_z - Petrosian Fluxes for the five photometric bands u (ultraviolet), g (green), r (red), i (infrared), and z (near-infrared) respectively. These features describe the total amount of light emitted from the celestial objects.
These parameters help in studying the photometric properties of the celestial objects, particularly in analyzing the brightness, colors, and spectral energy distribution of the objects. By using petrosian fluxes in different bands, astronomers can obtain a comprehensive view of an object's light emission across the electromagnetic spectrum.

petroR50_u, petroR50_g, petroR50_r, petroR50_i, and petroR50_z - Petrosian half-light radii for the five photometric bands u (ultraviolet), g (green), r (red), i (infrared), and z (near-infrared) respectively. PetroR50 is a measure of the radius at which half of the total light (or flux) emitted from a celestial object is enclosed with the petrosian aperture. The petrosian aperture is defined based on the petrosian radius, which is a measure of the size of the celestial object. The petrosian aperture allows astronomers to capture a substantial fraction of the total light emitted by an extended object while minimizing the contamination from nearby sources or background noise.
These parameters are important for characterizing the sizes of objects in the SDSS data and how the sizes of the objects vary at different wavelengths.

psfMag_u, psfMag_g, psfMag_r, psfMag_i, and psfMag_z - Magnitudes of objects measured using the Point Spread Function (PSF) in the five photometric bands u (ultraviolet), g (green), r (red), i (infrared), and z (near-infrared) respectively.
The Point Spread Function (PSF) is a mathematical model that describes the response of an imaging system, such as a telescope, to a point source of light (e.g., a star) in an image. As most astronomical objects are extended and not point sources, the PSF is often used to characterize the brightness of these extended objects by approximating them as if they were point sources.

The psfMag values represent the magnitudes of objects as measured through the PSF. Magnitude is a logarithmic scale used in astronomy to quantify the brightness of celestial objects. Lower magnitudes correspond to brighter objects, and higher magnitudes correspond to fainter objects. These PSF magnitudes help in characterizing the brightness and colors of astronomical objects, such as stars and galaxies, in the SDSS data.

expAB_u, expAB_g, expAB_r, expAB_i, and expAB_z - axis ratio of exponential fits to the light profile of celestial objects observed in the five photometric bands u (ultraviolet), g (green), r (red), i (infrared), and z (near-infrared) respectively.
These axis ratios are morphological features that help characterize the shapes of celestial objects, such as galaxies, in different SDSS bands.
