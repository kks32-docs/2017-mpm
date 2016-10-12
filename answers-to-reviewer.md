# Comments

The authors would like to thank for an insightful review. We have addressed the comments raised by the reviewer. 

## Reviewer 1
### Text in figures cannot be read. 

The figures have been updated.

### Define mean fraction

Mean packing fraction is the fraction of solid mass in a given space. The definition has been added to the paper. 



## Reviewer 2

### This is a clear well-written paper on the comparison between MPM and DEM simulation results on the motion of a granular slope. The title, however, suggests an analysis of the differences in the results from both approaches. Such discussion is hardly found in the current version.

The paper title has been modified to reflect this: `Modelling of transient dynamics of granular slopes: MPM and DEM`.

### Figures 3a,b show clear differences between DEM and MPM results. Not much information is provide about the causes of these differences and which one of the models is correct. Yet, the last conclusions calls MPM successful. I think that needs some more detailed discussion.

At very low energies, DEM simulations show longer run-out distance due to local fluidisation, mainly controlled by failure of the soil mass at the top of the pile. A critical energy is required, before the entire soil mass participates in the flow. This results in an almost constant normalised time in DEM, which is absent in MPM due to its continuum nature.


### Figures 4 and 5 contains curves for low energies e.g. 10J that show deviating behaviour like the oscillations in 5b. Not much information is provided explaining this.

Higher proportion of vertical acceleration $E_{ky}/E_0$ is observed for lower values of input energy $E_0$. This means that, at lower input energies a larger fraction of the energy is consumed in the destabilisation process, which results in oscillations in the kinetic energy. Whereas at a higher input energies, most of the energy is dissipated in the spreading phase. For this reason, the total duration $t_1$ of this destabilisation phase is nearly the same in both regimes and its value is controlled by gravity rather than the input energy. 

### Page 2, Line 4 says that DEM ‘often’ correctly reproduces the dynamics. I guess this is the motivation to make the comparison between MPM and DEM. I suggest to be more specific on what is correctly reproduced by DEM that builds confidence in the model and allows to draw conclusions from this comparison only without using any experimental data.

DEM simulations were compared to experimental work on granular column collapse. The parameters for MPM were obtained by performing a periodic shear test. Since, DEM was able to reproduce the behaviour of granular collapse, the same configuration and properties were used to study the slope failure problem with an input kinetic energy. In this study, we are interested in understanding if MPM is capable of reproducing the micro-scale behaviour observed in DEM using parameters obtained from a simple shear test.

### Some other questions that popped up while reading the paper: Is this configuration a standard test? Or should experimenters be stimulated to perform such a test? Why would this be a good test for demonstrating the capacities of the MPM-approach?

A comparison of DEM and MPM was done for collapse of a granular column. For tall columns, the collapse was controlled by the collision between grains and was not reproduced in MPM (Soundararajan, 2015). Hence, in this study, we coverted the vertical acceleration from a column collapse to a horizontal kinetic energy and applied to a slope, there-by eliminating the collision effect. This configuration shows an overall good comparison between MPM and DEM.

### It looks like the simulation is essentially 2D. Is this a severe limitation? Why not a 3D simulation? These aspects should be addressed. Preferably some additional information should be provided as in what respect 3D-effect could change the picture. In other words, how relevant is this test when it comes to ‘real world’ applications.

The study assumes a plane-strain condition, which is typical for a large landslide. A 3D simulation will definitely consider movement into the plane, however, we feel that effect in a large landslide is minimal. Although, effects like fingering of flow would be interesting to look at from a 3D perspective.

### The lettering of most graphs is too small. Particularly, graphs 4 and 5 contain too many curves. L_i in figure 8 is not defined.

All figures have been updated.

### If MPM was demonstrated to be successful, what are the pro’s and con’s and promises in the comparison with DEM?

MPM is computationally faster to run than DEM to study large-deformation problems. MPM is able to reproduce the overall run-out dynamics, when collision is not involved. 
