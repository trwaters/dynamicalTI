## Animations
The animations below are of time-dependent solutions to the equations of non-adiabatic gas dynamics described in this [ApJ paper](https://ui.adsabs.harvard.edu/abs/2021arXiv210109273W/abstract), designed to model the parsec-scale environments of AGN accretion disks that are being subjected to irradiation by ionizing X-ray photons (assumed to be produced in a hot corona in the immediate vicinity of the supermassive black hole).  These are 1D calculations performed in either spherical coordinates ('RW' = radial wind case) or cartesian coordinates ('VW' = vertical wind case) using [Athena++](https://github.com/PrincetonUniversity/athena-public-version/wiki) (v19). 

### RW runs
Here is a movie of the initial evolution starting from constant pressure initial conditions.  This shows the 'construction' of the full thermal wind solution consistent with the imposed boundary conditions.  The final state -- a disk atmosphere and a tenuous disk wind -- is insensitive to the initial conditions.  In all of the runs below, time is shown in units of the Keplerian orbital period at 1 R_IC.  The red contour marks where the Bernoulli function vanishes, indicative of a transition from bound to unbound flow.  
<video poster="fig6vw.png" width="675" height="1408" controls preload> 
    <source src="rwmovie.mp4" media="only screen and (min-device-width: 568px)"></source> 
    <source src="rwmovie.mp4" media="only screen and (max-device-width: 568px)"></source> 
</video>

### VW runs


### Acknowledgements
These simulations were run on the Pleiades supercomputer at NASA's Advanced Supercomputing facility under the HEC Program allocation SMD-20-10568625.  We thank the [Athena++](https://github.com/PrincetonUniversity/athena-public-version/graphs/contributors) development team for maintaining this code. 
