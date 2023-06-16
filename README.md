# Coding3-Final-Project
## Video Link

## Outline
A deep learning model is used to classify plant images based on their edibility and health status. The method involves training convolutional neural networks (CNNs) on a dataset of leaves that range from healthy specimens to those with obvious signs of disease or decay.


## Process
The design and development process for the project involved several steps:

#### Project conceptualisation: 
The initial phase involved defining the project goal of creating a Convolutional Neural Network (CNN) based deep learning model capable of classifying plant images based on their edibility and health status.By monitoring the plant's disease status, the presence of diseases or pests can be promptly detected, allowing for timely measures such as spraying insecticides or applying appropriate medications to control the diseases and prevent further damage, thereby minimizing yield losses. It also enables the evaluation of agricultural practices and timely adjustment of agricultural management strategies. For instance, irrigation water levels, fertilization plans, and pesticide usage can be adjusted based on disease conditions to optimize plant growth and maximize yield.I think CNN is the excellent tools for image processing tasks because they can automatically learn and extract features from images, which are then used for classification tasks. This capability makes CNN particularly well-suited for this project.

#### Dataset selection:
After defining the project objectives and the machine learning approach, the task was to identify a suitable dataset. The final choice was the leaf dataset from Kaggle (URL: https://www.kaggle.com/code/aaalexlit/from-simple-cnn-to-transfer-learning-on-tpu), as it contains a variety of states of leaves, from healthy to unhealthy. 

#### Code base selection:
The basic code for training the DenseNet121 model, a specific type of CNN, was identified on GitHub. This code was the basis for the project.

#### Code customisation:
Several changes were made to the base code, such as the implementation of GIF creation to visualise the training progress of the model. The imageio library was used for this purpose, inspired by this tutorial. DenseNet121, the chosen CNN architecture, was utilized due to its efficiency in categorizing images by reducing the vanishing gradient problem, making it a good fit for our project.

#### Model training:
The DenseNet121 model was trained on the selected dataset. During this phase, callbacks such as EarlyStopping and ReduceLROnPlateau were used to optimize the training process. These techniques are common in training CNN, as they help prevent overfitting and ensure the model learns efficiently.

#### Model evaluation:
The performance of the model was evaluated using metrics such as accuracy, precision and recall. These are standard evaluation metrics for classification tasks in CNN. 

#### The successful realization of this project hinges on achieving two key objectives:
surpassing a classification accuracy of 90% with our model, and seamlessly generating GIFs to elucidate the model's training progression or to generate any other good visual outputs. These ambitious yet attainable targets are based on the established performance benchmarks of Convolutional Neural Networks (CNN) for analogous tasks.

#### third-party resources:
In the spirit of acknowledging the collaborative nature of coding and data science, this project credits all third-party resources that were employed. I leveraged the Tensorflow and Keras libraries extensively to architect and train our CNN models, while the 'imageio' library was utilized for GIF creation. For the training phase, images were sourced from two valuable datasets: the PlantVillage dataset and the Plant Pathology 2020 dataset.

Additionally, meticulous attention has been paid to the readability and comprehensibility of the code, ensuring it is sufficiently commented. This not only facilitates better understanding for those seeking to learn from or build upon this work but also aligns with best practices for coding and documentation.

Many thanks to the teachers for the comments! It really taught me a lot! Below are links to relevant materials I looked up in the course of completing this project （In addition to the weekly tutorials in github that appear in the course）:
[1].https://git.arts.ac.uk/rfiebrink/ExploringMachineIntelligence_Spring2023/blob/main/week2/ImageClassifier.ipynb

[2].https://www.kaggle.com/code/aaalexlit/from-simple-cnn-to-transfer-learning-on-tpu

[3].https://www.kaggle.com/code/kaledhoshme/classification-foliar-diseases-in-apple-trees/notebook

[4].https://www.kaggle.com/code/rajesh2609/apple-foliar-diseases-extensive-analysis

[5].https://github.com/tensorflow/docs-l10n/blob/master/site/zh-cn/tutorials/load_data/images.ipynb

[6].https://www.tensorflow.org/tutorials/load_data/images?hl=zh-cn

[7].https://github.com/spMohanty/PlantVillage-Dataset/blob/master/README.md

[8].https://www.kaggle.com/code/aaalexlit/from-simple-cnn-to-transfer-learning-on-tpu

[9].https://keras.io/api/data_loading/image/

[10].https://keras.io/guides/sequential_model/

[11].https://imageio.readthedocs.io/en/stable/
