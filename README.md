# ISOMIP+ with MOM6
The goal of this repository is to centralize experiments setup, tests, issues/difficulties and steps needed during the implementation of ISOMIP+ using MOM6.

## Input files for the ISOMIP+ experimets

* **[Ocean0_COM](https://github.com/gustavo-marques/ISOMIP/blob/master/setup/Ocean0/COM/)**

* **[Ocean0_TPY](https://github.com/gustavo-marques/ISOMIP/blob/master/setup/Ocean0/TPY/)**

* **[Ocean1_COM](https://github.com/gustavo-marques/ISOMIP/blob/master/setup/Ocean1/COM/)**

* **[Ocean1_TPY](https://github.com/gustavo-marques/ISOMIP/blob/master/setup/Ocean1/TPY/)**

* **[Ocean2_COM](https://github.com/gustavo-marques/ISOMIP/blob/master/setup/Ocean2/COM/)**

* **[Ocean2_TPY](https://github.com/gustavo-marques/ISOMIP/blob/master/setup/Ocean2/TPY/)**


## TESTS

Quiet runs:

* **[2D without ice shelf](https://github.com/gustavo-marques/ISOMIP/blob/master/ipynb/quiet_2D_noIS.ipynb)**

* **[2D with ice shelf](https://github.com/gustavo-marques/ISOMIP/blob/master/ipynb/quiet_2D_yesIS.ipynb)**

* **[3D without ice shelf](https://github.com/gustavo-marques/ISOMIP/blob/master/ipynb/quiet_3D_noIS.ipynb)**

* **[3D with ice shelf](https://github.com/gustavo-marques/ISOMIP/blob/master/ipynb/quiet_3D_yesIS.ipynb)**

* **[3D with idealized ice shelf](https://github.com/gustavo-marques/ISOMIP/blob/master/ipynb/quiet_3D_idealIS.ipynb)**

Sponge layer:

* **[2D, cold interior and cold forcing](https://github.com/gustavo-marques/ISOMIP/blob/master/ipynb/sponge_cold.ipynb)**

* **[2D, cold interior and warm forcing](https://github.com/gustavo-marques/ISOMIP/blob/master/ipynb/sponge_warm.ipynb)**

## ISSUES

* **[Spurious velocities in "quiet experiments"](https://github.com/gustavo-marques/ISOMIP/blob/master/ipynb/spurious_velocities_quiet_experiments.ipynb)**

* **[Horizontal pressure gradient errors due to the ice shelf](https://github.com/gustavo-marques/ISOMIP/blob/master/ipynb/horizontal_pressure_gradient_errors_due_to_the_ice_shelf.ipynb)**

* **[Inconsistency in ALE sponge layer](https://github.com/gustavo-marques/ISOMIP/blob/master/ipynb/inconsistency_ale_sponge_layer.ipynb)**

## TO DO LIST
* **[~~Parameterization of vertical mixing under the ice shelf~~](ipynb/vertical_mixing_parameterization.ipynb)**

* **[~~Implementing sponge layer in layer mode~~](https://github.com/gustavo-marques/ISOMIP/blob/master/ipynb/sponge_layer_in_layer_mode.ipynb)**

* **[~~Impose an evaporative flux in the open ocean region to compensate the melt water~~]()**

* **[~~Create a script to generate the requested output~~](ipynb/requested_output.ipynb)**

## Notes from discussions

* **[June 29th 2016](ipynb/notes/29june2016.ipynb)**

* **[August 5th 2016](ipynb/notes/05august2016.ipynb)**

