# SNAP_IA_HCP-YA
Interthalamic adhesion's mask on the HCP Young Adult (unrelated) dataset

All associated T1w MRIs are publicly available: [https://openneuro.org/datasets/ds000030/versions/00016](https://www.humanconnectome.org/study/hcp-young-adult)
Those analysis follows a protocol named SNAP, which is in preparation.

The HCP-YA_overlay_IA_masks.zip file contains all the IA's masks by subject. Those masks are the overlap of two raters' segmentation when the Dice coefficient was superior to 0.80, demonstrating high agreement.

HCP_PVE_results.ods file is the output sheet of the FSL FAST segmentation overlapped with the IA's mask to estimate the partial volume effect (PVE, i.e mean rate of CSV).

SNAP_IA_HCP-YA_github.ods is the file with the IA's characterization, including its presence or absence, anatomical variant, and area corrected by the PVE.
