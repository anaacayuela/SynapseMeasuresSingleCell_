# SynapseMeasuresSingleCell_

This ImageJ/Fiji plugin was developed to quantify the accumuation of a protein (i.e. actin or clathrin) at the Immunological Synapse single cell. The sofware allows to obtain a ratio of the fluorescence intensity observed at the cell-to-cell contact area respect other zones of one single cell. Moreover, this sofware takes into account the fluorescence in the contac of cell A, the fluorescence in other zones of cell A and the fuorescence apported by the background. To achive a correct installation and launching, you should download the one single JAR file [SynapseMeasuresSingleCell_.jar](https://github.com/anaacayuela/SynapseMeasuresSingleCell_/releases/download/1.0/SynapseMeasuresSingleCell_.jar) and place it into the "plugins" folder of ImageJ/Fiji. Note that for a better understanding of this plugin, you shall do the following steps:

## •STEP 1. 
It is better to try to analyze the maximal projection of the image channel you select using ImageJ/Fiji -> ZProject... tool (ImageJ/Fiji -> Stacks -> ZProject... -> Max Intensity) althought this step is not essential, you can start analyzing whichever image type or bit depth you desire.

  ![step1](https://user-images.githubusercontent.com/54528366/65417800-3bb8b000-ddfb-11e9-89c1-de02f28085cb.jpg)

## •STEP 2. 
Select Synapse Measures Single Cell plugin (ImageJ/Fiji ->Plugings -> Synapse Measures Single Cell) and then click “Initialize” button.

![step2](https://user-images.githubusercontent.com/54528366/65418141-17110800-ddfc-11e9-92f6-5bc10ace5498.png)

![step2 1](https://user-images.githubusercontent.com/54528366/65418456-c4841b80-ddfc-11e9-97f8-c82d1be79f85.png)

## •STEP 3. 
At this point, you should select the counter type. It is recommended to start with “Type Bg” counter to mark the background by clicking with the mouse several times over the image background (outside cell structure).

![step3](https://user-images.githubusercontent.com/54528366/65418286-66573880-ddfc-11e9-900c-e0932b58a0e9.png)

![step3 1](https://user-images.githubusercontent.com/54528366/65418495-da91dc00-ddfc-11e9-9bb7-81343b260005.jpg)

## •STEP 4. 
Click on “Type Tsyn” counter to mark the area in cell to cell contact site.

![step4](https://user-images.githubusercontent.com/54528366/65418707-52600680-ddfd-11e9-8026-188c3953fcff.png)

![step4 1](https://user-images.githubusercontent.com/54528366/65418782-7a4f6a00-ddfd-11e9-9ab9-c39453bf68e0.jpg)

## •STEP 5.
Click on “Type Tnosyn” counter to mark the area in cell A (not in the cell to cell contact site).

![step5](https://user-images.githubusercontent.com/54528366/65418875-b387da00-ddfd-11e9-8512-913938218a52.png)

![step5 1](https://user-images.githubusercontent.com/54528366/65418924-d5815c80-ddfd-11e9-807d-67023db221d7.jpg)


## •STEP 6. 
Click “Measure Cell” button. At this point, you will obtain the ratio of the fluorescence signal at the cell to cell contact site respect to the signal at other part in the cell A.

![step6](https://user-images.githubusercontent.com/54528366/65419418-e383ad00-ddfe-11e9-840f-72a93eeed1b8.png)

![droppedImage_11](https://user-images.githubusercontent.com/54528366/65419461-fdbd8b00-ddfe-11e9-8dcc-ba4e4e66d7fa.jpg)

•STEP 7. Repeat these previous steps as many measurements as you need. (The data will be saved by the program). Once finish, press on “Final Measure” button. The data corresponding to the “Ratio” from all measurements will appear in a new window called "Results" and they can be exported for further analysis.

Note: the size/area of the circles can be adjusted by using the “Larger” (bigger size) or “Smaller” (smaller size) buttoms. If you want to delete the last circle made, you should press on “Delete” button. Moreover, if you need to delete every circle made, you shall press on "Reset" button.
