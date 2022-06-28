# aggregate_scattering
Scattering calculations and geometry information for various aggregation experiments.

## Structure
Files containing the forward and backward scattering data for the aggregation sets have 'radar' at the end of their names. Likewise, the corresponding geometry files have 'geom' at the end of their names.

The first part of the file name corresponds to the aggregation assumptions. The two orientation assumptions, full Euler-angle random and azimuthally random correspond to 'er' and 'ar', respectively. Aggregates of branched planar crystals and columns are indicated by 'bpa' and 'ca', respectively. Pivoting and non-pivoting monomers are indicated by 'p' and 'np', respectively.

These files are all [NetCDF](https://www.unidata.ucar.edu/software/netcdf/) files and can be read with the appropriate interfaces in many different languages.
