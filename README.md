# aggregate_scattering
Scattering calculations and geometry information for the various aggregation experiments in [Schrom et al. (2022)](https://doi.org/10.1175/JAS-D-22-0149.1).

## Structure
Files containing the forward and backward scattering data for the aggregation sets have 'radar' at the end of their names. Likewise, the corresponding geometry files have 'geom' at the end of their names.

The first part of the file name corresponds to the aggregation assumptions. The two orientation assumptions, full Euler-angle random and azimuthally random correspond to 'er' and 'ar', respectively. Aggregates of branched planar crystals and columns are indicated by 'bpa' and 'ca', respectively. Pivoting and non-pivoting monomers are indicated by 'p' and 'np', respectively.

These files are all [NetCDF](https://www.unidata.ucar.edu/software/netcdf/) files and can be read with the appropriate interfaces for a variety of languages.
