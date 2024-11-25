## **Semi - Supervised Learning for Semantic Segmentation using Limited Point Annotation**
In this Repo I overcome the challenge of limited point annotation by:

* Using `pandas` and `OpenCV` to prepare the satellite images and masks from the `DeepGlobe` dataset, ensuring they are appropriately formatted for the model.

* Setting up the `DeepLabV3Plus` model with `ResNet-50` as the backbone, leveraging `transfer learning` by initializing with `pre-trained ImageNet weights` using the `segmentation_models_pytorch library`.

* Using NumPy to simulate `random point labels` on segmentation masks to handle partially labeled data effectively.

* Varying `sampling ratio` and `image resolution` to study their effects on the model's `Intersection over Union (IoU)` performance.

<p align="center" width="75%">
    <img width="75%" src="https://github.com/Cheeetah97/SemanticSegmentation-PointLabelling-DeepLabV3-PCrossEntropy-/assets/62606459/0428387b-a57a-40a0-acd6-a142e5ff77e7"> 
</p>

<p align="center" width="75%">
    <img width="75%" src="https://github.com/Cheeetah97/SemanticSegmentation-PointLabelling-DeepLabV3-PCrossEntropy-/assets/62606459/6623dd23-2fea-4cd5-bc99-5ab665e29e29"> 
</p>

<p align="center" width="75%">
    <img width="75%" src="https://github.com/Cheeetah97/SemanticSegmentation-PointLabelling-DeepLabV3-PCrossEntropy-/assets/62606459/9cd162b0-cdcf-4ecd-b9a1-226f879312bc"> 
</p>

<p align="center" width="75%">
    <img width="75%" src="https://github.com/Cheeetah97/SemanticSegmentation-PointLabelling-DeepLabV3-PCrossEntropy-/assets/62606459/901548e0-a86b-427a-96e3-d53b56f3e76c"> 
</p>


