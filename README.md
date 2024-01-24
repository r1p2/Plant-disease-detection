# Plant-disease-detection

In recent years, the agricultural industry has faced escalating challenges in crop disease identification and classification, with global losses exceeding $220 billion annually. This study addresses the limitations of existing crop disease detection solutions emphasizing the necessity for resilient models that can adapt to various agricultural environments.

This research uses a dataset gathered from various reputable sources, including Harvard University, the University of Energy and Natural Resources, AI Challenger, PlantVillage, and the National Institute of Health datasets, which are divided into 30 classes, each containing 1500 images. The dataset represents 10 different crops such as Apple, Cashew, Cassava, Cocoa, Grapes, Groundnut, Maize, Potato, Tomato and Beans, each afflicted by two disease classes and one healthy class. The selection of disease classes is based on their difficulty for prediction and their significant impact on the farmers.

While CNNs in prior studies, often concentrated on a limited range of crop types and utilized transfer learning, frequently attained accuracies surpassing 90%, our investigation uncovers a notable distinction. Specifically, the accuracy of a traditional CNN model on the RGB image dataset is revealed to be 85.41%. To enhance the traditional CNN model's performance, this research explores additional mechanisms. The study assesses how different image types, namely RGB and grayscale, affect the model's training. The findings suggest that the model's performance remains stable across different types of images. Notably, the integration of CNN with self-attention and Convolution Block attention mechanisms demonstrates promising improvements, achieving accuracies of 87.33% and 92.66%, respectively.

Exploring alternative models, the Vision Transformer achieved an accuracy of 85.83%, comparable to the traditional CNN, while the Neural Architecture Search (NAS) model excelled with an accuracy of 98.50%. This study demonstrates the effectiveness of these algorithms across a diverse array of crops and diseases, showcasing their ability to perform in a generalized manner. These findings underscore the potential for diversified models to outperform the CNN baseline, opening avenues for further exploration and refinement in crop disease detection using deep learning. This research contributes to the ongoing efforts to address the critical issue of crop diseases and lays the foundation for future advancements in agricultural technology.


These datasets are available at below mentioned sites:
1. Harvard University dataset: https://dataverse.harvard.edu/dataverse/airlabug/
2. University of Energy and Natural Resources dataset: https://data.mendeley.com/datasets/bwh3zbpkpv/1
3. AI Challenger dataset: https://aistudio.baidu.com/datasetdetail/76075 
4. PlantVillage dataset: https://www.tensorflow.org/datasets/catalog/plant_village
5. Groundnut dataset - National Institute of Health dataset: https://data.mendeley.com/datasets/22p2vcbxfk/3


As the dataset is compiled from diverse sources, careful measures have been taken to address potential class imbalances. A total of 10 crops were selected, with two primary diseases challenging farmers in identification and an additional healthy class for each crop. This classification structure results in a total of 30 classes within the dataset. Each class was curated with a substantial collection of 1500 images under different light settings.  This deliberate effort toward balance is crucial in preventing biases in the deep learning model. A balanced dataset ensures that the model is exposed to an equitable representation of different classes, thereby enhancing its ability to make accurate predictions across all categories. Additionally, considering the disparate sizes of images collected from various sources, all the images have been standardized by resizing all dimensions to a uniform 196x196 pixel format. This not only streamlines computational efficiency but also ensures consistent model interpretation across varied image scales.

Below is the image containg the sample of the dataset and the classes considered
![image](https://github.com/r1p2/Plant-disease-detection/assets/20014921/74beb1d9-0ccb-4c17-ab6d-8a70bee79444)

![image](https://github.com/r1p2/Plant-disease-detection/assets/20014921/fac124f1-3050-44bd-ac4f-dd32963851de)

