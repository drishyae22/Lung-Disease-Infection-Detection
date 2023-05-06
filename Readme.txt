LUNG DISEASE INFECTION DETECTION

I developed a pipeline that uses CXR images to detect COVID-19 and Pneumonia. In this pipeline, the features from the radiographs are extracted, and only the relevant features are selected using a hybrid model of bio-inspired algorithms, combining a modified Social Group Optimization (SGO) algorithm, which we call Hybrid SGO algorithm (HSGO), and Particle Swarm Optimisation (PSO). The features selected using this model were then used in classifying radiographs using Deep Learning algorithms.

NEED OF THE MODEL:
The previously proposed DL models require large amounts of data for training purposes, which could be challenging to obtain in pandemics like COVID-19. Therefore, a robust solution is required that efficiently works on small data and gives extraordinary results. I have combined two evolutionary algorithms to develop a hybrid model which can be trained with small datasets and still yields great accuracy.

RESULTS:
The model was trained on 2,338 images (comprising of 3 classes- Covid, Normal and Pneumonia) and tested on 553 images. It outperforms other existing methods in terms of accuracy of 98.32%.

NOTE:
The code has not been uploaded because the research paper is yet to be published.

