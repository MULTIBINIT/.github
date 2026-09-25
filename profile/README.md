# MULTIBINIT

**Second-principles models for large-scale materials simulations**

<p><img src="uliege-logo.png" alt="Université de Liège" width="300"></p>

MULTIBINIT is a software platform for automatically constructing second-principles models from first-principles calculations and using them for large-scale materials simulations. These effective models are designed to reduce computational cost while retaining the accuracy of their first-principles reference.

## Core modules

- [MULTIBINIT-Lattice](https://multibinit.github.io/docs/lattice/) — constructs atomic potentials and forms the foundation of the platform.
- [MULTIBINIT-LWF](https://multibinit.github.io/docs/lwf/) — lattice dynamics using Lattice Wannier Functions (LWFs).
- [MULTIBINIT-Spin](https://multibinit.github.io/docs/spin/) — atomistic spin dynamics based on extended Heisenberg and Landau–Lifshitz–Gilbert models, including coupled spin–lattice dynamics.

## Ecosystem

The wider ecosystem includes [ABINIT](https://github.com/MULTIBINIT/abinit) for first-principles calculations; [Agate](https://github.com/MULTIBINIT/agate) and [QAgate](https://github.com/MULTIBINIT/qAgate) for visualization and post-processing; [TB2J](https://github.com/MULTIBINIT/TB2J) for magnetic-interaction calculations; [LaWaF](https://github.com/MULTIBINIT/lawaf) for Wannier functions and compact atomic-potential models; and [Matjes](https://github.com/MULTIBINIT/Matjes) for magnetic simulations. Workflow and interface projects include [pymultibinit](https://github.com/MULTIBINIT/pymultibinit), [multibinit-lammps](https://github.com/MULTIBINIT/multibinit-lammps), and [atomchain](https://github.com/MULTIBINIT/atomchain).

## Resources

- [Documentation and tutorial](https://multibinit.github.io/docs/)
- [Database of MULTIBINIT potentials](https://multibinit.github.io/database/)
- [Publications](https://multibinit.github.io/publications/)
- [All MULTIBINIT GitHub repositories](https://github.com/orgs/MULTIBINIT/repositories)

## Contributing

Use the Issues and Pull Requests in the relevant repository to report problems or propose improvements; see that repository for component-specific guidance.


