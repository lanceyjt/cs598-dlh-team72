## CS 598 Deep Learning for Health Care Project - Team 72
 * Timothy Ta (ta14@illinois.edu)
 * Ariel Chiang (arieltc2@illinois.edu)
 * Jingtian Yao (yao28@illinois.edu)

#### **Github Repo:** https://github.com/lanceyjt/cs598-dlh-team72

This Github repo intends to reproduce the [CASTER (Huang et al., 2020)](https://arxiv.org/abs/1911.06446) neural network framework and experiments discussed in the original paper. It incorporates original code sourced from the GitHub repository: https://github.com/kexinhuang12345/CASTER/tree/master.

The Jupyter notebook ```DL4H_Team72.ipynb``` contains all the information for this project, including model architecture, model training, evaluation, results and discussions.

Use one of the methods below to run the notebook.

### Option 1: Amazon SageMaker Notebook
The training process is implemented in an [Amazon SageMaker](https://aws.amazon.com/sagemaker/) notebook with an **ml.p3.8xlarge** instance. Click [here](https://docs.aws.amazon.com/sagemaker/latest/dg/notebooks-available-instance-types.html) for more information.

Follow the steps below to reproduce the code:

1. Follow the [instructions](https://docs.aws.amazon.com/accounts/latest/reference/manage-acct-creating.html) to create an AWS account, or log in to an existing AWS account.

2. Follow the [instructions](https://docs.aws.amazon.com/sagemaker/latest/dg/gs-setup-working-env.html) to create a SageMaker instance, **ml.p3.8xlarge** instance is recommended, but can consider other instance types with GPUs too. (**Note**: You will pay for the instance computation and storage, click [here](https://aws.amazon.com/sagemaker/pricing/) for more pricing information)

3. After the status of the SageMaker instance becomes "Active", click the "Open JupyterLab" from the upper right.

4. Launch a terminal window from the instance, run the commands below:

```
cd ~/SageMaker
git clone https://github.com/lanceyjt/cs598-dlh-team72
```

5. Run the code blocks in the notebook ```DL4H_Team72.ipynb```  in sequential order. The parameter ```LOAD_FINAL_MODEL``` in the first block is set to True by default. If you would like to perform the model training process, set it to False.


### Option 2: Google Colab

