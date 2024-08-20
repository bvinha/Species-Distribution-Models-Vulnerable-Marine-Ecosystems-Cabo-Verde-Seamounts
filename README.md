# Species-Distribution-Models-Vulnerable-Marine-Ecosystems-Cabo-Verde-Seamounts
Code used in the study of Vinha et al., 2024, Diversity and Distributions (https://doi.org/10.1111/ddi.13896) to create an ensemble Species Distribution Models of four cold-water corals, that are VME indicators, on five seamounts of Cabo Verde (Central Atlantic Ocean).

Two R Markdown files are available:

- "1_Ocean_Terrain_Data_Analysis.Rmd"  - with code used to:
    (i) calculate and prepare environmental data (terrain and oceanographical parameters) used for modelling.
  
- "2_ModelFit.Rmd" - with code used for:
    (i) variable selection and prepation
    (ii) model training based on Generalized Additive Methods (GAM) and Random Forest
    (iii) model testing through 10-fold cross validation
    (iv) to investigate the extent of spatial auto-correlation in model's residuals
    (v) create final model's predictions
    (vi) to interpret modelling results by calculating model extrapolation and plotting variable importance and response curves.

Please download the following datasets to reproduce the code:

- Presence-Absence data of cold-water corals on the seamount of Cabo Verde is published in PANGAEA:
Vinha, B.; Hansteen, T. H.; Huvenne, V. A. I.; Orejas, C. (2023): Presence-absence records for four cold-water coral taxa on the seamounts of Cape Verde (NW Africa). PANGAEA, https://doi.org/10.1594/PANGAEA.963704
  
- Bathymetry data and spatial mask of the seamounts of Cabo Verde is available in Dryad:
Vinha, B., Murillo, F. J., Schumacher, M., Hansteen, T., Schwarzkopf, F., Biastoch, A., Kenchington, E., Piraino, S., Orejas, C., Huvenne, V. (2024). Terrain variables used for ensemble distribution modelling of vulnerable marine ecosystems indicator taxa on data-limited seamounts of Cabo Verde (NW Africa) [Dataset]. Dryad. https://doi.org/10.5061/dryad.0vt4b8h5g

- Data from the Viking20x model can be downloaded from:
Schwarzkopf, F. (2024). Supplementary data to Vinha et al. (2024): Ensemble modelling to predict the distribution of Vulnerable Marine Ecosystems indicator taxa on data-limited seamounts of Cabo Verde (NW Africa) [dataset]. GEOMAR Helmholtz Centre for Ocean Research Kiel [distributor]. hdl:20.500.12085/20248b0a-49fd-4868-90bf-581c61f4b396

**Please cite code as:**
Vinha, Beatriz (2024). Code to reproduce ensemble species distribution models of CWCs in five seamounts of Cabo Verde. figshare. Software. https://doi.org/10.6084/m9.figshare.25475533.v1

**Reference of the study where code and data was used:**

- Vinha, B.,  Murillo, F. J.,  Schumacher, M.,  Hansteen, T. H.,  Schwarzkopf, F. U.,  Biastoch, A.,  Kenchington, E., Piraino, S.,  Orejas, C., &  Huvenne, V. A. I. (2024).  Ensemble modelling to predict the distribution of vulnerable marine ecosystems indicator taxa on data-limited seamounts of Cabo Verde (NW Africa). Diversity and Distributions,  00, e13896. https://doi.org/10.1111/ddi.13896
- 

**DISCLAIMER**
Some parts of the code presented here were adapated to the objectives of the study, following code and modelling frameworks presented in:

- Nephin, J., Gregr, E.J., St. Germain, C., Fields, C., and Finney, J.L. 2020. Development of a Species Distribution Modelling Framework and its Application to Twelve Species on Canada's Pacific Coast. DFO Can. Sci. Advis. Sec. Res. Doc. 2020/004. xii + 107 p. https://www.dfo-mpo.gc.ca/csas-sccs/Publications/ResDocs-DocRech/2020/2020_004-eng.html

- Workshop on the Use of Predictive Habitat Models in ICES Advice (31st January 2021), https://github.com/ices-eg/WKPHM


