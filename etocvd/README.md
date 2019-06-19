# Eye-Tracking of Color Vision Deficiencies

This is the README file of the [Eye-Tracking of Color Vision Deficiencies (ETTO)](https://journals.sagepub.com/doi/full/10.1177/2041669519841073) dataset.
All the project files are in the following subdirectories:

* *ETOCVD_ALLFIXATIONLOCS* - Contains all the fixation point maps acquired during the first 3 seconds of image observation. The tests have been performed with observers not affected by any color vision deficiency (*fixationLocsNoCVD* directory), affected by protanopia (*fixationLocsCVD_P* directory) and affected by deuteranopia (*fixationLocsCVD_D* directory). For each of the three directories there are two subdirectories, one containing the full fixation point maps (*full* directory) and one containing the fixation point maps obtained excluding the first 200 ms of observation (*excluding_200ms* directory)
* *ETOCVD_ALLFIXATIONMAPS* - Contains all the fixation maps (obtained by smoothing the fixation point maps), which show the most salient areas of the respective images. Directory gerarchy is identical to that of *ETOCVD_ALLFIXATIONLOCS*
* *ETOCVD_ALLSTIMULI* - Contains three subdirectories: *images* contains the unmodified images shown to all observers, *imagesRecoloredCVD_P* contains the images enhanced for observers affected by protanopia and *imagesRecoloredCVD_D* contains the images enhanced for observers affected by deuteranopia.

This directory also contains the paper in PDF format (*Image Content Enhancement Through Salient Regions Segmentation for People With Color Vision Deficiencies.pdf*).

If you use ETTO Data in your experiments please cite the reference main article as follows:

Authors: "Bruno, Alessandro and Gugliuzza, Francesco and Ardizzone, Edoardo and Giunta, Calogero Carlo and Pirrone, Roberto"
Title: "Image Content Enhancement Through Salient Regions Segmentation for People With Color Vision Deficiencies"
Journal: "i-Perception" Vol.10 No.3 Year 2019. SAGE Publications Sage UK: London, England
