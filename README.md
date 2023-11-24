# ltu_lakes_ds
**[NOT A FINAL VERSION, DATASET IMPROVEMENTS ARE YET IN PROGRESS]** <br/><br/>
Repository contains the dataset for segmentation task of 357 multispectral satelite images of Lithuanian lakes.
Also included a .ipynb notebook used to download the data itself (to be refactored).
<br/>
<img width="618" alt="Screenshot 2023-11-24 at 15 42 26" src="https://github.com/somkamarius/ltu_lakes_ds/assets/62346438/b2d66521-1d6d-4f45-ae58-b42ee6a2b94f">
<br/>_Samples of RGB and mask image pairs from the dataset_<br/>
<br/>
**Dataset contains three main categories of data:**
- RGB images.
- Multispectral images, with 6 channels, according to "Sentinel-2" data specifications:
  - B2 (red)
  - B3 (green)
  - B4 (blue)
  - B8 (VNIR)
  - B11 (SWIR1)
  - B12 (SWIR2)
- Mask images for water segmentation.

[Download link for the dataset](http://www.google.com/ "Named link title") (will be moved to proper source out of Google drive).<br/>
[Research paper for which this dataset was created](http://www.google.com/ "Named link title")

<br/>

**Planned improvements:**
- Include lake images of other Baltic states
- Rewrite the image extraction script properly from notebook to simple Python to run locally
- Some images come out blank, either filter these out, or investigate the issue further
