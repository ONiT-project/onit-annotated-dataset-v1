# ONiT: Annotated Dataset Version 1
This is the first version of our annotated image dataset extracted from the ONiT 16th century travelogues subcorpus during the first project year (Link: [Ottoman Nature in Travelogues project](https://onit.oeaw.ac.at/)). The curated images all contain representation of "nature" and are annotated with [ICONCLASS](https://iconclass.org/) notations of animals (25F), plants/vegetation (25G), landscapes (25H), and maps (25A).

A collection of direct links leading to the extracted images at the Austrian National Library IIIF repository are provided in the CSV/Excel files. This repository contains:

**1. Two variants of the multi-label annotated dataset:**
1. A detailed version that contains 592 annotated images. We do not recommend using this version for Machine Learning (ML) because the annotations do include material that is too fuzzy for training tasks.
2. A more robust training dataset with 407 images that contains 234 representations of animals (on 57% of the images), 177 plants/vegetation (on 43% of the images), 167 landscapes (on 40% of the images), and 22 maps (on 5% of the images). The annotations include only representations of the classes with distinct visual features, which makes them more suitable for ML training tasks.


**2. An extended version of the training dataset including bounding boxes for object detection tasks.**
In addition to the images from the 16th century travelogues, this dataset includes images from 17th century as well.

The CSV/Excel files contain the annotations and direct IIIF links to the extracted images on the repository of the [Austrian National Library (ÖNB)](https://search.onb.ac.at/).

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
