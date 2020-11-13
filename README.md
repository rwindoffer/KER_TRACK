# KER_TRACK
We provide the workflow for tracking granules of mutated keratin proteins in living cells that has been used in Lehmann et al. (unpubl.).
The workflow includes an example dataset, a description how to track the granules with the ImageJ plugin Trackmate and provides two matlab scripts for the final analysis.

After unzipping you get these directories and files including the documentation:
### 00_Trackmate\				
*	image_stack.tif			Example Image file
*  image_stack.xml			saved Trackmate file
*  Links in tracks statistics.csv		trackmate result
*  Spots in tracks statistics.csv	trackmate result
*  Track statistics.csv			trackmate result
### 01_programs\
*	Prog_01_Tracks_in2_Subtracks\	matlab script 01
*  Prog_02_calc_parameters\		matlab script 02
### 02_RESULT_all_subtracks\
*	track_0000_subtrack_001.csv	matlab result file
*  track_0000_subtrack_002.csv	matlab result file
*  etc.
### 03_RESULT_all_subtracks_parameters\
*	track_0000_subtrack_001_all.csv	matlab result file
*  track_0000_subtrack_002_all.csv	matlab result file
*  etc.
### 04_documentation\
*	Ker_TRACK documentation.pdf
