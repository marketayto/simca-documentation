---
sidebar_position: 3
---

# Feature B : Optical Design

The optical Design tab is used for quick evaluation ofthe optical system caracteristics (spectral dispersion & distorsions).

![layout scene tab](/img/layout_optical_design_tab.svg "Mask design tab")


## 1 - System Settings 


![Docusaurus logo](/img/mask_to_detector.svg)

Located on the left side of the application window.

Includes :


- **infos** : general informations about the optical system
    - *system name* : name of the studied system
    - *results directory* : path to save config file and optical simulations results
- **system architecture** : parameters that define the optical system between the mask (where the filtering takes place) and the detector. 
    - *focal lens F* [in micrometers]
    - *dispersive element* :
        - *A (only when prism is selected)* : apex angle of the prism [in degrees]
        - *m (only when grating is selected)* : considered order of diffraction [no units]
        - *G (only when grating is selected)* : grating lines density [lines/mm]
        - *delta alpha c* [in degrees]
        - *delta beta c* [in degrees]
        - *wavelength center* [in nm]
- **detector** : parameters that define the detector grid
- **SLM** : parameters that define the mask grid 
- **spectral range**: the spectral boundaries of the system and the number of spectral bands to consider

## 2- Run Optical Design button

By clicking on this button, a `CassiSystem` instance is created. 

For each considered wavelength, the mask grids are propagated onto the detector.

## Display

Located on the right side of the application window.

Used to analyse the mask grid object and its images in the detector plane.

### Mask grid 

![Docusaurus logo](/img/input_grid.svg)

### Propagated mask

Spectral images of the in put mask grid for the minimum, maximum, and center wavelength.

**ATTENTION : center wavelength different from system architecture center wavelength**

![Docusaurus logo](/img/propagated_grids.svg)

### Distortion maps

Get qualitative and quantitative distortion data :

![Docusaurus logo](/img/distortion_maps.svg)
