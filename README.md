# SynapseMeasuresSingleCell_

This ImageJ/Fiji plugin was developed to quantify the accumuation of a protein (i.e. actin or clathrin) at the Immunological Synapse single cell. The sofware allows to obtain a ratio of the fluorescence intensity observed at the cell-to-cell contact area respect other zones of one single cell. Moreover, this sofware takes into account the fluorescence in the contac of cell A, the fluorescence in other zones of cell A and the fuorescence apported by the background. To achive a correct installation and launching, you should download the one single JAR file SynapseMeasuresSingleCell_.jar and place it into the "plugins" folder of ImageJ/Fiji. Note that for a better understanding of this plugin, you shall do the following steps:

•STEP 1. It is better to try to analyze the maximal projection of the image channel you select using ImageJ/Fiji -> ZProject... tool (ImageJ/Fiji -> Stacks -> ZProject... -> Max Intensity) althought this step is not essential, you can start analyzing whichever image type or bit depth you desire.

•STEP 2. Select Synapse Measures Single Cell plugin (ImageJ/Fiji ->Plugings -> Synapse Measures Single Cell) and then click “Initialize” button.

•STEP 3. At this point, you should select the counter type. It is recommended to start with “Type Bg” counter to mark the background by clicking with the mouse several times over the image background (outside cell structure).

•STEP 4. Click on “Type Tsyn” counter to mark the area in cell to cell contact site.

•STEP 5. Click on “Type Tnosyn” counter to mark the area in cell A (not in the cell to cell contact site).

•STEP 6. Click “Measure Cell” button. At this point, you will obtain the ratio of the fluorescence signal at the cell to cell contact site respect to the signal at other part in the cell A.

•STEP 7. Repeat these previous steps as many measurements as you need. (The data will be saved by the program). Once finish, press on “Final Measure” button. The data corresponding to the “Ratio” from all measurements will appear in a new window called "Results" and they can be exported for further analysis.

Note: the size/area of the circles can be adjusted by using the “Larger” (bigger size) or “Smaller” (smaller size) buttoms. If you want to delete the last circle made, you should press on “Delete” button. Moreover, if you need to delete every circle made, you shall press on "Reset" button.
