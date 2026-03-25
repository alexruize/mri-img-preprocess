# mri-img-preprocess

Python scripts to pre-process medical images of the human body for ingestion into real-time 3D rendering software like TouchDesigner. 

<img width="1727" height="971" alt="a_vm1110" src="https://github.com/user-attachments/assets/c1a5ce4a-13e6-4407-9477-f2e75235c82b" />

This code allows users to download, clean and stitch together MRI and CT scan segment images from the following public projects:

1) **OpenNeuro**: A free and open platform for validating and sharing BIDS-compliant MRI, PET, MEG, EEG, and iEEG data.

2) **The Human Visibility Project**: A National Library of Medicine project with publicly-available complete, anatomically detailed, three-dimensional representations of a human male body and a human female body.  

Files prefixed with `mri` are intended to be used with the OpenNeuro project, wnd files prefixed with `human-visibility` are to be used for the HV project. 
