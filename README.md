# Running Speed Prediction Using Lumo Run IMU
Code repository for Lumo Run running speed prediction project

## Description of Folders
- Codebase : Contains code (i.e. Python scripts) to build neural networks models
- Confusion Matries : .csv and .png image files of confusion matrices for each model run
- Learning Curves : .csv and .png image files of training and validation learning curves for each model run
- Model Final Parameters : stores parameters for each model of appropriate architecture
- Model Final Predictions : results of each model run on validation set 
- Model Performance Tables : tracker tables storing performance metrics per model, such as mean absolute error
- Saved NP Arrays : raw kinematic running data and labeled spped stored as numpy arrays for easy access

## Notes
- The models are built and trained in scripts SpeedPrediction_FFCN_CNN_keras.ipynb and SpeedPrediction_Helper.py. The scripts declare a model architecture, run training, and store results and select charts/tables in appropriate folders labeled by the model name (as declared in the "SpeedPrediction..." script).
- [Important] All data files have been removed from the repository due to restrictions on data access. For this reason, all code linked linked to the anticipated data folders/files will fail. We recommend using these scripts as a framework to build similar models, but do not expect scripts to be functional as written (due to hardcoded dependencies on data file location). 
discription of necessary modules and libraries.
- Code was written using Jupyter Notebooks and Python 3.6. Please consult file "Codebase/SpeedPrediction_FFCN_CNN_keras.ipynb" for a description of required modules and libraries.
- Feel free to email agotlin@stanford.edu for thoughts/questions
