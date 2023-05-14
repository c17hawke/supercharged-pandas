# Supercharged-Pandas

This is demo repository to show the capabilities of **`PandasAI`** python package.

Refer demo notebook [here](notebooks/demo.ipynb)

## Tutorial is available on YouTube [Click on the following thumbnail]-

[![Watch the video](https://img.youtube.com/vi/S49aRE9CS6A/maxresdefault.jpg)](https://www.youtube.com/watch?v=S49aRE9CS6A)


## Steps to do the basic setup -

### *STEP 0*: Main requirements -

Make sure you have the following requirements to successfully execute the code:

1. A python environment with version 3.9 or above.
    > *IMPORTANT: PandasAI can work with python 3.9 onwards*
2. A python environment with the following dependencies installed -
    - notebook
    - ipywidgets
    - python-dotenv
    - *pandasai*
    - pandas

### *STEP 1*: Get your Openai API key -

Create a `.env` file in the root of the project from the copy of `.env.template`.
And replace the OPENAI_API_KEY with your Openai API key

> NOTE: 1. You can obtain from - [OpenAI Keys](https://platform.openai.com/account/api-keys) 2. Refer the following screenshot - ![screenshot](images/ss-openai-api-key.png)

### *STEP 2*: Initialize bash script for the project setup

run the following command-

```bash
bash init_setup.sh
```

> NOTE: Make sure you have gitbash intalled in your Windows laptop, otherwise for any other Linux based OS its not required

### STEP 3: Activate the environment

```bash
conda activate ./env
```

### STEP 4: Launch the jupyter notebook


## References -

1. [Pypi PandasAI](https://pypi.org/project/pandasai/)
2. [PandasAI github/docs](https://github.com/gventuri/pandas-ai)
