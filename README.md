# ONiT: Annotated Dataset Version 1
This is the first version of our annotated image dataset extracted from the ONiT corpus during the first project year (Link: [https://onit.oeaw.ac.at/](Ottoman Nature in Travelogues project)). The images are annotated with [https://iconclass.org/](ICONCLASS) notations of animals (25F), plants/vegetation (25G), landscapes (25H), and maps (25A). 

This repository contains:
**1. Two variants of the multi-label annotated dataset:**
1. A detailed version that contains 592 annotated images. We do not recommend using this version for Machine Learning (ML) because the annotations do include material that is too fuzzy for training tasks.
2. A more robust training dataset with 407 images that contains 234 representations of animals (on 57% of the images), 177 plants/vegetation (on 43% of the images), 167 landscapes (on 40% of the images), and 22 maps (on 5% of the images). The annotations include only representations of the classes with distinct visual features, which are more suitable for ML training tasks.
**2. An extended version of the training dataset including bounding boxes for object detection tasks.**

# References
This dataset was published in context of the short presentation held at the DH 2023 conference in Graz, AT:

```
@inproceedings{vignoli_revolution_nodate,
	title = {Revolution or {Evolution}? {AI}-{Driven} {Image} {Classification} of {Historical} {Prints}},
	shorttitle = {Revolution or {Evolution}?},
	booktitle = {{DH} 2023},
	author = {Vignoli, Michela and Gruber, Doris and Simon, Rainer},
}
```
