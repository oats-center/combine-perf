# combine-perf

This is the repository for hosting a set of Jupyter notebooks for demonstrating the data processing software for the Journal of ASABE manuscript: **A New Methodology For Combine Performance Analyses in Wheat Harvests With GNSS Data**.

## Software Dependency

* `python==3.9.1`
* `pandas==1.4.4`
* `geopandas==0.9.0`
* `numpy==1.21.5`
* `shapely==1.7.1`
* `sklearn==1.1.2`
* `scipy==1.7.3`

## Organization

There are a total of 8 Jupyter notebooks. Each of them corresponds to different parts of the Methodology section in the paper.

### `step0-preprocessing-get-data.ipynb`

This corresponds to steps described in *Raw Positioning Data Preprocessing*.

### `step1-imm.ipynb`

This corresponds to the IMM algorithm utilized in *Step 1: Removal of Random Noise V(k)*. It specifies the state-space models and how IMM is run.

### `step2-classification.ipynb`

This corresponds to the steps taken in *Combine State Classification* that employs ST-DBSCAN clustering.

### `step3-smooth-state-based.ipynb`

This corresponds to how a Kalman-based smoother is set up and run in *State-Based Track Smoothing*.

### `step4a-optimization.ipynb`

This corresponds to the steps taken in *Optimized Solution Search*.

### `step4b-effective-swath-estimation.ipynb`

This corresponds to computations of metrics defined in *Part III: Wheat Harvest Performance Metrics*.

### `step5a-efficiency-calculations.ipynb`

This corresponds to more computations of metrics defined in *Part III: Wheat Harvest Performance Metrics*.

