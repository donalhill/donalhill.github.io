## Machine learning

During my physics career at CERN, I have applied machine learning methods extensively in data selection and processing tasks. My work has included the use of XGBoost for signal selection (binary classification), and the determination of decay kinematics in cases where not all particles are reconstructed (regression). As co-founder of the environmental start-up [Plastic-i Ltd](https://www.plastic-i.com/), I am also applying computer vision methods to detect ocean plastics with satellite imagery. 

Machine learning continues to find applications across a wide range of academic and industrial fields, thanks to the explosion in big data, the availability of affordable cloud computing resources, and the development of cutting-edge open-source software such as [TensorFlow](https://www.tensorflow.org/). Deep learning in particular is enjoying a prolific period of growth, with the advent of models such as [DALL·E 2](https://openai.com/dall-e-2/) for image generation from text captions, and ever-improving libraries of powerful [pre-trained models](https://huggingface.co/).

### NLP for classifying sentences in paper abstracts

In this [notebook](https://github.com/donalhill/portfolio-projects/blob/main/NLP_PubMed.ipynb), I explore the application of Natural Language Processing models in Keras, as I aim to replicate the 2017 paper [PubMed 200k RCT: a Dataset for Sequenctial Sentence Classification in Medical Abstracts](https://arxiv.org/abs/1710.06071).

### U-Net CNN for segmentation of cells in microscope images

In this [notebook](https://github.com/donalhill/portfolio-projects/blob/main/cell_segmentation.ipynb), I apply a U-Net Convolutional Neural Network (CNN) to the task of classifying cells in microscope slide images. U-Net models are designed for semantic segmentation, where every pixel in an image is assigned a class prediction. In this case, we are dealing with a binary classification problem: does a pixel belong to a cell or not?
