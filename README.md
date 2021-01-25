** ``` Authors: Sumit Pandey and Prof. Kuan-Fu Chen```**


In This research project, we completed these steps:
- Collected total ```785 Ultra-Sound images``` from multiple subjects. 
-  ```Labeled and prepare segmentation``` the images under expert supervision.
- ```Pre-process``` (Normalize and resize) the images. 
-  train and validate the model over multiple machine-learning and deep-learning based algorithm including .



## Libraries:
``` python 
import numpy 
import tensorflow 
import keras
import matplotlib.pyplot as plt
import glob 
import keras 

```
## Results: 
We compared all 5 models:

Figure 1: This figure shows the graph between  SSIM (Structure Similerity Index Measure) and image number (test image id). 

<img align="center" src="newplot (1).png" width="500" />

Figure  2: This figure shows the graph between IOU (Intersection over Union) and image number (test image id).

<img align="center" src="newplot (2).png" width="500" />

Figure  3: This figure shows the graph between PSNR (Peak signal-to-noise ratio) and image number (test image id).

<img align="center" src="newplot (4).png" width="500" />
