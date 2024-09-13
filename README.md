# ShaLPA
<strong>ShaLPA tool - Shallow Landslides Propagation Assessment at basin scale</strong>

Hazard maps for shallow landslides at the basin or regional scale often provide information solely about past events (inventory maps) and/or potential source areas (initiation susceptibility maps). Despite the availability of several propagation assessment software tools, runout maps that estimate the propagation areas of potential shallow landslides at basin scale are very rare. To fill this gap, the ShaLPA runout GIS tool was developed as an easy-to-use and efficient solution. This tool is based on a geometric approach, that relates one or more dimensional characteristics of a shallow landslide to the maximum runout of the mobilized material.

The ShaLPA GIS tool was tested for the first time in the Giampilieri and Briga area (Sicily, Italy), allowing the identification of strengths and weaknesses in the process and leading to improvements in the structure of the scripts. The application leverages the capability of the free QGIS software to automate the data processing required for the runout analysis. The scripts used by the runout GIS tool primarily manage a detailed DTM and basic geotechnical data, drawing the paths along which shallow landslides may move. The model estimates the maximum distance reached by the mobilised material (runout) and describes the distribution of velocity and kinetic energy along the path.

The reliability assessment was conducted by comparing observed and estimated runout values, providing encouraging results. The simplicity of using the ShaLPA tool promotes the integration of runout and failure susceptibility analyses, enhancing the completeness of hazard and risk assessment and improving the effectiveness of landslide mitigation measures.

All files are Graphical Models for QGIS version 3.32 and later

# ShaLPA DATA

The landslide inventory used in this study is available in "ShaLPA_DATA.zip", 3 shape files for calibration and 3 shape files for validation.<br />
The Soil Thickness Map has been divided into 2 raster files ("ShaLPA_SoilThicknessMap_West.tif" and "ShaLPA_SoilThicknessMap_East.tif") because the total size exceeds the 25MB limit of this repository. These two maps need to be combined into a single raster file, the "ShaLPA_SoilThicknessMap.tif"

The 2 m cell size DTM (ATA flight 2012-2013), used in the study as basis for the morphometric analysis, is provided by Sicilian Regional Authorities (https://www.sitr.regione.sicilia.it/geoportale/it/Metadata/Details/946).<br />
The high-resolution aerial images (tiff format) and the 1:50,000 geological map of the Messina province (shp format) are provided by the Regional Civil Protection Department of Sicily, as well as the geotechnical report of the General Master Plan of the Messina Municipality (Comune di Messina - Piano regolatore generale - Variante parziale di tutela ambientale. Elaborato: relazione geologica – Giugno 2015/Aggiornato Febbraio 2017), used to identify the unit weight of the formations present in the geological map.<br />  
The soil thickness map was produced using the GIST model approach described in Catani et al., 2010 (https://doi.org/10.1029/2008WR007450) and the specific process details are described in Falconi et al. 2023 (https://doi.org/10.1007/s11069-023-05945-8).
