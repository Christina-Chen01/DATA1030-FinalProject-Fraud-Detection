# Mobile Phone Transactions Fraud Detection

The prevalence of mobile phone transactions has turned individual monitoring for fraudulent activity into a task that is both crucial yet complicated. Failing to maintain a robust fraud detection system can result in considerable risks, such as major financial losses for both businesses and individuals, diminishing customer trust, and increased operational expenses for financial institutions.

This project aims to evaluate an extremely imbalanced transaction dataset through supervised machine learning methods – Logistic Regression, K Nearest Neighbor, Random Forest, and XGBoost – for fraud detection in a Jupyter Notebook or any other coding environment. 

I hope that by the end, participants will be well-equipped to start innovating with ChatGPT and develop their own applications.

I assume participants have basic Python knowledge and know how to work with containers (such as lists and dictionaries), control flow (like for loops and if statements), and functions.

## Prerequisites

Please run `test_environment.ipynb`. It checks the versions of your python and some packages (like pandas, openai). If the notebook returns all OK, you should be able to run the code without issues. If some FAILs are returned, you need to install/update those packages first.

You can recreate the python environment using the `dscov-chatgpt.yml` conda environment file by running these two commands in the terminal:

`conda env create -n dscov-chatgpt -f dscov-chatgpt.yml`

`conda activate dscov-chatgpt`

You should be able to run `src/DSCoV - ChatGPT API.ipynb` now.

## OpenAI API key

You will need an API key to query ChatGPT. Follow the instructions [here](https://tfthacker.medium.com/how-to-get-your-own-api-key-for-using-openai-chatgpt-in-obsidian-41b7dd71f8d3) to obtain one. Note that the API access is not free, check out pricing [here](https://platform.openai.com/docs/quickstart/pricing). For reference, it costs me maybe $0.05 to develop and test the code for this presentation.

## Author

Andras Zsom (andras_zsom@brown.edu)

## License

This project is licensed under the MIT License.
