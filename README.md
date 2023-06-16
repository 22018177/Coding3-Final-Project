# Coding3-Final-Project
## Video Link

## Outline
A deep learning model is used to classify plant images based on their edibility and health status. The method involves training convolutional neural networks (CNNs) on a dataset of leaves that range from healthy specimens to those with obvious signs of disease or decay.


## Process
The design and development process for the project involved several steps:

Project conceptualisation: The initial phase involved defining the project goal of creating a Convolutional Neural Network (CNN) based deep learning model capable of classifying plant images based on their edibility and health status. CNN are excellent tools for image processing tasks because they can automatically learn and extract features from images, which are then used for classification tasks. This capability makes CNN particularly well-suited for this project.

Dataset selection: After defining the project objectives and the machine learning approach, the task was to identify a suitable dataset. The final choice was the leaf dataset from Kaggle (URL: https://www.kaggle.com/code/aaalexlit/from-simple-cnn-to-transfer-learning-on-tpu), as it contains a variety of states of leaves, from healthy to unhealthy. However, it's important to note that the status of leaves doesn't seem to have a direct correlation with their edibility.

Code base selection: The basic code for training the DenseNet121 model, a specific type of CNN, was identified on GitHub. This code was the basis for the project.

Code customisation: Several changes were made to the base code, such as the implementation of GIF creation to visualise the training progress of the model. The imageio library was used for this purpose, inspired by this tutorial. DenseNet121, the chosen CNN architecture, was utilized due to its efficiency in categorizing images by reducing the vanishing gradient problem, making it a good fit for our project.

Model training: The DenseNet121 model was trained on the selected dataset. During this phase, callbacks such as EarlyStopping and ReduceLROnPlateau were used to optimize the training process. These techniques are common in training CNN, as they help prevent overfitting and ensure the model learns efficiently.

Model evaluation: The performance of the model was evaluated using metrics such as accuracy, precision and recall. These are standard evaluation metrics for classification tasks in CNN. 

The successful realization of this project hinges on achieving two key objectives: surpassing a classification accuracy of 80% with our model, and seamlessly generating GIFs to elucidate the model's training progression. These ambitious yet attainable targets are based on the established performance benchmarks of Convolutional Neural Networks (CNN) for analogous tasks.

In the spirit of acknowledging the collaborative nature of coding and data science, this project conscientiously credits all third-party resources that were employed. I leveraged the expansive capabilities of the Tensorflow and Keras libraries extensively to architect and train our CNN models, while the 'imageio' library was utilized for GIF creation. For the training phase, images were sourced from two valuable datasets: the PlantVillage dataset and the Plant Pathology 2020 dataset.

Additionally, meticulous attention has been paid to the readability and comprehensibility of the code, ensuring it is sufficiently commented. This not only facilitates better understanding for those seeking to learn from or build upon this work but also aligns with best practices for coding and documentation.
