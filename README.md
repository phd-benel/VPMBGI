# VPMBGI :Vietnamese Public Merged dataset of Broken Glass Insulator for UAV inspection of power lines

Hy, Peace be upon you,

You will find in this repo a dataset [ images + annotations (Yolov7 format)] which I hope will be useful for your work (view samples from the dataset on figure 1). Especially, if you are interested in detecting anomalies (here broken glass insulators) present on electrical towers by computer vision methods.




We build a database of broken glass insulators from a set of Vietnamese public images [1][2][3][4][5]. Images were collected during inspections of high voltage power lines by ground patrol agents , helicopters and drones. Once the images are collected, we clean the images that are not of interest and label the defects on the glass insulators with rectangular bounding boxes on all the images. Accuracy and consistency are checked to ensure that all broken glass insulator cases are labeled in the images and that the labels surround each anomaly. We ensure that the labeling correctly delineates the anomalies to maximize spatial information. We use the Roboflow platform for this work and export the results in Yolov7 annotation format. Finally, we build a relatively small (~544 images) but diverse dataset that best represents the real deployment environment. 

You can find the broken glass insulator dataset in the release part. https://github.com/phd-benel/BGI/releases/tag/dataset All the images are under the CC by 4.0 license. Please feel free to contact me if you need any further information.

Reference

[1] hieulc@cpc.vn, “Su110kV_Broken Dataset,” https://universe.roboflow.com/hieulc-cpc-vn/su110kv_broken, Mar. 2022.
[2] “Project Overview.” https://universe.roboflow.com/qbpcluoi110gd1/cdien_ttinh_ct_vo-nqghi (accessed Feb. 09, 2023).
[3] “Cách điện thủy tinh bị vỡ bát trung thế Object Detection Dataset by DAKNONGPC.” https://universe.roboflow.com/daknongpc/cach-dien-thuy-tinh-bi-vo-bat-trung-the (accessed Feb. 09, 2023).
[4] “3cdien_ttinh_ct_vo Object Detection Dataset by QBPCLuoi110GD3.” https://universe.roboflow.com/qbpcluoi110gd3/3cdien_ttinh_ct_vo (accessed Feb. 09, 2023).
[5] “SUTHUYVO-MATBAT Dataset > Overview.” https://universe.roboflow.com/daknongpc/suthuyvo-matbat (accessed Feb. 09, 2023).
