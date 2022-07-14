# VIMS-IAARC
This contains my project I presented in the VIMS/IAARC datathon. 


The file json to mask helps you to create segmentation masks from a json file of coco format.


I have used yolo and created a model by training it from the dataset provided by the organizers with mean IOU of 85%. The model creates segments of PVC, Cementitious debris, Rebar, Bricks and Wires in the test image.
