## Algorithmic Trading Bot with Machine Learning Capabilities

This repository hosts a powerful algorithmic trading bot developed using Python, combining financial programming and machine learning skills. The bot is designed to learn and adapt to new data and evolving market scenarios, with an aim to automate trading decisions.

Inside a Jupyter notebook, you'll find the following:

- Implementation of a machine learning-based algorithmic trading strategy, designed to make autonomous trading decisions.
- Techniques to adjust input parameters to optimize the trading algorithm's efficiency.
- Procedures to train a new machine learning model, along with a comparative analysis of its performance against a baseline model.

Below is a detailed report that analyzes the performance of the machine learning models. The analysis is rooted in the trading predictions made by each model and the cumulative returns achieved by each strategy. This comprehensive report will serve as a guide, helping you grasp the operational effectiveness of the algorithms and the potential return scenarios they can create.

Last Updated: 2023-06-25.


---

## *Technologies*

- **Programming Language:** Python
- **Libraries:** Pandas, pathlib, hvplot, sklearn, numpy, matplotlib

- **Framework:** JupyterLab
- **Operating Systems:** Mac OS, Microsoft Windows

---

## *Installation Guide*

If you don't have Python, JupyterLab, or Anaconda installed on your operating system:

-**[Install Python](https://www.python.org/downloads/)**

-**[Install JupyterLab](https://jupyter.org/install)**

-**[Install Anaconda](https://docs.anaconda.com/free/anaconda/install/index.html)**


**1. Conda 'dev' Environment** - To run the main application you will need to create a new enviornment that will be compatible with this application, type and enter the following. You will still use the previous steps' command to activate:

        conda create -n env_name python=3.7 anaconda

Activate conda enviorment by running the following function:

        conda activate env_name 

**2. Other Libraries** - It was mentioned earlier that the other required libraries should already be installed with the Anaconda package. To confirm installation for these libraries, you can either use the 'conda list' command followed by the library name to confirm installation. Or, you can install the libraries which will either install successfully or if already installed, will result in a 'requirement already satisfied' message. Listed below are the commands to install each library if needed:
        
        pip install sklearn
        pip install tensorflow


**3. Clone Repo**

After completing all prerequisite installations, you're ready to clone this repository to your local machine. To do this, begin by copying the SSH keys.

Next, navigate to the directory in your terminal where you want this repository to be placed. Once you're in your desired directory, execute the following command:

        git clone 'paste ssh keys here'

To operate the repository in JupyterLab, navigate into the repository folder by typing:

        cd 'repository folder name'

Then, initiate JupyterLab by entering:

        jupyter lab

___


# Report: Exploration and Evaluation of Machine Learning Models for Algorithmic Trading

## Methodology

1. **Establishing Baseline Performance**: The initial step involved setting a benchmark using the Support Vector Machine (SVM) classifier from sklearn's SVM learning method. The trading signals for this baseline model were generated using short window and long window Simple Moving Averages (SMA).

2. **Tuning the Baseline Trading Algorithm**: Subsequently, I fine-tuned the baseline trading algorithm by adjusting the size of the training dataset and the SMA input features. 

3. **Evaluating a New Machine Learning Classifier**: A new Machine Learning classifier, AdaBoost, was introduced. Using the original training data, I evaluated its performance. This new model underwent backtesting to gauge its performance and subsequently compare it with the baseline SVM model and the tuned trading algorithm.

4. **Generating an Evaluation Report**: The final phase of the process was the creation of an evaluation report that summarizes the findings of the analysis. The report was supplemented with PNG images created at each step to visually represent the outcomes.

## Results

The plot showcasing the Baseline Trading Algorithm's performance can be viewed in 'actual_vs_strategy_returns.png', while the Tuned Baseline Trading Algorithm's plot is located in 'new_actual_vs_strategy_returns.png'.

## Conclusions

Upon examining the effect of adjusting the training window size, it was observed that a slight increase had a detrimental impact on the strategy returns in the tuned algorithm.

Comparative performance analysis revealed that the newly tuned model underperformed in comparison to the baseline algorithm. Thus, the efforts to fine-tune the trading algorithm did not result in improved performance.

---

## *Contributors*

**Rosalinda Olvera Fernandez**

[GitHub](https://github.com/rolvera05) - rolvera98271@gmail.com

