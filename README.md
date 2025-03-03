# Inhomogeneity-induced-wavenumber-diffusion
- Supporting materials for paper titled inhomogeneity-induced wavenumber diffusion
- Any questions, please email michael.cox [at] ed.ac.uk

## Ray tracing
- ray_tracing_for_github.ipynb contains ray tracing code for rotating shallow water system

## Rotating shallow water flow
- flow.mat example rotating shallow water flow (compressed as flow.zip)
- contains
  - 'xx', 'yy' : meshgrids of x and y coordinates
  - 'kxx', 'kyy' : meshgrids of horizontal wavenumbers
  - 'psik' : Fourier transform of stream function psi on wavenumber grid

## Geostrophic energy spectrum from 3D Boussinesq simulation
- geo_flow.zip compressed folder containing
  - kkh.npy : numpy meshgrid array of horizontal wavenumbers
  - kkz.npy : numpy meshgrid array of vertical wavenumbers
  - geoflow.npy: geostrophic flow energy at these gridpoints
- This is extracted from a snapshot of the full Boussinesq simulation described in Cox, Kafiabad, Vanneste (2023), JFM: doi:10.1017/jfm.2023.83
