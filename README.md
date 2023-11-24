# ltu_lakes_ds
**[NOT A FINAL VERSION, DATASET IMPROVEMENTS ARE YET IN PROGRESS]** <br/><br/>
Repository contains the dataset for segmentation task of 357 multispectral satelite images of Lithuanian lakes.
Also included a .ipynb notebook used to download the data itself (to be refactored).
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

[AWS S3 download link for the dataset](https://ltu-lakes-ds.s3.eu-north-1.amazonaws.com/LTU_LAKES_DS.zip?response-content-disposition=inline&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAcaCmV1LW5vcnRoLTEiSDBGAiEA0INLWy%2BED1iLJg8sg2RFsswdryAFDejke%2Fhz1WzqzLACIQDhNw%2FC%2BmsFUCKhX5MlbwZlgLEll%2F6dwfLJDlkUfijFUirkAghgEAIaDDE2MDQ5MTY4NTY2NSIMLXjtLHfuxI9%2B8T86KsECZdLa9pigfEa4YSpNG6JWK%2FkFrjeXSnSTd3HvkkEyTsLC6o6DTkemDc%2F0eIf4BC9AnJqvwZUBaakEJBIsc0HWOYjV87m4qi8r556edwzL%2BSp8xXuMSiNznjEzXAwbaafYpaxq5mMFK7a6RDY2%2BuGNbi%2BYArsxuwKxTvzcF%2FoIrUXaBOjbuJ3GvOAhRZrWkbZjPkQOXEd%2BlTUQKP%2ByaHRmEY5FcYlLSrjFPFoMpgAUaE5dIEAdjFSBpiMwHF3xZ6nH41TFT7QrdIr0YCRzTUgJQve9fhS2BF7R9NeU7A%2FdrMR3t052%2FnA9pYpVhTnGdYowB4g9ULcx%2BMq8GdEnpDcXCoTB2v7eLfk6D1xz2cVIwoU%2BHpxL3VaCQReo7FSrK26X7Elry93NnzXqwaJxHJ5wJ9D%2F7obp7CZXm6e%2FmY0LrYcBMJL%2BgqsGOrICdJHu7mHMirkyRiVPF449OBBWV73WEZtolcJIBhSEnoCMoem86exsw9Bj2FqnJcOtfamfKVlkwzAydl8L87E68%2FzymE2BuP54KJ89bm4RkgL%2Fpk6HTThEu5QmwUrQDql9Jgg0X8TmNWgt%2B9Tbydk8N2BozeGt0s5w6XnFyQgLKM5NnIcXfoOxkoRO8Etf%2Fk1VweEvUmKx18bg6%2FPe4Baxi6zHRdi6Vk0xRi6BUG6MshNsWadg3QjXTr9zRcHDP7J%2Bcfe%2FzQJ69FQN8jZp34RtX39PMCru%2BFZ7WWH2UjWa4%2B1LJmPMqrHD%2FuojT5VFHAxhsu4kvo%2FsPgiZCiyMKPII9hFiwODnaU9spI8uz%2BzkdCiK2LM91P5fIGMwSyUXYlPBNn6G8A3imbJJJjScxYXvjOoP&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20231124T153716Z&X-Amz-SignedHeaders=host&X-Amz-Expires=43200&X-Amz-Credential=ASIASKXQMY4QSOAHUFG6%2F20231124%2Feu-north-1%2Fs3%2Faws4_request&X-Amz-Signature=000e46205b2e6d02a75e3517a9a6f9d975425afaa4e096f9118d78a598b0c5af "AWS link")<br/>
[Dropbox download link for the dataset](https://www.dropbox.com/scl/fi/bg9hxsx96q4tq50lqi0zb/LTU_LAKES_DS.zip?rlkey=5m8bry299fesf0tev879hddxp&dl=0 "Dropbox link")<br/>
[Research paper for which this dataset was created - not yet public, will update soon](http://www.google.com/ "todo")

<br/>

**Planned improvements:**
- Include lake images of other Baltic states
- Rewrite the image extraction script properly from notebook to simple Python to run locally
- Some images come out blank, either filter these out, or investigate the issue further
