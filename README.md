# AMEGO-X-AstroPix-SingleTriggerBG
Background simulations for astropix (0.5 mm pixel size) with single trigger

Detector configuration files: https://github.com/ComPair/Geometry/tree/master/AMEGO_Midex/TradeStudies/Tracker/BasePixelTracker_05mm_SingleTrigger

The directory `tra_files` contains the `.tra` output from **60 seconds** worth of background simulations **with the ACD veto on**.

The directory `tra_files_noVeto` contains the `.tra` output from **60 seconds** worth of background simulations **with the ACD veto switched off**.

The directory `sim_files` contains the `.sim` output from **10 seconds** worth of background simulations.

Note: The (prompt) **trapped hadronic** and **trapped leptonic** background files are retained here only for historical reasons. These two components contribute mainly during the SAA passage when the detector is expected to be off, and thus **do not contribute to the overall background rates**. They are simulated because they do contribute to the **activation** background. They have been removed from the summary files `FullBG_10s.sim.gz` and `FullBG_60s.tra.gz`. 


