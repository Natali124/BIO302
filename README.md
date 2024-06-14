You will find labeled false positives in the folder ```annotated_csvs```. Labels are one of these: "background", "glia", "black cell", "vein". In case I was not sure about the classification, I added "_unsure" in the end.

```read_debug_proofread.ipynb``` imports data of this format. It also contains code for getting selected points from the points layer and creating a new feature from it. This is already integrated into the pull request for napari-brainbow-diagnose.
