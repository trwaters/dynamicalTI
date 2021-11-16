## Animations
The animations below are of time-dependent solutions to the equations of non-adiabatic gas dynamics described in this [ApJ paper](https://ui.adsabs.harvard.edu/abs/2021arXiv210109273W/abstract), designed to model the parsec-scale environments of AGN accretion disks that are being subjected to irradiation by ionizing X-ray photons (assumed to be produced in a hot corona in the immediate vicinity of the supermassive black hole).  These are 1D calculations performed in either spherical coordinates ('RW' = radial wind case) or cartesian coordinates ('VW' = vertical wind case) using [Athena++](https://github.com/PrincetonUniversity/athena-public-version/wiki) (v19). 

### RW runs
Here is an animated version of Figure 3 in the paper, showing how the outflow climbs the S-curve starting from a stable location on the cold branch.  This illustrates one of the key ideas of the paper --- that a simple rise in the flux is sufficient to make a UFO unstable.  Here, time is shown in years.  For more information, see Section 3.2 of the paper.  
<video poster="fig3.png" width="675" height="1408" controls preload> 
    <source src="rw_unstable.mp4" media="only screen and (min-device-width: 568px)"></source> 
    <source src="rw_unstable.mp4" media="only screen and (max-device-width: 568px)"></source> 
</video>

Here is the animated version of Figure 6, showing how the clumps form within and then comove with the background wind solution.
<video poster="fig6rw.png" width="675" height="1408" controls preload> 
    <source src="rwmovie.mp4" media="only screen and (min-device-width: 568px)"></source> 
    <source src="rwmovie.mp4" media="only screen and (max-device-width: 568px)"></source> 
</video>

### VW runs


### Acknowledgements
These simulations were run on the Pleiades supercomputer at NASA's Advanced Supercomputing facility under the HEC Program allocation SMD-20-10568625.  We thank the [Athena++](https://github.com/PrincetonUniversity/athena-public-version/graphs/contributors) development team for maintaining this code. 
