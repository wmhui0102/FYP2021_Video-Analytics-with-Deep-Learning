# FYP2021_Video-Analytics-with-Deep-Learning

# Required Environment
Python3.6  
TensorFLow 1.13.1 (or gpu, with CUDA 10.0, cuDNN 7.4)  
Keras 2.1.0  
pycocotools  
jupyter notebook  
Other requirements in requirements.txt  

# Run the code
1. Create a virtual environment with Tensorflow 1.13.1, CUDA 10.0 and cuDNN 7.4.  
  
2. Clone the Mask R-CNN repository    
https://github.com/matterport/Mask_RCNN.git  

3. Delete the requirements.txt from the Mask R-CNN repo and use the one in this repo to install other requirements.  
pip install -r requirements.txt  
  
4. Run setup.py from Mask R-CNN  
python setup.py install  

5. Download the pre-trained Mask R-CNN 2.0 ()mark_rcnn_coco.h5) weight from the following link  
https://github.com/matterport/Mask_RCNN/releases  

6. Use jupyter notebook to open the code file  

7. Modify the directory inside the code, and it should be able to run  
