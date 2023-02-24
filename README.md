# Development repository for the updated pyiron_atomistics documentation
Please checkout our discussion https://github.com/pyiron/pyiron_atomistics_docs/discussions 

This repository was created as result of the documentation Hackathon https://pad.gwdg.de/lhITAHqIQ-CcEwC5DMmEBw?both

# Current proposed structure
- landing page
- Installation
    - How to add LAMMPS, VASP, SPHInX
- How-To / [FAQ](https://pyiron.readthedocs.io/en/latest/source/faq.html)
    - Less than 5 lines -> How-to; otherwise tutorial
- Tutorial
    - Copy from the existing page from the [web](https://pyiron.readthedocs.io/en/latest/source/examples.html) 
    - [potentials-workshop-2022](http://pyiron.org/potentials-workshop-2022/intro.html) 
    - [potentials-workshop-2021](https://github.com/pyiron/potentials-workshop-2021)
    - [swimm-workshop-2021](https://github.com/pyiron/swimm-workshop-2021)
    - [phasediagram-workshop-2020](https://pyiron.org/phasediagram-workshop-2020/Introduction.html)
    - [pyiron-virtual-workshop-2020](https://pyiron.org/pyiron-virtual-workshop-2020/README.html)
    - [NIST-workshop-2020](https://github.com/pyiron/NIST-workshop-2020)
    - [ADIS-workshop-2020](https://github.com/pyiron/ADIS-workshop-2020)
    - [handbook](https://github.com/eisenforschung/pyiron-meeting-mpie/tree/master/handbook)
    - [high entropy elastic constants](https://github.com/pyiron-dev/pyiron-no-file-access)
    - [phono3py](https://github.com/pyiron-dev/phono3py_pyiron)
    - [quantum-espresso](https://github.com/pyiron-dev/pyiron-quantum-espresso)
    - [cp2k](https://github.com/pyiron-dev/pyiron-cp2k)
    - [randspg](https://github.com/pyiron-dev/pyiron-randspg)
    - [fit moment tensor potential](https://github.com/pyiron-dev/pyiron-mlip)
    - [aimsgb](https://github.com/pyiron-dev/pyiron-aimsgb)
    - [lammps script](https://github.com/pyiron-dev/pyiron-free-energy)
    - [fit lennard jones](https://github.com/pyiron-dev/pyiron-fitting-example)
    - [langevin](https://github.com/pyiron-dev/pyiron-md-example)
- API Reference
- Developer guide
- Application Topics
    - Use jupyter notebooks
    - Impressive physics in application topics
    - [cm-journal-club](https://github.com/eisenforschung/cm-journal-club)
    - Papers with pyiron
        - [melting point](https://github.com/pyiron/pyiron_meltingpoint)
        - [DFT uncertainty](https://github.com/pyiron/pyiron-dft-uncertainty)
        - [md montecarlo](https://github.com/pyiron/pyiron_md_montecarlo)
        - [generalized dipole](https://github.com/pyiron/pyiron_generalized_dipole)
        - [spin_space_averaging](https://github.com/pyiron/spin_space_averaging)
        - [magnesium-mtp-training-data](https://github.com/eisenforschung/magnesium-mtp-training-data)

# Topics to include:

- Structure Generation 
    - grainboundaries 
    - sqs structures
    - ASE structures
    - water structure 
    - Randspg structures 
    - Analysis:
        - CNA, aCNA
        - Vacancy
        - Neighbours

- Simulation Codes
    It's important to also address this to advanced users of resp. code
    - LAMMPS 
    - Sphinx 
    - VASP 
    - GPAW 

- Material Properties 
    - Quasi-harmonic Approximation 
    - Elastic Constants 
    - Murnaghan 
    - Stacking faults 
    - Paramagnetic structures 
    - Phase diagrams 
    - interface energies 
    - solutes (interstitial & substitutional) at grainboundaries 
    - fitting machine learning potentials 
    - thermodynamic integration 

# Tasks
* [ ] Revise tutorials
* [x] Set-up repository
* [ ] We work on discussion-basis - We set up meetings as we feel it's needed

# Lessons Learned
- Use a separate repository for the documentation process
- Format `.rst` -> `.md`
- Documentation meeting at least once or twice a year
