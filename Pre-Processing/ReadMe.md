Histogram equalization   
Follow “Histogram_Equalilzation.ipynb” code to produce histogram equalization image 

Lung segmentation using U-net

Find a trained U-net using “Montgomery + Shenzhen” data set:
https://www.kaggle.com/eduardomineo/u-net-lung-segmentation-montgomery-shenzhen

The trained model is saved in unet_lung_set.hdf5 in that kaggle file

Wrote a jupyter notebook file  (lung-segmentation-v1.ipynb ) to test the U-net on “ COVID-19 Radiography database (CXR)” 

( lung-segmentation-v1.ipynb is changed from the code in kaggle, be aware of the path of test images when running the jupyter notebook. )
Alternatively, use “lung-segmentation-v2.ipynb” to show Unet training and produce the images in Figure 2 of the paper
