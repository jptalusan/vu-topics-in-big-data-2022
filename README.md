# Examples

## Updates
* Added OpenAI gym taxi example
* Added Tensorflow, Keras timeseries forecasting examples
* Added Osmnx example

## To follow
* Must add one to one, many to one, one to many and many to many at least for RNNs
* Add PyTorch transformer example
* Add Julia

## Note about Tensorflow with GPUs
* If you prefer to use tensorflow with GPUs, its better to install it using Anaconda or use colab.
```
conda create -c conda-forge -n py39_tf python=3.9
conda activate py39_tf
conda config --add channels conda-forge
conda install tensorflow-gpu
```

# Setup
1. Install [Anaconda](https://www.anaconda.com/products/distribution) 
2. `cd environment`
3. `conda env create --name ENVNAME -f conda.yml`
4. `conda activate ENVNAME`
5. `pip install -r requirements.txt`

* If you plan to use VS Code
* `conda install -n vu_tutorial ipykernel --update-deps --force-reinstall`
