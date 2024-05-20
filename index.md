---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults


layout: page
---

CCAKE is a relativistic viscous hydrodynamic code with 3 conserved charges (baryon number, strangeness, and electric charge) that uses Smoothed Particle Hydrodynamics. CCAKE can make state-of-the-art predictions for heavy-ion collisions and follows a multi-stage approach that includes initial conditions -> hydrodynamics -> freeze-out -> particle decays.  It uses the [4D lattice QCD equation of state](https://zenodo.org/record//6829115/) with T, baryon, strangeness, and electric charge that is coupled to the PDG16+.

You can download it [here](https://github.com/the-nuclear-confectionery/CCAKE).

If you have any questions, please [contact us](mailto:jnorhos@illinois.edu).

## Roadmap

- 2011: Development started.
- 2013: First (2+1)D simulations including bulk viscosity.
- 2014: vUSPHydro is ready, including Israel-Stewart type shear and bulk viscosity corrections.
- 2020: vUSPHydro renamed to CCake --- Development of conservation of BQS charges starts.
- 2024: Version 1.0.0 of CCake is on the [arXiv](https://arxiv.org/pdf/2405.09648).
- Under development:
    - Support for (3+1)D simulations.
    - Support for parallelism in both CPUs and GPUs.
    - Inclusion of DNMR terms.
- Future:
    - Inclusion of BSQ charge diffusion terms.
    - Adaptive Smoothed Particle Hydrodynamics.

## Publications

<!--Ideal Hydro-->
- [J. Noronha-Hostler, J. Noronha, G. S. Denicol, R. P. G. Andrade, F. Grassi and C. Greiner, "Elliptic Flow Suppression due to Hadron Mass Spectrum," Phys. Rev. C **89**, no.5, 054904 (2014)](https://www.doi.org/10.1103/PhysRevC.89.054904)
<!--Bulk version-->
- [J. Noronha-Hostler, G. S. Denicol, J. Noronha, R. P. G. Andrade and F. Grassi, "Bulk Viscosity Effects in Event-by-Event Relativistic Hydrodynamics," Phys. Rev. C **88**, no.4, 044916 (2013)](https://www.doi.org/10.1103/PhysRevC.88.044916)
<!--Bulk+Shear version-->
- [J. Noronha-Hostler, J. Noronha and F. Grassi, "Bulk viscosity-driven suppression of shear viscosity effects on the flow harmonics at energies available at the BNL Relativistic Heavy Ion Collider," Phys. Rev. C **90**, no.3, 034907 (2014)](https://doi.org/10.1103/PhysRevC.90.034907)
<!--With hadronic resonances-->
- [J. Noronha-Hostler, J. Noronha and M. Gyulassy, "Sensitivity of flow harmonics to subnucleon scale fluctuations in heavy ion collisions," Phys. Rev. C **93**, no.2, 024909 (2016)](https://doi.org/10.1103/PhysRevC.93.024909)
- [P. Alba, V. Mantovani Sarti, J. Noronha, J. Noronha-Hostler, P. Parotto, I. Portillo Vazquez and C. Ratti, "Effect of the QCD equation of state and strange hadronic resonances on multiparticle correlations in heavy ion collisions," Phys. Rev. C **98**, no.3, 034909 (2018)](https://doi.org/10.1103/PhysRevC.98.034909)
- 

<!--## Talks and Posters

- Conference 1: Presenter, Title, Location, Date (pdf link)-->

## Developers

The code started as a post-doctoral research project at the University of São Paulo, Brazil, by Jacquelyn Noronha-Hostler. Since then, a number of people have contributed to the code. The current developers are:

- Jacquelyn Noronha-Hostler, University of Illinois Urbana-Champaign, USA
- Dekrayat Almaalol, University of Illinois at Urbana-Champaign, USA
- Christopher Plumberg, Pepperdine University, USA
- Débora Mroczek, University of Illinois at Urbana-Champaign, USA
- Jordi Salinas San Martin, University of Illinois at Urbana-Champaign, USA
- Willian M. Serenone, University of São Paulo, Brazil and University of Illinois Urbana-Champaign, USA
- Kevin Ingles, University of Illinois Urbana-Champaign, USA
- Isaac Long, University of Illinois Urbana-Champaign, USA
- Fernando Gardim, Universidade Federal de Alfenas, Brazil

### Alumni developers
- Travis Dore, currently at Universität Bielefeld, Germany
- Lydia Spychalla, currently at Pennsylvania State University, USA
- Gabriel S. Denicol, currently at Universidade Federal Fluminense, Brazil
- Jorge Noronha, currently at University of Illinois Urbana-Champaign, USA
- Rone P. G. Andrade, University of São Paulo, Brazil
- Frederique Grassi, University of São Paulo, Brazil


