# Open Codes | 公開ソフトウェア

All of the following codes are open to the public with the MIT license. 

## OpenSWPC

![logo-swpc](https://openswpc.github.io/fig/logo_h.png)
![demo-swpc](https://openswpc.github.io/fig/swpc-demo.gif)

This software simulate seismic wave propagation by
solving equations of motion with constitutive equations of elastic/viscoelastic
medium by finite difference method (FDM) under message passing interface (MPI)
environment in 3D and 2D (P-SV or SH) media.

This package also provides a set of tools for visualizing/converting simulation
output.

The code is available at [github](https://github.com/tktmyd/OpenSWPC/). The [online documentations](https://OpenSWPC.github.io/) are available in English and Japanese


## TDAC

![TDAC demo](https://raw.githubusercontent.com/tktmyd/tdac/master/out/tdac_demo.gif)

This code assimilates tsunami wave field from observation of tsunami height at discrete stations. The package contains a synthetic example of the tsunami data assimilation. The theory, synthetic tests, and an application are described in the following accompanying papers:

* Maeda, T., K. Obara, M. Shinohara, T. Kanazawa, K. Uehira,
Successive estimation of a tsunami wavefield without earthquake source data: A data assimilation approach toward real-time tsunami forecasting,
_Geophys. Res. Lett._, _42_, 7923-7932, doi:[10.1002/2015GL065588](http://doi.org/10.1002/2015GL065588), 2015.

* Gusman, A. R., A. F. Sheehan, K. Stake, M. Heidarzadeh, I. E. Mulia, and T. Maeda,
Tsunami data assimilation of high-density offshore pressure gauges off Cascade from the 2012 Haida Gwaii earthquake,
_Geophys. Res. Lett._, _43_(9), 4189-4196, doi:[10.1002/2016GL068368](http://doi.org/10.1002/2016GL068368), 2016.

The authors request that the user to cite the accompanying papers in any publications that result from the use of this software, although this is not an obligation.

The above-showing demo animation shows the result obtained from the example code. Left and right panels show assumed and data-assimilated tsunami wavefield (wave height) at elapsed times shown on top. Dots at the center of panels show synthetic station locations. The data observed at these stations at every one second are used for data assimilation.


The code is available at [github](https://github.com/tktmyd/tdac/).

## tsunami_pml

This software simulates tsunami wave propagation under the linear long wave (LLW) and the liner dispersive wave (LDW) approximation with the perfectly matched layer absorbing boundary condition. The theory and example are described in the accompanying paper:

* Maeda, T., Tsushima, H., & Furumura, T., An effective absorbing boundary condition for linear long-wave and linear dispersive wave tsunami simulations, _Earth, Planets, and Space_, _68_, 63, doi:10.1186/s40623-016-0436-y, 2016.

The authors request that the user to cite the above accompanying paper in any publications that result from the use of this software, although this is not an obligation.

The code is available at [github](https://github.com/tktmyd/tsunami_pml/).



## hinet_decon

Fortran2003 codes to deconvolve Hi-net velocity record by its seismometer response by using inverse filtering technique according to the following paper.

Maeda, T., K. Obara, T. Furumura, and T. Saito, Interference of long-period seismic wavefield observed by dense Hi-net array in Japan, J. Geophys. Res., 116, B10303, doi:10.1029/2011JB008464, 2011. 

The code is available at [github](https://github.com/tktmyd/hinet_decon).

## sacpack

Fortran2003 utilities on reading/writing SAC (Seismic Analysis Code) formatted seismograms without using the `SACIO` library. It contains the following utilities as well as a fortran2003 module for treating SAC format data.

The code is available at the [github](https://github.com/tktmyd/sacpack/releases).
