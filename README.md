# Time series forecasting short course

Short course on time series forecasting, taught as a part of Machine Learning course at AGH.

Lectures:
1. [Introduction to time series](lectures/1_ts_intro.pdf) - decomposition, transformations, baselines, evaluation
2. [Statistical forecasting models](lectures/2_ts_statistical_models.pdf) - ARIMA, ETS, regression
3. [Neural forecasting models](lectures/3_ts_neural_models.pdf) - linear, MLP-based, transformers, foundation models

Hands-on laboratories (Jupyter Notebooks):
1. [Statistical forecasting models](lab1_statistical_models)
2. [Neural forecasting models](lab2_neural_models)

To install dependencies, using [uv dependency manager](https://docs.astral.sh/uv/).
If you want to use pure venv, use provided `requirements.txt` file to install dependencies.

If you have NVidia GPU and want to use for neural networks in lab 2, check if you have
it available after install. See [uv docs for PyTorch](https://docs.astral.sh/uv/guides/integration/pytorch/#installing-pytorch)
for details.

If you notice any errors, please report an issue / make PR.

### License notes

Images on lecture slides belong to their respective creators. I cited every source, but
if I missed something, or you want your image removed, please report the issue on GitHub.

Datasets used in notebooks use their original licenses, as per their original sources,
cited in notebooks.

Everything else, in particular slides and notebooks themselves, is shared under the MIT
license.
