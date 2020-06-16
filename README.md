# AI Programming with Python Project

Project code for Udacity's AI Programming with Python Nanodegree program. In this project, I developed code for an image classifier built with PyTorch.

### Hardware Requirement
This project requires a lot of computation to train the neural network. The code is written to run on an Nvidia GPU. Using a CPU would take hours to complete as compared to using a GPU which could take a half hour or less. At the time this code was written Pytorch only works on Nvidia GPUs.

### Install

This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [Pytorch](https://pytorch.org/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

I recommend installing [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains most of the necessary libraries and software for this project.

### Code

Template code is provided in the `Image Classifier Project.ipynb` notebook file. You will also be required to use the flower dataset which can be found [here](https://s3.amazonaws.com/content.udacity-data.com/nd089/flower_data.tar.gz). This dataset will need to be decompressed using a tool from [Rarlabs](https://www.rarlab.com/download.htm). Place the dataset under the directory _Image-Classifer/Flowers/_.

### Data

The dataset consists of 102 types of flowers. It is split into three parts, training, validation, and testing. Each part is in a separate folder under the _Image-Classifer/Flowers/_ folder.

### Run

Simply launch the Jupyter Notebook software from the Anaconda software package then open the file `Image Classifier Project.ipynb` to excute the code.

or

In a terminal or command window, navigate to the top-level project directory `Image-Classifer/` (that contains this README) and run one of the following commands:

```bash
ipython notebook Image Classifier Project.ipynb
```  
or
```bash
jupyter notebook Image Classifier Project.ipynb
```

This will open the iPython Notebook software and project file in your browser. From there you can execute the code by running each cell.
