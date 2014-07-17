polarikss : Polarity Kept Stupidly Simple
==========================================
*A small modelling project for the 2014 Dresden Summer School in Systems Biology*

We tried developing a quantitative model for cell polarity
establishment in a single-cell C. elegans embryo.

This model is often described using two population of proteins with
antagonistic interactions, but we tried to make it simpler by
modelling two populations of proteins **without interactions** but with
different diffusion and advection coefficients.


You can download the ipython notebook to try our model interactively
on your computer or visualize the non interactive version at
http://nbviewer.ipython.org/github/geeklhem/polarikss/tree/master/

If you want to use it on your computer the dependencies are:
- the python libraries: numpy, scipy, pandas, matplotlib.
- for the verifications and the flow speed input: as these are unpublished data, we cannot disclose them at the moment.

We decided to focus on:

- Simplicity: The model is as simple as possible, without interactions
between the two proteins. We want to see in what extent a diffusion
and a differential advection are able to break symmetry. The
implementation is also very simple (forward euler discretisation of an
EDP).

- Pedagogy: The model is implemented step by step in an Ipython
notebook, which means that all the code is visible and explained to
the user. It can also be easily modified in order to test how it would
behave. This is also why we choose to distribute it under a
free-software license: you are welcome to copy and modify it !


License:
---------
Copyright (C) 2014 - Dresden Summer School in Systems Biology Group 4

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or (at
your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
