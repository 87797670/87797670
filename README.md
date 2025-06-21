## Hello 👋

This site collects a bunch of info related to what I learn as I build and maintain my HomeLab.

### Hardware

- 1x <a href=“https://turing.com”>Turing Machines</a> TuringPi2
- 4x <a href=“https://turing.com”>Turing Machines</a> RK1 SoM
- 4x NVMe (one per RK1)
- 1x SSD (connected to the Node 3 SATA controller on the TuringPi2)

### Software

- Talos (min ver 1.10.x to allow partitioning/sharing of the single NVMe drive for SYSTEM and DATA)
- Kubernetes managed by Flux through a private Repo on GitHub
- Longhorn for PVCs


