# HydroSat FusionHub Google Earth Engine (GEE) Asset Tools

Example code/tools for ingesting HydroSat FusionHub images into GEE.

The "reservoir_gee_asset_ingest.ipynb" notebook file has the processing workflow that was used to load the Hydrosat FusionHub images for a subset of reservoirs and lakes in the western United States.

To use this notebook, a "creds.json" file will need to be generated with a users FusionHub "username" and "password" values and saved in the same folder as the notebook file.

Many of the parameters in this notebook are hardcoded at the beginning of the notebook and will need to be adjusted for other users or projects.  These include the image workspace folder, project ID, and bucket name.
