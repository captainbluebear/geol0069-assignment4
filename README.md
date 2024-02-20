# Unsupervised Learning with Altimetry Classification on SEN-3 Data

## About The Project

This project was created to demonstrate the following objectives: 
1. Classification of sea ice and leads using Gaussian Mixture Models (GMM) with altimetry data from Sentinel-3.
2. Graphs of the classified echoes for visual analysis.
3. A confusion matrix comparing our GMM-classified results with the official ESA classification.

The SAR dataset that the GMM algorithm is trained on is included.

For more detailed explanations on each of these steps, as well as the code, refer to the contents of `Unsupervised_Learning_Methods_Assignment4.ipynb`.
## Getting Started
The notebook runs linearly, with steps depending on their predecessors. One modification will be required from the user's end once this project is downloaded; they must specify the file path to where they have downloaded this project. 

**For this notebook to work properly, do not modify the structure of this project!**

Step by step explanations behind each step can be found within the notebook.
## Usage
For clarity, the images required for the assignment are shown here. They can be retrieved by running through the notebook.
### Images from GMM Classification
![image](https://github.com/captainbluebear/geol0069-assignment4/assets/59548582/4b03fe8b-06cb-4618-9c57-1863dd4d94e4) | ![image](https://github.com/captainbluebear/geol0069-assignment4/assets/59548582/ffaa1b05-407c-42f3-bf8b-92a2c35bdaab)
:-------------------------:|:-------------------------:
_Graph of Average Echo Shape for Lead and Ice from GMM Classification_ | _Graph of Echo Standard Deviation for Lead and Ice from GMM Classification_
### Quantification of Results
The notebook contains a confusion matrix that examines the GMM classification against the official ESA classification to verify accuracy. For reference, 0 represents sea ice and 1 represents leads in the matrix. As an example of how the matrix works, we can see that both the ESA and GMM classifications agreed 4241 times that an echo was sea ice.
![image](https://github.com/captainbluebear/geol0069-assignment4/assets/59548582/2375b7f6-577e-4794-b7ea-a18ad05b1b9a)
:-------------------------:
_Confusion Matrix Quantifying GMM Classification Against ESA Official Classification_

## Credits
UCL 2024
GEOL0069
Dr. Michel Tsamados
