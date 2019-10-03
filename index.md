## Simulations from Waters et al. (2019)

The animations below are part of [this paper](https://arxiv.org/abs/1910.01106), which has been submitted for publication to MNRAS Letters.

The top panels show the inflow (blue lines) and outflow (red lines) rates as a function of radius.  The difference between these curves is the net accretion rate, shown as dashed black lines; it shows barely noticeable fluctuations away from the Bondi rate as the simulation evolves.   

The middle panels show colormaps of pressure (in units of `p_0`, the reference pressure at the outer boundary) on a linear scale over the full domain.  The bottom panels zoom into the region within the Bondi radius and show instead log-scale plots of the azimuthal component of angular momentum in units of `R_s c`.  This region looks nearly identical to the spherically symmetric Bondi solution when looking at density, radial velocity, or pressure; the sonic surface is unchanged and appears in the bottom left corner as a black contour.  

The initial conditions for all of these runs is the analytic Bondi solution.  Time is shown in the upper right corner of each plot in units of the dynamical time `R_B/c_s(R_o)`.

### Constant entropy BC runs

<video poster="poster.png" width="650" height="1200" controls preload> 
    <source src="A2_movie.mp4" media="only screen and (min-device-width: 568px)"></source> 
    <source src="A2_movie.mp4" media="only screen and (max-device-width: 568px)"></source> 
</video>
<video poster="poster.png" width="650" height="1200" controls preload> 
    <source src="A3_movie.mp4" media="only screen and (min-device-width: 568px)"></source> 
    <source src="A3_movie.mp4" media="only screen and (max-device-width: 568px)"></source> 
</video>
<video poster="poster.png" width="650" height="1200" controls preload> 
    <source src="A4_movie.mp4" media="only screen and (min-device-width: 568px)"></source> 
    <source src="A4_movie.mp4" media="only screen and (max-device-width: 568px)"></source> 
</video>

### Constant pressure BC runs
<video poster="poster.png" width="650" height="1200" controls preload> 
    <source src="B2_movie.mp4" media="only screen and (min-device-width: 568px)"></source> 
    <source src="B2_movie.mp4" media="only screen and (max-device-width: 568px)"></source> 
</video>
<video poster="poster.png" width="650" height="1200" controls preload> 
    <source src="B3_movie.mp4" media="only screen and (min-device-width: 568px)"></source> 
    <source src="B3_movie.mp4" media="only screen and (max-device-width: 568px)"></source> 
</video>

### Acknowledgements
These simulations were run on the Institutional Computing clusters at Los Alamos National Laboratory under allocation award w19_rhdccasims (PI: T. Waters).  We thank the [high performance computing team](https://www.lanl.gov/org/ddste/aldsc/hpc/index.php) for their continued efforts, as well as the developers of the public GRMHD code [Athena++](https://github.com/PrincetonUniversity/athena-public-version/graphs/contributors).  
