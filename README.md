# About the Project
This is a final project for the course CISB62 in Mt.SAC.
## Description
For this project, I want to try image clustering using SOM and image generation using GAN.

You can find the data here: <br>**Anime VS Cartoon VS Human**:([https://en.wikipedia.org/wiki/Haiku](https://www.kaggle.com/datasets/hadiepratamatulili/anime-vs-cartoon-vs-human)

The main steps are as follows:

- Split data into different folders and load data using tf.data.Dataset API.
- Analyze and preprocess the data to prepare for the training.
- Use <b>SOM</b> to build a model for image clustering.
- Use <b>Conditional GAN</b> to generate images with different labels.
- Use <b>Callbacks</b> for training the model
- Save the GAN model and deploy the model with <b>Flask</b>.

Please check [here](CISB62_Final_Chao.ipynb) to see my project in detail.
