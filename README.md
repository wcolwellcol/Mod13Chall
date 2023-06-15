# Mod13Chall
Repo for Week 13 Challenge of Fintech Course in which I attempt to create three different deep learning models to predict whether start ups will be successful given certain details about their company.

---
## Technologies
This code was written using Python 3.7.13. I had to utilize google colab for various purposes, mainly because some of the code is expensive and is better run in the cloud. 

My OS is Ventura 13.2.1 though it should be fine on most others. Note that the CLI in any screenshots may look different on different OSs.

I used conda to manage all of my packages.
Packages used:
tensorflow
sklearn


---
## Installation
I do not recommend installing these packages. Rather, I would recommend a local install utilizing !pip install like you can observe in the forecasting_net_prophet.ipynb notebook.




---
### Usage
The goal of this project is to create a deep learning model (neural network) to predict whether startups will be successful given certain metrics. I created three different models (nn, nn_A1, nn_A2) which utilize varying numbers of nodes and layers in an attempt to improve accuracy and loss. The weights of these models are all stored in [resources](https://github.com/wcolwellcol/Mod13Chall/tree/main/Resources) as three separate h5 files aptly named AlphabetSoup, AlphabetSoupA1, and AlphabetSoup2.
 Unfortunately, I was not too successful at optimizing.

Code can be found in the following notebook [GC_venture_funding_with_deep_learning.ipynb](https://github.com/wcolwellcol/Mod13Chall/blob/main/GC_venture_funding_with_deep_learning.ipynb).

Data for this project is sourced from a csv found in the [resources](https://github.com/wcolwellcol/Mod13Chall/tree/main/Resources) folder.


## Contributors

This code was written by me, but the framework was provided by the Columbia Fintech Bootcamp

## License

MIT License

Copyright (c) [2023] [willcolwell]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.