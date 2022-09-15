## Ruffed grouse automated detection in OpenSoundscape

This repository contains a notebook demonstrating how to use the python packge [OpenSoundscape](opensoundscape.org) to detect ruffed grouse (*Bonasa umbellus*) in audio recordings. It is associated with an article in review in the Wildlife Society Bulletin (Lapp et al. 2022). The Jupyter notebook reproduces the evaluation of the recognition method on a validation set. It could also be used to analyze new audio data with minor adaptations. 

The audio data and annotations used in the notebook are available on Dryad ([doi:10.5061/dryad.hdr7sqvmc](https://doi.org/10.5061/dryad.hdr7sqvmc)). However, this notebook can also be run without downloading the data by using the labels and pre-computed outputs of the model, which are included in this repository. 

A description of the automated recognition method can be found in the manuscript. 

Finally, this repository contains a dataset of ruffed grouse detections from avian point counts conducted in 2020 (Parker et al. 2020) in the folder `point_count_data`. Lapp et al. 2020 compares these point count survey detections with detections by automated detection on ARU recordings. For the full ARU audio dataset or resulting detections please contact Sam Lapp. 

### Works Cited:

Lapp, S., Larkin, J., Parker, H., Larkin, J., Shaffer, D., Tett, C., McNeil, D., Fiss, C., Kitzes, J., In Review. "Automated recognition of Ruffed Grouse drumming in field recordings".  Wildlife Society Bulletin. 

Parker, H. A., J. T. Larkin, D. Heggenstaller, J. Duchamp, M. C. Tyree, C. S. Rushing, E. Just Domoto, and J. L. Larkin. 2020. Evaluating the impacts of white-tailed deer (Odocoileus virginianus) browsing on vegetation in fenced and unfenced timber harvests. Forest Ecology and Management 473:118326.
