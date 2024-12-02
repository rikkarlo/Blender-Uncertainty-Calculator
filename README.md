Blender plugin for uncertainty assessment of hypotetical 3D reconstruction of lost or never built architecture

[Download the plugin from here!](https://github.com/rikkarlo/Blender-Uncertainty-Calculator/releases/download/v2.3.1/AU_VR.py)


How to install: Edit -> Preferences -> Add-ons -> Install from Disk -> Browse to the "AU_VR.py" python script downloaded from the link above -> the plugin will appear on the sidebar in the newly created "Uncertainty" tab.

<img src="https://github.com/user-attachments/assets/6e354786-3ca5-4855-a36d-bbe82779feaf" alt="install plugin" width="400" height="">


When exporting from another software pay particular attention to exporting close watertight manifold solids. If the solid meshes have unwelded vertices the volume calculation might give unexpected results (if a very minor part of the edges is unwelded the volume might still be calculated correctly, but it is not guaranteed, so to avoid any error it is better to check import-export options and test various formats) in the following image you can see the suggested option to export from McNeel Rhinoceros to Blender in glTF and Glb exchange formats.
<img src="https://github.com/user-attachments/assets/a8ade583-57fb-46f3-b462-4c6bb5088957" alt="export from rhino to blender" width="600" height="">


The following image explains the plugin tabs and buttons:
<img src="https://github.com/user-attachments/assets/ee99f5c0-d2e1-42e5-8321-436bc8fe5541" alt="Tutorial" width="800" height="">

Use the following image as an aid to assign the correct Uncertainty Level:
<img src="https://github.com/user-attachments/assets/14ff314c-132e-4539-b206-ca6142247d37" alt="YES/NO Flow Chart" width="800" height="">

This is an example of false colour view for the dissemination of the uncertainty of an hypotetical 3D reconstruction:
<img src="https://github.com/user-attachments/assets/0b6edead-6975-40bd-a83e-61b7f02e4e50" alt="Example of false colour view" width="400" height="">

Refer to the following table for the full description of each Level of Uncertainty (Remember that each level description is also accessible directly from the plugin by hovering the mouse on each button):
<img src="https://github.com/user-attachments/assets/1b5756ad-88ba-42d3-89b5-e38b6db0fbc5" alt="Scale of Uncertainty Levels descritions" width="700" height="">

The mathematical formulas used to calculate the AU_V and AU_VR are reported below:
<img src="https://github.com/user-attachments/assets/ac0c8f2c-1316-43b7-9ea1-061d6a008e3f" alt="AUV_AUVR Formulas" width="500" height="">

It is important to note that higher uncertainty in hypothetical reconstructions does not imply lower scientific value; well-documented high-uncertainty models can enhance understanding by critically integrating diverse sources and advancing scientific discourse. Nevertheless since the two formulas AU_V and AU_VR represents the extreme synthetis of the complex process of Uncertainty assessing, they have not to be considered self sufficient, but complementary to a proper documentation and visualization of the hypotetically reconstructed case study.
 

BIBLIOGRAFIC REFERENCES:

- Foschi, R., Fallavollita, F., & Apollonio, F. I. (2024). Quantifying Uncertainty in Hypothetical 3D Reconstruction—A User-Independent Methodology for the Calculation of Average Uncertainty. Heritage, 7(8), 4440-4454. https://doi.org/10.3390/heritage7080209
- Apollonio, F. I., Fallavollita, F., Foschi, R., & Smurra, R. (2024). Multi-Feature Uncertainty Analysis for Urban-Scale Hypothetical 3D Reconstructions: Piazza delle Erbe Case Study. Heritage, 7(1), 476-498. https://doi.org/10.3390/heritage7010023
- Apollonio, F. I., Fallavollita, F., & Foschi, R. (2019, October). The critical digital model for the study of unbuilt architecture. In Workshop on Research and Education in Urban History in the Age of Digital Libraries (pp. 3-24). Cham: Springer International Publishing. https://doi.org/10.1007/978-3-030-93186-5_1
