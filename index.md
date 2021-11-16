## Animations
The animations below are of time-dependent solutions to the equations of non-adiabatic gas dynamics described in this [submitted paper](https://arxiv.org/abs/2111.07440), designed to follow the evolution of an ultrafast outflow (UFO) launched from the subparsec-scale environment of an AGN accretion disk.  The UFO is subjected to irradiation by ionizing X-ray photons (assumed to be produced in a hot corona in the immediate vicinity of the supermassive black hole), and this makes it prone to dynamical thermal instability.  These are 1D calculations performed in either spherical coordinates ('RW' = radial wind case) or cartesian coordinates ('VW' = vertical wind case) using [Athena++](https://github.com/PrincetonUniversity/athena-public-version/wiki) (v21). 

### RW runs
Here is an animated version of Figure 3 in the paper, showing how the outflow climbs the S-curve starting from a stable location on the cold branch.  This illustrates one of the key ideas of the paper --- that a rise in the flux is sufficient to make a UFO unstable.  Here, time is shown in years.  For more information, see Section 3.2 of the paper.  
<video poster="fig3.png" width="675" height="270" controls preload> 
    <source src="rw_unstable.mp4" media="only screen and (min-device-width: 568px)"></source> 
    <source src="rw_unstable.mp4" media="only screen and (max-device-width: 568px)"></source> 
</video>

The complicated tracks above are from a transient clump generated from the change in flux. This clump leaves the domain at t = 28 years, at which point the background flow reaches an unstable steady state.
<video poster="fig3.png" width="675" height="270" controls preload> 
    <source src="rw_unstable_p2.mp4" media="only screen and (min-device-width: 568px)"></source> 
    <source src="rw_unstable_p2.mp4" media="only screen and (max-device-width: 568px)"></source> 
</video>

Here is the animated version of Figure 6, showing what happens when we perturb this unstable background flow.  We manually insert perturbations at the base of flow every 5.2 years to isolate the dynamics accompanying the formation of a single clump. As seen here, there are significant ionization changes from compression effects but overall the dynamics is intuitive: the clump simply comoves with the background wind solution.
<video poster="fig6rw.png" width="675" height="1408" controls preload> 
    <source src="rwmovie.mp4" media="only screen and (min-device-width: 568px)"></source> 
    <source src="rwmovie.mp4" media="only screen and (max-device-width: 568px)"></source> 
</video>

Finally, here is an animated version of Figure 7.  In the above run, a clump forms at t=8 years.  Here, we show this formation process --- the saturation of dynamical TI --- on either the phase diagram.  For a description of the dynamics, please refer to sections 3.4-3.5.  
<video poster="fig7.png" width="675" height="270" controls preload> 
    <source src="rw_phase.mp4" media="only screen and (min-device-width: 568px)"></source> 
    <source src="rw_phase.mp4" media="only screen and (max-device-width: 568px)"></source> 
</video>

### VW runs
Similarly, here are the animated versions of Figures 6 and 7 but for the case of purely vertical flow.  VW and RW solutions are identical kinematically, having the same velocity profile and the same density at the base of the flow.  However, due to the different geometries of these flowtubes, their thermodynamic evolution is very different.  Whereas cooling in the RW solution is small overall and due mainly to adiabatic expansion, there is strong cooling in the VW solution, which is entirely due to the advective transport of heat downstream.  
<video poster="fig6vw.png" width="675" height="1408" controls preload> 
    <source src="vwmovie.mp4" media="only screen and (min-device-width: 568px)"></source> 
    <source src="vwmovie.mp4" media="only screen and (max-device-width: 568px)"></source> 
</video>

<video poster="fig7.png" width="675" height="270" controls preload> 
    <source src="vw_phase.mp4" media="only screen and (min-device-width: 568px)"></source> 
    <source src="vw_phase.mp4" media="only screen and (max-device-width: 568px)"></source> 
</video>

### Acknowledgements
These simulations were run on the Pleiades supercomputer at NASA's Advanced Supercomputing facility under the HEC Program allocation award SMD-20-10568625.  We thank the [Athena++](https://github.com/PrincetonUniversity/athena-public-version/graphs/contributors) development team for maintaining this code. 
