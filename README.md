# LLaVA_Evaluation

This repository contains image captioning evaluation experiments on the Flickr8k-Expert dataset using the LLaVA model. These experiments were conducted for the seminar "Seminar CS715: Solving Complex Tasks using Large Language Models" of the University of Mannheim, following the topic "LLMs as Evaluation Metrics". The notebook files used to execute the experiments and the CSV result files are included.

The csv results files include (1) the file name of the image, (2) the image caption, (3) the candidate score of the selected model, (4) the average human score.

In order to reproduce the results, execute the following steps:
  1) Install LLaVA like explained in its repository: [haotian-liu/LLaVA](https://github.com/haotian-liu/LLaVA)
  2) Download the images of the Flickr8k-Expert dataset (e.g., from [here](https://www.kaggle.com/datasets/sayanf/flickr8k)) and store them in a folder called "Flickr8k_Dataset"
  3) Execute the notebook file "Image_Captioning_Evaluation.ipynb". Select the desired model in the second cell and execute the experiments. **Note:** the already existing result files should be deleted beforehand.
  4) Execute the notebook file "Evaluation.ipynb" to obtain the accuracies and Kendall's Tau of the experiments.
