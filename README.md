# reproducible_geobia


Scripts and models that were developed for the example change detection workflow described in the article “Reproducibility and Practical Adoption of GEOBIA with Open-Source Software in Docker Containers.” Remote Sensing 9(3), [10.3390/rs9030290](https://www.mdpi.com/2072-4292/9/3/290) :


Script computing local references and differences of object values to those references (Python script):
diff_to_local_ref_v1.3.py

Script performing clustering (regarding one feature only) on  selected vector layer (Python script):
kmeans_clustering_v2.3.py

Model performing exemplary analysis for conflict damage detection (QGIS model):
example_analysis_v3.2.model

Model performing settlement detection on edge layer (QGIS model, used by example analysis model):
detect_settlements_on_edgelayer.model

Please note that the QGIS models require certain plugins (e.g., OTB, SAGA) to be installed and there might be compatibility problems with some versions. For a fully reproducible collection, please refer to our package on zenodo.
