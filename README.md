things.stimuli
==============================

The current image dataset (which includes >4k images representing 720 image concepts) is a subset of the THINGS images, a freely available dataset of 26k images of 1,854 object concepts currated systematically from everyday American English language by the THINGS Initiative (https://things-initiative.org/). 

The THINGS images (saved under ``images_fmri.zip``) have an Attribution NonCommercial-ShareAlike CC BY-NC-SA license. The copyright of each image belongs to the owner(s) of the image. Images are made available for research purposes only, according to fair use. Commercial use, reproduction or distribution of the images, or any modification thereof, is not permitted without the explicit consent of the owner(s).

To use the images, unzip the ``images_fmri.zip`` file at the root of the current repository. You will be prompted for a **password** provided inside the ``password_images.txt`` file.

By using this password to unzip the images, you confirm that you have read and agree to the license agreement (``LICENSE.txt``).

In particular, you agree to **use the images only for research and non-commercial purposes**, and you agree **not to distribute or alter them without permission from the owner(s) of the images**.

Unzip ``images_fmri.zip`` in place; you will be prompted for a password:
```bash
unzip images_fmri
Archive:  images_fmri.zip
[images_fmri.zip] images_fmri/acorn/acorn_01b.jpg password:
```

Note that the same password is used for the ``images_test_fmri.zip`` and ``images_catch_fmri.zip`` files; images saved under ``images_test_fmri.zip`` are covered by the same license as ``images_fmri.zip`` images.


**Please cite the following paper when using the THINGS images:**

Hebart M.N., Dickter A.H., Kidder A., Kwok W.Y., Corriveau A., Van Wicklin C., Baker, C.I. THINGS: A database of 1,854 object concepts and more than 26,000 naturalistic object images. PLoS ONE 14(10): e0223792. (2019) https://doi.org/10.1371/journal.pone.0223792


### Image Annotations

Annotations saved in annotations/task-things_desc-manual_annotation.tsv fall under a CC0 license. 

Annotations saved under things.stimuli/annotations/THINGS+ were retrieved from the THINGS object concept and object image database (https://osf.io/jum2f/) and fall under an Attribution CC BY license. This licence lets you distribute, remix, modify, and buil upon a given work, even for commercial purposes, as long as credit is given to the original creators.

The concreteness ratings used in the creation of the THINGS+ database were taken from “Brysbaert, M., Warriner, A.B., & Kuperman, V. (2014). Concreteness ratings for 40 thousand generally known English word lemmas. Behavior Research Methods, 46, 904-911.”

COCA word frequency data published with the THINGS+ database are from the Corpus of Contemporary American English (COCA). Modified word frequency data was published by THINGS+ with permission from Mark Davies (https://www.wordfrequency.info).

Please cite the following two papers when using the THINGS+ image annotations:

Hebart M.N., Dickter A.H., Kidder A., Kwok W.Y., Corriveau A., Van Wicklin C., Baker, C.I. THINGS: A database of 1,854 object concepts and more than 26,000 naturalistic object images. PLoS ONE 14(10): e0223792. (2019) https://doi.org/10.1371/journal.pone.0223792

Stoinski, L.M., Perkuhn, J. & Hebart, M.N. THINGSplus: New norms and metadata for the THINGS database of 1854 object concepts and 26,107 natural object images. Behav Res 56, 1583–1603 (2024). https://doi.org/10.3758/s13428-023-02110-8

