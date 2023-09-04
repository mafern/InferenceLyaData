# InferenceLyaData
Emulator files and MCMC chains from arXiv:xxxx.xxxxx, '*Cosmological Constraints from the eBOSS Lyman-a Forest using the PRIYA Simulations*'

## Contents

Included in the Emulator_Files directory are all of the necessary files to train a multi-fidelity emulator for the Lyman-a forest flux power spectrum and mean temperature of the IGM (go to [lya_emulator_full](https://github.com/sbird/lya_emulator_full) for the code needed to do this):
- LF/HF flux power files (*mf_emulator_flux_vectors_tau1000000.hdf5*, *hires/mf_emulator_flux_vectors_tau1000000.hdf5*)
- LF/HF mean temperature files (*emulator_meanT.hdf5*, *hires/emulator_meanT.hdf5*)
- LF/HF parameter JSON files (*T0emulator_params.json*, *emulator_params.json* and *hires/T0emulator_params.json*, *hires/emulator_params.json*)
- LF/HF leave-one-out errors (*loo_t0.hdf5*, *loo_fps.hdf5* and *hires/loo_t0.hdf5*, *hires/loo_fps.hdf5*)
- and a directory containing a pre-trained multi-fidelity emulator (optimized hyperparameters for the GP framework), *trained_mf*

Included in the Chains directory are the MCMC chains for the main results from the paper, in three sub-directories: *meant-only*, *fps-only*, and *fps-meant*.
