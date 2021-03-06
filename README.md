# Climate State Intelligence
Climate State Intelligence (CSI) is a framework which allow capturing the state of multiple climate signals and improve seasonal forecast. CSI is composed of four steps:  
- The detection of relevant climate teleconnections is performed by means of the [Nino Index Phase Analysis](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/2015WR017644), which categorizes years by climate phase and, for each phase, identifies preseason SST anomalies statistically significantly correlated with local conditions.
- The seasonal precipitation forecasts are generated by a nonlinear, multivariate Extreme Learning Machine model conditioned on the preseason SST for the relevant teleconnections detected in the previous step.
- The hydrologic forecasts are produced through a temporal downscaling procedure of the seasonal precipitation forecast to feed a hydrologic model.
- The forecast operational value is assessed by using the [Information Selection and Assessment framework](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/2015WR017044).

Details about the framework and its application to the Lake Como basin are provided in the [Giuliani et al. (2019)](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2019WR025035). The code for the detection of climate teleconnections has been adapted from the original version of NIPA developed by Brian Zimmerman and Paul Block. The code for the seasonal precipitation forecasts is based on the ELM code used by Riccardo Taormina, Gulsah Karakaya, Stefano Galelli and Selin Damla Ahipasaoglu in the [W-QUEISS wrapper](https://github.com/stefano-galelli/Matlab-Multi-objective-Feature-Selection).

**References** 
```
Zaniolo, M., M. Giuliani, S. Sinclair, P. Burlando, and A. Castelletti (2021), When timing matters - misdesigned 
dam filling impacts hydropower sustainability, Nature Communications
```


----
### Copyright:

Copyright 2019 NRM group (Politecnico di Milano) and Water Systems & Society Research Group (University of Wisconsin Madison).

Developers: Matteo Giuliani, Marta Zaniolo, Andrea Castelletti, Paul Block, Brian Zimmerman, Angelo Carlino, Alessandro Amaranto.

CSI is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

The code is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with CSI.  If not, see <http://www.gnu.org/licenses/licenses.en.html>.

