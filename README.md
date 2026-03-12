# Warren Mammoth Site (48LA3800)
This repository includes the shapefiles and photogrammetric model of the Warren Mammoth Bone bed

# Overview
wms_bonebed.zip, contains the shapefile of all excavated skeletal elements.
We have created unique attribute codes for specific characteristics of skeletal elements. 

Once inside a GIS software, the shapefile attributes are as follows:
1. Column "FS_Num" corresponds with the Catalog No. from Table 2 of DePlata-Peterson et al. 2026
2. Column "Element_La" is a unique element code that corresponds with the element type (ie. "PLV" corresponds with "Pelvis"). These codes are always specified in the "Notes" column.
3. Column "Side" corresponds with either left or right anatomical position _or_ if the element is axial or unspecified ("US")
4. Column "Region_Lab" refers to a code for the region of the body each element belongs.
  CRNL = Cranial Region,
  CRVL = Cervical Region,
  FORL = Foreleg Region,
  THRC = Thoracic Region,
  LMBR = Lumbar Region,
  HNDL = Hindleg Region,
  CADL = Caudal Region,

wms_excavation.las, is a photogrammetric model of the bonebed and excavation block from both 2022 and 2023 seasons. 

# Citation
When using the datasets from this repository please cite the following:

DePlate-Peterson, M., T.A. Surovell, S.R. Pelton, D.R. Garner, and S.A. Allaun. 2026. The Warren Mammoth site (48LA3800): A Non-Cultural Terminal Pleistocene Mammoth from Southeastern Wyoming. Journal of Quaternary Science, In Prep.

# Software Requirements
GIS Software and
Point Cloud viewers
