# TrajectorySelection
This is a matlab script that allows selection and display of the TGMM trajectories (TGMM software 10.1038/nprot.2015.111)

Version 1.0 2018

Leila Muresan lam94@cam.ac.uk

License: Apache 2.0

Parameters to be updated:
TGMMpath   - folder containing the TGMM software 10.1038/nprot.2015.111 (e.g. 'D:\TGMM\Supplementary_Software_6\')
startT -  first time point of interest for trajectories 
endT - last time point of interest for trajectories
time - time point to make selection
timeShape - time point to recognize the shape of the embryo. If -1, then not used
hollow - Experimental. If the strucuture hollow set to 1. Tries to eliminate points on the far side of the embryo
pt -  folder with TGMM data, e.g. 'D:\TGMM\Data\GMEMtracking3D_2018_6_14_13_10_55\XML_finalResult_lht' 
basename -the first part of TGMM file-names, e.g.  'D:\TGMM\Data\TGMMruns\GMEMtracking3D_2017_11_9_13_24_26\XML_finalResult_lht\GMEMfinalResult_frame'


