# Blood-Cell-Detection
Solve a Blood Cell Detection problem. Our task is to detect all the Red Blood Cells (RBCs), White Blood Cells (WBCs), and Platelets in each image taken via microscopic image readings. 

I have summarized below the steps followed by a Faster R-CNN algorithm to detect objects in an image:

step-1:Take an input image and pass it to the ConvNet which returns feature maps for the image
step-2:Apply Region Proposal Network (RPN) on these feature maps and get object proposals
step-3:Apply ROI pooling layer to bring down all the proposals to the same size
step-4:Finally, pass these proposals to a fully connected layer in order to classify any predict the bounding boxes for the image
