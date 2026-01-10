# WoodDefect Detection Dataset
## Dataset Description
WoodDefect Detection for automated visual inspection in wood processing, a multi-class defect detection dataset with bounding-box labels for European beech wood boards.

### Origin and Acquisition
The images were collected by GoldenY through a high-resolution industrial camera under controlled diffuse LED illumination in a European sawmill.
The original footage is publicly shared on the Roboflow Universe platform under the "CC-BY 4.0" licence.
All data were taken from the planed surface of kiln-dried European beech (Fagus sylvatica) boards with thickness 26–50 mm. No magnification filters or digital zoom were applied, guaranteeing a native pixel resolution of ≈ 0.08 mm px⁻¹ on the wood surface.

### Volume and Dataset Splits
Total annotated images: 3785
Current partitioning (**stratified split**, preserve global defect-class distribution):
- Training set: 3105 images (80 %)
- Validation set: 680 images (20 %)

### Task & Annotation Format
Task: Multi-class defect detection with bounding-box labels
Annotation type: Bounding box labels (standard format for object detection models)

### Full Dataset Download (Important)
The complete dataset is large in volume and hosted on **Zenodo** with a permanent DOI for academic citation.
✅ Full Dataset Download Link: https://doi.org/10.5281/zenodo.18205890
✅ Permanent DOI: 10.5281/zenodo.18205890
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18205890.svg)](https://doi.org/10.5281/zenodo.18205890)

### License
This dataset is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** License.

## Citation
If you use this dataset in your research or publications, please cite this work as:

Golden Y. (2025). WoodDefect Detection Dataset for Automated Visual Inspection in wood Processing [Data set]. Zenodo. https://doi.org/10.5281/zenodo.18205890

### BibTeX Citation
```bibtex
@dataset{golden_y_2026_18205890,
  author       = {Golden Y.},
  title        = {WoodDefect Detection Dataset for Automated Visual Inspection in wood Processing},
  month        = jan,
  year         = 2026,
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.18205890},
  url          = {https://doi.org/10.5281/zenodo.18205890}
}
