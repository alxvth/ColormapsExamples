# ColormapsExamples

Small, interactive colormap example.

## Local

``` bash
conda create -n my-conda-env           # creates new virtual env
conda activate my-conda-env            # activate environment in terminal
cd my-local-path                       # change to this repo directory 
conda install --file requirements.txt  # install jupyter + notebook and other requirements
jupyter notebook                       # start server + kernel inside my-conda-env
```

## Online

### Binder.org

Binder can open a public repo and even automatically installs the `requirements.txt`.
Open https://mybinder.org/, use `https://github.com/alxvth/ColormapsExamples` as the GitHub URL and specify `main` as the Git ref. Press `launch`, wait some seconds and get started.

Alternatively, simply open:
https://mybinder.org/v2/gh/alxvth/ColormapsExamples/main

### Google Colab

If you are logged in with a Google accont, you can run this on Google Colab be replacing `https://github.com` in the url of any notebook in this repo with `https://colab.research.google.com/github/`, e.g. to start `ColormapsExampleWithGray.ipynb`, open:

https://colab.research.google.com/github/alxvth/ColormapsExamples/blob/main/ColormapsExampleWithGray.ipynb

(Since not all requirements are installed, you also cannot be sure that all modules are of a compatible version. E.g. the matplotlib version might not have the "turbo" colormap.)