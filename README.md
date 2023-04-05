# SCD_MRA_ML
Scripts associated with manuscript "Machine learning investigation of severity and progression in pediatric sickle cell disease clinical neuroimaging data"

All scripts written by Meredith Fay, PhD candidate, in preparation for thesis defense and brief report publication

The workflow as written for initial manuscript submission is comprised of seven scripts/notebooks:

Workflow:
(1) Read and organize large amounts of MRI metadata - metadata.py
(2) Combine data frames into one large, indexable excel file dataframe - script combine_dataframes.py
(3) Select desired images - script select_imgs.py
(4) Skeletonize images into a single pixel width representation of all vessels - script skeletonize.py
(5) Calculate intepretable metrics (width) for each vessel - script img_tiles_width.py
(6) Calculate descriptive statistics for produced metrics - Jupyter notebook descriptive_stats.ipynb
(7) Perform machine learning analysis of data - Jupyter notebook SCD_MRA_ML.ipynb
