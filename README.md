
# Neuropixels-NHP-hardware

![Neuropixels NHP](/docs/images/Neuropixels%20NHP%20-%2045mm.png)

This repository and the associated wiki contain a collection of open-source hardware designs and documentation of methods for using silicon probes like the Neuropixels-NHP in nonhuman primates (NHP) and other large animal models. The experience documented here is currently focused on acute recordings, and information regarding semi-chronic recordings will be added once this testing is complete. We welcome pull requests for additional designs and information from the community. 

Using silicon probes in NHP involves a different set of design constraints from single electrodes or wire-based linear arrays (e.g.: S-probes, V-probes). In particular the probe shank is typically shorter (currently 45mm and 25mm for the two variants of Neuropixels NHP), and the mechanical properties of silicon are different from tungsten or stainless steel. Commercially-available electrode drive systems (such as Narishige, NaN, Thomas, FHC, Alpha Omega, etc.) are designed for inserting long, metal-based electrodes. Using these drives with silicon arrays like the Neuropixels NHP requires mechanical adapters, and careful consideration of the insertion mechanics. 

This repository contains:
1. CAD models, 3D models, and drawings for mechanical adapters for the Neuropixels-NHP probe for a variety of commercially available drives.
2. ![Neuropixels NHP wiki](https://github.com/etrautmann/Neuropixels-NHP-hardware/wiki) - describing design constraints and considerations for different experimental use cases. 

Most documentation lives on the wiki

Some examples:


### Custom linear rail guide for deep insertion

![cousteau_chamber_with_rail_shuttle_-_grid_mk_7_2022-May-03_04-45-58PM-000_CustomizedView28366638586](https://user-images.githubusercontent.com/768056/199261985-25c108b2-2d36-405a-8038-47a3bb62a5f5.png)

### NAN drive adapter


![NAN dovetail rod mount - concept 2 - 3](https://user-images.githubusercontent.com/768056/199263060-92165520-8abc-41f7-8434-deb7cd273246.png)

