# com.mcast.project.briffaTravis
Research Design 1 Project

# Setup

- Install Python 3.10
- Install Anaconda
- From Windows find Anaconda Prompt and run as administrator. 
- Run the following commands:

```
conda create --name travis python=3.10
conda activate travis
conda install -c conda-forge numpy
conda install -c conda-forge scipy
conda install -c conda-forge seaborn
conda install jupyter
ipython kernel install --name "travis-kernel" --user
conda install -c conda-forge matplotlib
conda install -c conda-forge pandas
conda install -c anaconda scikit-learn
conda clean --all
conda deactivate
```

# References
- [Initial Tutorial](https://www.geeksforgeeks.org/disease-prediction-using-machine-learning/)
