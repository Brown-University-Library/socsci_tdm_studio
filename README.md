# Notebooks to run on ProQuest TDM Studio

## Overview

These notebooks (Python and R) are expanded versions of the sample resources available on the ProQuest TDM Workspace instance. They fill in some of the missing functionality, and give you options to accomplish your goals.

* `dataset_export_with_noise_fn.ipynb` (Written in Python): Use this notebook to export your dataset (collection of texts) as a .csv. 

Note that to comply with ProQuest licensing, you MUST use a noise function to alter the Full Text data - PQ does not permit exporting complete, unaltered full texts. Alternatively you can run your analysis within the Workspace environment. Details for each (and a possible noise function) are included in this notebook.


## How to import a Notebook from your computer into the Workspace environment

Download the notebook locally from this GitHub repo.

It can be tricky to copy and paste text/code into Workspace, so we'd suggest uploading the entire `.ipynb` file into the environment through Workspace's upload functionality.

You can upload this notebook directly into the Workbench environment by using the My Files features on the taskbar at top of screen (which will deposit a file into the virtual computer's file system under My Files/Temporary Files) and then, afterwards, uploading into the Jupyter Notebook environment via the Upload button and navigating to the My Files shortcut -> Temporary Files.
