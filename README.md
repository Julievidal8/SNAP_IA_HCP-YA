# SNAP_IA_PROTOCOL
Those analyses follow a protocol named SNAP-IA

Citation: Vidal, J. P., Forno, G., Hornberger, M., Cuadra, M. B., Danet, L., Kumar, V. J., ... & Barbeau, E. J. (2026). Standardized methodology for assessing the presence, variants and area of the interthalamic adhesion using anatomical MRI (SNAP-IA): multicentric validation on 565 healthy individuals and multiple neurological disorders. Brain Structure and Function, 231(3), 42.
![image](https://github.com/user-attachments/assets/efd2737d-d364-465e-80fd-dbe729bcd5e1)

# SNAP_IA_HCP-YA
Interthalamic adhesion's mask on the HCP Young Adult (unrelated) dataset

All associated T1w MRIs are publicly available: [https://openneuro.org/datasets/ds000030/versions/00016](https://www.humanconnectome.org/study/hcp-young-adult)

The HCP-YA_overlay_IA_masks.zip file contains all the IA's masks by subject. Those masks are the overlap of two raters' segmentation when the Dice coefficient was superior to 0.80, demonstrating high agreement.

HCP_PVE_results.ods file is the output sheet of the FSL FAST segmentation overlapped with the IA's mask to estimate the partial volume effect (PVE, i.e mean rate of CSV).

SNAP_IA_HCP-YA_github.ods is the file with the IA's characterization, including its presence or absence, anatomical variant, and area corrected by the PVE.
