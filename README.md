# Generate a corpus with an LLM  

Geoff Ford  
[https://geoffford.nz](https://geoffford.nz/)  

![GitHub Release](https://img.shields.io/github/v/release/polsci/generate-a-corpus-with-an-LLM) [![DOI](https://zenodo.org/badge/840954047.svg)](https://zenodo.org/doi/10.5281/zenodo.13364417)

The notebook in this repository is provided for students in DIGI405 at the University of Canterbury to query a Large Language Model (LLM) to generate a corpus. Students can adapt the code to generate their own data for an assignment.  

I appreciate this notebook may be relevant for others. If you use it please retain the authorship information and links or cite it.  

To learn more take a look at [the notebook](https://github.com/polsci/generate-a-corpus-with-an-LLM/blob/master/DIGI405%20-%20generate%20a%20corpus%20with%20an%20LLM.ipynb). I've also written a post on my website about [how we are using this in class](https://geoffford.nz/generate-a-corpus).  

Changes are documented in the [CHANGELOG](changelog.md).

## Note on OpenRouter

The notebook provides multiple examples that query [OpenRouter](https://openrouter.ai/)'s API. OpenRouter provides a single API endpoint that provides access to multiple LLMs via multiple LLM providers. OpenRouter provides [good documentation](https://openrouter.ai/docs) and access to several [free models](https://openrouter.ai/models?max_price=0). The free models are [rate limited](https://openrouter.ai/docs/limits) with the following limit at the time of writing this: "Free limit: If you are using a free model variant (with an ID ending in :free), then you will be limited to 20 requests per minute and 200 requests per day."  

If anyone from OpenRouter sees this - the free models and rate limits are very helpful for educators. Thank you!  

## Create an OpenRouter API key

Go to [OpenRouter](https://openrouter.ai/) and create an account. Once you are logged in, there will be a menu in the top right corner of your screen. Click on the and then click 'Keys'. Click the option to 'Create Key'. Give it a name (e.g. DIGI405 Lab) and click the 'Create' button. You will be shown an API key. Copy and paste the key into your password manager for future use. There is a field in the notebook where you need to paste in your key. You can delete the key at any time.   

## Instructions for DIGI405 students

Create a folder on our JupyterHub server for this notebook. Upload the files to the new folder and then open the Jupyter notebook.  

### Warning about excessive, rapid or repeated requests during lab times

This is the first semester we are using OpenRouter's service in DIGI405, please avoid making excessive, rapid or repeated requests during the lab times as there is the potential this could cause our network to be flagged as malicious and create problems for your classmates accessing the API.  

## Installation  

There is a requirements.txt file and a cell at the top of the notebook that can be run to install the required libraries OR just run:  

```
    pip install -r requirements.txt
```
