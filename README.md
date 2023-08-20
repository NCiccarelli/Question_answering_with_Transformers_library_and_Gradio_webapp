# Question answering with the Transformers (HuggingFace) library and Gradio webapp

In this repo, we fine tune the BERT model to perform classification on the IMDB dataset

Libraries and installations

The libraries that are used in this repo are reported in the "environment.yml" file.

To install the libraries, execute the following command in Anaconda Prompt:

conda env create -f environment.yml
After the libraries are installed, execute in Anaconda Prompt:

conda activate intro_to_transformers_env
python -m ipykernel install --user --name=intro_to_transformers_env
The latter command is used to install the environment as a kernel in Jupyter notebooks.

Fine tuning the BERT model for text classification

The code that fine-tunes the BERT model for text classification is reported in the repo's jupyter notebook.
