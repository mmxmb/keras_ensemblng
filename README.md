# Ensembling ConvNets using Keras

Source code for the practical guide on ensembling convnets using Keras. The guide was [published on Medium](https://towardsdatascience.com/ensembling-convnets-using-keras-237d429157eb) and [my personal website](https://lawnboymax.github.io/2017/12/13/ensembling-convnets-using-keras.html).

## Requirements

1. Ensure you have [Python 3](https://www.python.org/downloads/) installed.
2. *Optional, but recommended:* create a new virtual environment using your favourite virtual environment tool. Examle tools: [virtualenv](https://virtualenv.pypa.io/en/latest/), [pipenv](https://pipenv.readthedocs.io/en/latest/).
3. Install other dependencies: `pip install -r requirements.txt`

## Usage

1. Run `jupyter lab keras_ensembling.ipynb`. Browser window with *Keras Ensembling* Jupyter Lab notebook should come up automatically. If it doesn't come up, navigate to the running Jupyter Lab instance in your browser using the URL displayed in your terminal (i.e. `The Jupyter Notebook is running at: http://localhost:8888/`).
2. Training models in this notebook without a good GPU can take quite a long time. If you don't want to train models yourself, you can use pretrained ones. In this case, simply don't execute the cells where training happens, e.g:
```python3
_, conv_pool_cnn_weight_file = compile_and_train(conv_pool_cnn_model, NUM_EPOCHS)
```
Pretrained model weights will be loaded automatically wherever needed.

## License

MIT License

Copyright (c) 2018 - 2019 Maxim Mikhaylov