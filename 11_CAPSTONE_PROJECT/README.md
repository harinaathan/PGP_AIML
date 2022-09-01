<h4 class="project-title">Deep Learning Based Car Identification</h4>
<p>
Computer vision based Object detection models specialise in identifying object(s) of interest in the field-of-view for real time applications. 
An object detection model should be able to localise and classify the detected objects.
Such models are frequently created by combining approaches from traditional machine learning algorithms and artificial neural networks.
Popular techniques include CNN &amp; R-CNN architectures,  which have a track record of success in SOTA models.<br>
This study presents a CNN that learns both object localisation and classification simultaneously.
</p>
<h4> The Project Flows as follows<br></h4>
<p>
1) Milestone1(.ipynb,.html) and extract.py (2 files)<br>
- dataset: https://www.kaggle.com/jutrera/stanford-car-dataset-by-classes-folder <br>
- complete EDA and data abstraction<br>
- base file for consecutive pipelines<br>
2) MobbileNetClassifier(.ipynb,.html) (2 files)<br>
- CNN based classifier model attempted<br>
3) RCNN_object_detection(.ipynb,.html) (2 files)<br>
- attempt at R-CNN network<br>
4) generatorGPU(.ipynb,.html) and generator.py (3 files)<br>
- custom Image Datagenerator for feeding images to the network, along with adjusted bounding box coordinates<br>
- unit tests for generator functionality<br>
5) customCallbacks(.py,.ipynb,.html) (3 files)<br>
- custom callback classes for tensorflow network training<br>
6) networkPipe(.py,.ipynb,.html) (3 files)<br>
- tailor-made ETL pipeline for model training, evaluation & report making<br>
7) unLearntModels(.ipynb,.html) (2 files)<br>
- modelling based on median, mode and random values<br>
- a base line study<br>
8) transfer******(.ipynb,.html) (12 files)<br>
- a battery of baseline models<br>
- implementation of Region Localisation combined with Classification in unified CNN<br>
- improvisation over RCNN<br>
9) CNN+R_Final(.ipynb,.html) (2 files)<br>
- hypertuning of chosen model from above battery<br>
- deployable model pickled<br>
10) main.py, helper.py (2 files)<br>
- streamlit GUI codes<br>
- frontend & backend<br>
- deployed at https://carmodelclassifier.herokuapp.com/<br></p>
<p class="project-highlight"><strong>Skills and Tools</strong></p>
<p>CNN, Computer Vision, Tensor Flow, Object Detection, Transfer learning</p>
