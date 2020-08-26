# Active-Stabilization-Test-Data

This is example data which can be used to evaluate the performance of an active stabilised microscope.

The first part constitutes an example of readout values. Shown is 1/1000 points. Standard deviation shown for x/y/z shoud be < 1 nm.

Second, is simulated data which demonstrates the negative effect of drift (or residual uncorrected drift) on the cummalative pointillistic pattern - characteristic of single-molecule localization microscopy. Load data in ThunderSTORM.

Third, shows that post-acquisition drift correction is not required. Gold nanorods were acquired for ~6 hours and do not show residual drift.
Applying drift correction, either using Redundant cross-correlation or fiducial correction, does not demonstrate an improvement. Load data in ThunderSTORM.

Fourth [Average Performance on different substrats (SI Fig 2)], is the Average sample stability on different substrats: clean glass, plasma-cleaned glass and biotinylated supported lipid bilayers.This indicates that the bulk of the BSA-biotin remains attached to the substrate; or that the biotin-streptavidin network in contact with the fiducial, operating as a whole, remains stable throughout. 
