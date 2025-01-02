# MachineLearning
This repo contains a few machine learning projects using LLMs, Deep Learning, and Matrix decompositions (SVD/PCA)


## LLMs

### Chatbots

* ### Simple Chatbot Powered by Mistral, Gemma, and Zephyr
  * In this project we look at creating a simple chatbot using Streamlit and pulling models from Hugging Face for inference.
    <br>We use the Mistral 7B model from Mistral AI, the Gemma models from Google, and the Zephyr model which is a fine tuned Mistral model by the team at Hugging Face. 
    * You can read more about the project [here](https://ngebodh.github.io/projects/2024-03-05/).
    * You can try try the interactive demo [here](https://ngebodh.github.io/projects/2024-03-05/index_demo.html).
     <br> **Note:** The Gemma models are currently being updated for inference and may not work at times. Hugging Face periodically updates and models may be unavailable at times.
     <br>
     <img src='https://github.com/ngebodh/MachineLearning/blob/master/images/LLLMChatbot.gif' width="65%"/>

### General

* ### Experimenting with LLM temperature values
  * [Here](https://ngebodh.github.io/projects/Short_dive_posts/LLM_temp/LLM_temp.html) we look at how changing the LLM temperature parameter affects the outputs.
     <img src='https://github.com/ngebodh/MachineLearning/blob/master/images/LLM_temp_scale.gif' width="65%"/>



<br>

## Deep Learning
### Image Recognition & Classification

* #### ResNet50
  * [Here](https://nbviewer.jupyter.org/github/ngebodh/MachineLearning/blob/master/DeepLearning/ImageRecog/DeepLearningWithKeras-ImageRecog.ipynb) we use the ResNet50 model in keras to perform image recognition. Notebook code [here](/DeepLearning/ImageRecog/DeepLearningWithKeras-ImageRecog.ipynb).<br/>
[<img align="center" src='https://ichef.bbci.co.uk/news/624/cpsprodpb/1245E/production/_102564847_gettyimages-946921072.jpg' width="35%"/>](/DeepLearning/ImageRecog/DeepLearningWithKeras-ImageRecog.ipynb)

<br>

* #### VGG16
  * [Here](https://nbviewer.jupyter.org/github/ngebodh/MachineLearning/blob/master/DeepLearning/ImageRecog/DeepLearningWithKeras_ImageRecog_VGG16.ipynb) we use the VGG16 model in keras to perform image recognition. Notebook code [here](/DeepLearning/ImageRecog/DeepLearningWithKeras_ImageRecog_VGG16.ipynb).<br/>
  [<img align="center" src='https://miro.medium.com/v2/resize:fit:1200/1*ATIx1SmkEH0FaL_5fMvX2w.jpeg' width="55%"/>](/DeepLearning/ImageRecog/DeepLearningWithKeras_ImageRecog_VGG16.ipynb)

<br>

* #### Simple Classifier From Scratch
  * [Here](https://nbviewer.jupyter.org/github/ngebodh/MachineLearning/blob/master/DeepLearning/ImageRecog/DeepLearning_DigitClassificationWithKeras.ipynb) we build a deep neural network to classify hand written digits from the MNIST dataset. Notebook code [here](DeepLearning/ImageRecog/DeepLearning_DigitClassificationWithKeras.ipynb).<br/>
  [<img align="center" src='https://i.ytimg.com/vi/ur6JY2Hl-MM/hqdefault.jpg' width="35%"/>](DeepLearning/ImageRecog/DeepLearning_DigitClassificationWithKeras.ipynb)
  
<br>

* #### PCA / SVD Image Decomposition 
  * [Here](https://nbviewer.jupyter.org/github/ngebodh/MachineLearning/blob/master/SVM/EigenFaces_PCA.ipynb) we use a combination of PCA and SVMs to classify famous faces. Notebook code [here](SVM/EigenFaces_PCA.ipynb).<br/>
  [<img align="center" src='https://upload.wikimedia.org/wikipedia/commons/6/67/Eigenfaces.png' width="20%" hight="40%"/>](SVM/EigenFaces_PCA.ipynb)


  
<br>





