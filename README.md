# install-tensorflow-and-keras-and-torch-numpy


Create an environment by using AI libraries
Start the Anaconda prompt application (or terminal on Mac). Start the prompt by searching for anaconda on your computer. At the Anaconda prompt, enter the following code:

conda create -n myenv python=3.7 pandas jupyter seaborn scikit-learn keras pytorch pillow

This code installs all the libraries we need through Anaconda. You'll download a few other libraries that are good data science libraries you might find useful in the future.

You'll be prompted to install the packages. Enter Y, and then press Enter.

You'll need to activate your new environment. To activate the environment, enter the following code:

conda activate myenv

The new environment should be created and ready to use. Then, we need to add one more library to the environment.

Install torchvision
To install torchvision, at the Anaconda prompt, enter the following code:

conda install -c pytorch torchvision

You'll be prompted to install the packages. Enter Y, and then press Enter.
