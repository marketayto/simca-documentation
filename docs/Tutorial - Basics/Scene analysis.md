---
sidebar_position: 2
---

# Feature A : Scene Analysis

The Scene analysis tab is used to **load & display scene caracteristics**.

![layout scene tab](/img/layout_scene_tab.svg "Mask design tab")

## 1 - Settings

Located on the left side of the application window.

Includes :

- `scenes directory` : path to the scenes directory. All scene data should be stored here.
    - click on the button if you change the scenes directory path

- `available scenes` : ComboBox displaying the scenes avalaible in the scenes directory

- `loaded scene dimensions` : These values are displayed once the scene is loaded 
    - `dimension along X` : dimension of the scene in the X direction (main spectral dispersion direction)
    - `dimension along Y` : dimension of the scene in the Y direction (perpendicular to spectral dispersion direction)
    - `number of spectral bands` : number of spectral bands in the loaded scene
    - `minimum wavelength` : minimum wavelength, usually corresponds to the spectral band n°0
    - `maximum wavelength` : maximum wavelength, usually corresponds to the last spectral band
  
## 2 - Load scene button

By clicking on this button, the scene selected in the `available scenes` ComboBox is loaded by the application.


## 3 - Display windows

Located on the right side of the application window.

**Once a scene is loaded**, one can inspect the spatial and spectral content of the scene.

### Spectral images

![SCene layout 2](/img/layout_scene_2.svg)

### Compare Spectrums

![SCene layout 2](/img/layout_scene_3.svg)

### Labelisation map

![SCene layout 2](/img/layout_scene_4.svg)

### Labelisation Histogram

![SCene layout 2](/img/layout_scene_5.svg)

