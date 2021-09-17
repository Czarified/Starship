# Starship
Starship OpenVSP models and related material

This work is part of course completion by the Owner, as part of a graduate program
from the University of Texas at Arlington; Course AE5368 Flight Vehicle Synthesis.

Please see the license for details of use, distribution, and repoduction.

To cite this work, please see the "Cite this repository" button. The Zotero plugin
should also automatically be able to import it as a reference.

---

## Installation

If you wish to use any of these models for additional analyses, or conversion to
other formats, simply install [OpenVSP](https://github.com/OpenVSP/OpenVSP), download
the model of your choosing (the vsp3 files) or clone the whole repository,
and open the model directly within OpenVSP.


## Model Quality

The `Starship.vsp3` model was originally intended just for structural layout. It was
then used for Loads Model meshing, manually. This configuration is from an older
variant of Starship with 3 fins, and contains no SuperHeavy booster.

The `Starship_HLS.vsp3` model represents the Lunar lander variant of Starship
as part of NASA's HLS Program. Geometry in this model should be suitable for
3d printing, internal layout conceptualization, and mass properties analyses.
Use of this model in VSPAero or CFD codes will likely require further refinement
and adjustment for water-tight boundaries.
