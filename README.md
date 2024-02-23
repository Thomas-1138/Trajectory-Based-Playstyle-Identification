# Trajectory Based Playstyle Ientification
This project has been created in the scope of the practical work course at JKU.
It contains all necessary files for executing the **single_round_tests.ipynb** notebook.

## Environment Setup
To run this project, you will need to set up the environment and install the necessary dependencies.
Run the following commands in the terminal 
```
git clone https://github.com/Thomas-1138/Trajectory-Based-Playstyle-Identification.git
cd Trajectory-Based-Playstyle-Identification
```

Then, set up the environment for the project (make sure your terminal is opened inside the project folder):
```
conda env create -f environment.yml
```

To activate the environment in the terminal:
```
conda activate trajectory_project
```


### Data Setup
Before running the **`main.ipynb`** notebook, you must first download the dataset and store it locally on your machine.
Go to [this GitHub repository](https://github.com/pnxenopoulos/esta) and download the data.
In the **`main.ipynb`** file, you will then need to adjust the path of the dataset to where you have stored it locally.
For example, if you have it stored at **`D:\Practical_Work\data\`**, ensure the path in the notebook matches your local setup.

### Running the Experiment
The only thing that's left is to run the whole project!
In the **`main.ipynb`** notebook, you can see the entire process from preparing the data, computing the metrics, performing PCA and KMeans, and later plotting some boxplots to analyze the different playstyles.
Enjoy exploring the data!
