# Leader Cell Integrity During Gonadogenesis — Interactive Simulation

An interactive browser-based simulation exploring how active nuclear positioning and actomyosin cortical contractility cooperate to maintain distal tip cell (DTC) integrity during *C. elegans* gonad morphogenesis.

## Based on

**Agarwal P, Berger S, Shemesh T, Zaidel-Bar R.** Active nuclear positioning and actomyosin contractility maintain leader cell integrity during gonadogenesis. *Current Biology* 34(11):2373–2386.e5 (2024).  
DOI: [10.1016/j.cub.2024.03.049](https://doi.org/10.1016/j.cub.2024.03.049)

## What it models

During *C. elegans* gonad morphogenesis, the DTC migrates along a stereotyped path — first ventrally, then executing a dorsal U-turn — to shape the gonad arms. Agarwal et al. (2024) discovered that:

1. The KASH-domain protein UNC-83 links the DTC nucleus to kinesin-1 motors on a polarised acentrosomal microtubule network, actively keeping the nucleus at the migratory front against frictional drag.
2. Actomyosin cortical contractility (NMY-2) maintains cell shape under mechanical load.
3. **Neither mechanism alone is essential** — each compensates for the other.
4. **Loss of both** causes the DTC to stretch catastrophically during the U-turn, fragment into a nucleated cell and an enucleated cytoplast, and produce gonad bifurcation.

## Features

- **Four genetic conditions**: Wild-type, *unc-83* RNAi (nuclear positioning knockdown), *nmy-2* RNAi (actomyosin knockdown), and double knockdown
- **Continuous parameter control**: adjust kinesin-1 motor force and cortical contractility via sliders
- **Real-time visualisation**: microtubule network, actomyosin cortex, nuclear position, cell deformation, germ cells, and fragmentation
- **Live readouts**: nuclear lag, cell stretch, path curvature, migration progress
- **Event log**: tracks key events (U-turn entry, nuclear drift, stretching, fragmentation)

## Usage

Open `index.html` in any modern browser. No dependencies or build step required.

Or visit the live version: [GitHub Pages link]

## Technical notes

This is a **qualitative educational simulation**, not a quantitative biophysical model. The physics are simplified to capture the conceptual relationships described in the paper — active nuclear positioning resists frictional forces, cortical contractility resists cell elongation, and their combined loss produces fragmentation during high-curvature migration.

## License

Educational use. Please cite the original paper (Agarwal et al., 2024) when referencing the biology.
