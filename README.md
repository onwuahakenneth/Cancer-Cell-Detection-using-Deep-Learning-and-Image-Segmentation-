<div class="alert alert-info" style="color:#004643"><h4><b><center>Cancer Image Segmentation using deep learning and transfer learning</b></h4></div> <a id="eda"></a>
<div>

<p>Authors:</p>
<p>&emsp;&emsp;Douglas Connolly (23053027)</p>
<p>&emsp;&emsp;Kenneth Onwuaha (23073022)</p>
<p>&emsp;&emsp;James Groth (23073283)</p>

#### Abstract

We present a cancer classification system based on transfer learning and CNN image segmentation with the aim of accurately distinguishing between normal and circulating cancer cells (CTCs) within greyscale microscopy images. Many studies have used cellular morphology to identify CTCs within blood samples. However, most validation experiments include only homogeneous cell lines and inadequately captured the broad morphological heterogeneity of cancer cells. We have chosen to use organoid-derived microscopic images from 3 cholangiocarcinoma patients showing normal and cancerous cells. To improve cell detection, a VGG16 model was pre-trained with ImageNet and fine-tuned with single cell images; this formed the down sampling layers of the image segmentation model. The approach achieved a mean intersection over union (IOU) score of 21.8%.  More work is needed to improve the generalisation score, but automated detection and counting of CTCs provides an alternative to testing laboratories.

#### Datasets

The datasets and model's pre-trained weights can be accessed via the links below

[Datasets](https://drive.google.com/drive/folders/1q3ML1yvChhivSs9SgpYjBbPTeOgUI5Xa?usp=drive_link)

[Model Weights](https://drive.google.com/drive/folders/1qazu05_4jbazH3HkKN2ys0dit-lEb8cT?usp=drive_link)