# **Confluency Tool v0.82**
**Current features:**
  - Batch analysis of image sets in directory
  - Progress indicator
  - Plotting of confluency vs time for the selected image set
  - 11/8/22 - Added "Enable detailed outputs" feature to improve data analysis and troubleshooting
  - 11/8/22 - Added y-error bars to plots
  - 11/9/22 - Improved image set  selection and added ability to merge analyses between sets

**Planned additions/improvements (ordered by priority):**
  - Write all data to and read from google sheets
  - Ability to run all image sets in directory
    - And only run sets that are not already in a designated data sheet unless specified
  - Automatically calculate doubling time
  - ~~Some way to inspect which, if any, images are giving inaccurate confluency measurements~~
  - An "Abort" button that doesn't require restarting the runtime
  - Ability to upload and analyze single images
  - Ability to upload and analyze folders of images from local device
  - Ability to select which directory to use
  - Time estimates for how long the analysis will take
  - ~~A "verbose" option to show all images before and after processing~~
  - ~~A nifty little progress bar~~

**Future versions:**
  - Modularity for image pre-processing and post-processing steps
  - General optimizations
  - Training or selecting the machine-learning model from within the tool

**Known issues:**
  - The trained ML model is highly inaccurate with certain image sets (specifically with some of the "Growth Curve" images)
  - Dead cells are not accounted for

All in all, about *82% done* with this code.
