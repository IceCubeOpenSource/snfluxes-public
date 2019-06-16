# snfluxes-public
Public core-collapse supernova neutrino light curves used for simulations in [ASTERIA](https://github.com/IceCubeOpenSource/ASTERIA/).

## Models from Nakazato et al. (2013)

This is a set of neutrino light curves, average energies, and spectral pinch
parameters fit from the public models produced by Ken'ichiro Nakazato, Kohsuke
Sumiyoshi, Hideyuki Suzuki, Tomonori Totani, Hideyuki Umeda, Shoichi Yamada,
"Supernova Neutrino Light Curves and Spectra for Various Progenitor Stars: From
Core Collapse to Proto-neutron Star Cooling," ApJ S 205:2, 2013,
[arXiv:1210.6841](https://arxiv.org/abs/1210.6841).

The black hole formation model using the LS220 equation of state is described
in Ken'ichiro Nakazato, Eri Mochida, Yuu Niino, Hideyuki Suzuki, "Spectrum of
the Supernova Relic Neutrino Background and Metallicity Evolution of Galaxies,"
ApJ 804:75, 2015, [arXiv:1503.01236](https://arxiv.org/abs/1503.01236).

### Attribution

The models themselves are available in ASCII format at the [Supernova Neutrino
Database](http://asphwww.ph.noda.tus.ac.jp/snn/) maintained by Ken'ichiro
Nakazato at Kyushu University. If you use the FITS files in this project,
please make sure to properly acknowledge the papers listed above.

### Analysis Notes

Nakazato et al. provide binned neutrino energy spectra vs. time in their ASCII
database. Our FITS files parameterize the spectrum using time series of the
average energy and spectral pinch parameter. Note that the parameterization
underestimates the high-energy tail of the spectrum.
