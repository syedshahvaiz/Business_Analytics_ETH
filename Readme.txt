ReadMe File for Business Analytics Project

There are two ways to get the project running. Both ways lead to the same result. From personal experience it is recommended to follow Approach 2. 

Approach 1: 

Do not start the Jupyter notebook until you have completed Step 1:

## Step 1: Installing Dependencies

- Install the Anaconda (5.3) distribution from https://www.anaconda.com/download/

- Go to Anaconda prompt
  - Create a new environment based on standard anaconda packages using `conda create -n BA anaconda`
  - Activate the enviornment: `conda activate BA`
  - Install Yellowbricks package: `conda install -c districtdatalabs yellowbrick`
  - Install the remaining required packages in the environment using `pip install -r requirements.txt`
  - Install ipykernel: `conda install -c anaconda ipykernel`
  - Type 'python -m ipykernel install --user --name=BA' (This will allow Jupyter to access this enviornment)

## Step 2: Jupyter configuration
- Choose the 'BA' kernel in the kernel section to run the file. 

If the kernel installation fails then you will have to install the missing packages manually in your conda (base) enviornment. 

Packages which might be missing are:

1. scikit-learn: (conda install scikit-learn)
2. yellowbrick: (conda install -c districtdatalabs yellowbrick)
3. plotly: (conda install -c plotly plotly)
4. seaborn: (conda install -c anaconda seaborn)
5. keras: (conda install -c conda-forge keras)
6. imblearn: (conda install -c conda-forge imbalanced-learn)
7. matplotlib: (conda install -c conda-forge matplotlib)

Once these packages are installed in your machine then you will be able to run the notebook and reproduce the results. 

It is highly recommended that you run the notebook on your machine inorder to avoid the incomplete rendering which might be
caused during download/transfer after the submission of this notebook.


Approach 2: 

An enviornment file has already been created titled "BAproject.yml". This is an anaconda enviornment that a user will have to 
import in the anaconda framework and use it for jupyter. All necessary dependencies are already installed in this enviornment. 

Once the enviornment is activated and selected in jupyter, follow the instructions on the Jupyter notebook and run the first 2
cells to check if all dependencies are installed. 



