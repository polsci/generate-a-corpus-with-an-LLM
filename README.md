# Generate a corpus with an LLM  

Geoff Ford  
[https://geoffford.nz](https://geoffford.nz/)  

![GitHub Release](https://img.shields.io/github/v/release/polsci/generate-a-corpus-with-an-LLM) [![DOI](https://zenodo.org/badge/840954047.svg)](https://zenodo.org/doi/10.5281/zenodo.13364417)

The notebook in this repository is provided for students in DIGI405 at the University of Canterbury to query a Large Language Model (LLM) to generate a corpus. Students can adapt the examples to generate their own data.  

I appreciate this notebook may be relevant for others. If you use it please retain the authorship information and links or cite it.  

To learn more take a look at [the notebook](https://github.com/polsci/generate-a-corpus-with-an-LLM/blob/master/DIGI405%20-%20generate%20a%20corpus%20with%20an%20LLM.ipynb). I've also written a post on my website about [how we are used this in class in 2024](https://geoffford.nz/generate-a-corpus).  

Changes are documented in the [CHANGELOG](changelog.md).

## Note on OpenRouter support 

Note: that version 1.1.1 of this repository used the OpenRouter API. From version 1.1.2 the notebook uses Cerebras. You can download the 1.1.1 release from the repository if you want to use OpenRouter. 

## Note on Cerebras 

The notebook provides code to query [Cerebras](https://www.cerebras.ai/)'s API. Cerebras provides an API endpoint that provides access to multiple LLMs with generous rate limits for development and testing. Cerebras provides [good documentation](https://inference-docs.cerebras.ai/quickstart) and access to a range of well-regarded models. API calls are [rate limited](https://inference-docs.cerebras.ai/support/rate-limits).  

If anyone from Cerebras sees this - free access to API calls and the provided rate limits are very helpful for educators. Thank you!  

## Create a Cerebras API key

Go to [Cerebras](https://www.cerebras.ai/) and click the link to "Get an API key". For students in DIGI405, you can signup with your UC email address. You should indicate you are a student. You will be shown an API key (partially obscured) and sample code. Copy and paste the key into your password manager for future use. There is a field in the notebook where you need to paste in your key. Don't share your key with anyone else. 

## Instructions for DIGI405 students - warning about excessive, rapid or repeated requests during lab times

This is the first semester we are using the Cerebras service in DIGI405, please avoid making excessive, rapid or repeated requests during the lab times as there is the potential this could cause our network to be flagged as malicious and create problems for your classmates accessing the API.  

## Installation  

If you are a DIGI405 student running this on our JupyterHub instance, all required libraries are pre-installed. If you want to install this on your own machine, there is a requirements.txt file with required libraries. To install the required libraries run:  

```
    pip install -r requirements.txt
```
