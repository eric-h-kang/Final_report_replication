# DSC180A-Methodology-02

The report replication is largely based off the GradCAM code provided in https://github.com/jacobgil/pytorch-grad-cam. This repo has been imported as submodule in `GradCAM`. 

A few significant edits were made in order to process the data with the COCO dataset. The original code was only able to run inference on a single image at a time, while our code is able to process any number of images. 

In order to run inference on images, move the images into `src/data/input_images`, and the model will run on all the models and generate overlaid heatmaps for each one. These overlaid images will be placed in `src/data/output_images`, named accordingly with each input image


## Running the code 

In order to run the code, please run the following line of code in the root directory of the repo: `python3 run.py --image-path src/data/input_images` and it will generate the GradCAM visualizations for every image. Please allow time for the model to run. 





#### Contributions 

Eric Kang wrote the edits to the code and Minjoo Kim solved a significant bug dealing with file pathing. Both members contributed equally to the edits (as there were not many) as we shared screen on Zoom and gave the other person remote control access to the machine so that we could both have mouse/keyboard control of one machine. 

Report contributions are dictated in the report for the replication.