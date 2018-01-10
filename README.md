# Simple Adversarial Examples

![alt text](./images/adversarial_example.jpg "Adversarial Examples!")

This repo contains an ipython notebook (along with corresponding helper python classes) that implements adversarial example generation for a neural network trained on MNIST, and also implements some (very) simple security measures against adversarial attacks. The majority of the base neural network impelmentation was shamelessly lifted from [neuralnetworksanddeeplearning.com](http://neuralnetworksanddeeplearning.com/). To run this notebook you will have to have `jupyter notebook` or `ipython notebook` installed. In addition, the code will need `numpy` and `matplotlib` as dependencies. 

Once everything is installed go to the root directory of this repo in the terminal and run either 

`$ jupyter notebook` 

or 

`$ ipython notebook`

A window should open up automatically in your browser. If not the output to the terminal should have a link you can put into a browser of your choice. It looks something like this 

`http://localhost:8888/?token=e848ccafeeea4a0d9d78659f943eedd4e94414add29f2f82`

Finally, in the tree view of the ipython notebook click on `adversarial_example.ipynb` to start the notebook. 

For more info about how to use Jupyter Notebooks check out the [docs](http://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html)
