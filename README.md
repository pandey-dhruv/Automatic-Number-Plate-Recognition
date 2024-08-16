# Overview - 
This is a License Plate Detection Model that uses YoloV8 from TensorFLow Model Garden and EasyOCR for optical character recognition.
Basically the workflow is that the object detection model extracts the poriton of the image containing the license plate and then we use EasyOCR for extracting the actual
license plate number from the extracted image segment.

# Running the code - 
Carefully follow the instructions mentioned in the Jupyter notebook cells. I have mentioned the necessary changes as comments in the cells wherever the associated commands are present.
These changes are necessary because the models in Model Garden are usually under research and do not seamlessly work with the latest TensorFlow version. One example was that the model code
contans code to create manual sessions. However, the same was deprecated in Tensorflow 2.x. This would require us to use TensorFLow to use in compatability mode for TensorFlow 1.x

# Dependencies - 
All the dependencies and the code to install them has been given in the Jupyter notebook itself. Just run the cells serially and eveything should work fine.

# Feel free to play around :)
