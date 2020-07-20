# Dog Breed Recognition project

This is a machine-learning project on building a dog breed recognition model out of breed-labelled dog pictures. This project uses deep learning.

The stages of the project were the following:

- Preprocessing the data:
  - turning (non-numerical) image data into tensors (numerical);
  - turning data into batches;
- Modelling the data with *convolutional neural networks*;
- Creating callbacks for:
  - tracking the model's progress;
  - preventing overfitting;
- Evaluating the model's performance;
- Making predictions on test data and our own pictures;
- Saving the model.

This project was written in Python using its data analysis tools, such as Pandas, NumPy, matplotlib, as well as advanced machine-learning tools, namely TensorFlow (through Google Colab).


## Explanation of files

This was a Kaggle competetion, and the data is available at: https://www.kaggle.com/c/dog-breed-identification/data.

The Jupyter notebook `dog-vision.ipynb` contains the project's code and report.

And the folder `models` contains some saved models we built during this project.
