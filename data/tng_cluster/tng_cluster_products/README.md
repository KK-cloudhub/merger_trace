## TNG-Cluster Data Products

This directory contains the data products generated from the **TNG-Cluster** simulation using our analysis pipeline.

### Files Overview

#### `BCG_offset_matrix_x/y/z.csv`
- Stores the BCG (Brightest Cluster Galaxy) offsets for each halo along the **x**, **y**, and **z** projections.
- `sigma_{number}_projectx/y/z`: the number indicates the **Gaussian smoothing scale** (in pixels) used when computing the BCG offset.

#### `feats_labels_dict_tngcluster.pkl`
- Pickle file storing the **extracted features** and **corresponding labels** for each halo and snapshot.

#### `sfr_tracking.pkl`
- Contains the **average star formation rates** (SFRs) of the 352 target halos from **snapshot 72 to 99**.

#### `sfr_curve_summary.csv`
- Summarizes the **curvature** of star formation histories for each halo.
- The `Norm` column indicates that the SFR curves are **normalized by each halo’s average SFR**.

#### `fof_halo_to_sub{snap}.csv`
- Stores basic information of the progenitors at certain snapshot for 352 primary zoom-in targets in TNG-Cluster at redshift 0.

---

If any files or naming conventions are unclear, feel free to check the associated scripts or contact the maintainers.
