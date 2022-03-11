# Facial Recognition using Traditional Machine Learning

## Setup guidelines for project:

1. Setup new virtual environment(venv) for running facial recognition using basic machine learning jupyter notebook using on Windows. Refer my [post](https://contactmansi.github.io/workoutdata/markdown/2022/01/29/Virtual-Environment-Jupyter-Notebook.html) for a quick setup.
2. Once the virtual environment has been created and activated, open a new terminal window simultaneously for cloning this project
3. On this new terminal window, avigate to local directory on your computer where repository files will reside
```
cd path_to/desired_local_directory/
```
3. Clone this github repository into your local directory 
```
git clone https://github.com/contactmansi/facial-recoginition-traditional-machine-learning.git
```
3. Switch back to venv activated terminal to install all required dependencies
```
cd path_to/local_directory_containing_requirements_file
pip install -r requirements.txt
```
3. Place `FisherFace.py` and `face/` folder containing all dataset images in the same directory as source jupyter notebook, following the file structure in this repo
4. To add new virtual environment to existing jupyter notebook setup on windows, follow this [post](https://contactmansi.github.io/workoutdata/markdown/2022/01/29/Virtual-Environment-Jupyter-Notebook.html) till the end.
5. Activate new venv using kernel option in jupyter notebook and run all cells
6. Expect `train/` and `test/` folders to be created in the same directory as jupyter notebook

### Hope you enjoy exploring this project!