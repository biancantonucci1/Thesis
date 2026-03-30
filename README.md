# Thesis
Code for my thesis

You should run the scripts in this order for maximum efficientcy:

Real_no_SN_cov -> RealSN+CMB+BAO -> w0wa_NOISY -> wNOISY -> w0wa_lessNOISE -> wNOISYlessnoise

Real_no_SN_cov: The script running the real data without supernova covariances

Real_SN+CMB+BAO: The script running the real data with supernova covariances

w0wa_NOISY: Running w0waCDM mock data realisations with full noise

w0wa_lessNOISE: Running w0waCDM mock data realisations with reduced noise

wNOISY: Running wCDM mock data realisations with full noise

wNOISYlessnoise: Running wCDM mock data realisations with reduced noise

You can either run all the realisations from scratch (may have to run over night), or you can use the h5 files of realisations I have already ran, all in this git. You can change the path and names of output files in the sampler code. If you are using the pre-ran h5 realisations, then make sure the path is adjusted to your computer.
