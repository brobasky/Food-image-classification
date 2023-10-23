# Food-image-classification
binary image classification using a convolutional neural network.  The model uses keras functionality and a subset of the 'Food 101' to determine whether an image is chicken wings or ice cream.

# installation
1. clone repository to your local machine
```bash
git clone https://github.com/brobasky/Food-image-classification.git 
```
2. navigate to project directory
```bash
cd Food-image-classification
```

3. Download Food 101 Dataset through this link: https://www.kaggle.com/datasets/kmader/food41 (The subset I used was too large to upload to Github even as a zip file).  Extract files as necessary.  To run the notebook, the 'images' folder should have no nested directories and should be saved to the same directory as the notebook.

4. Create a virtual environment (optional but recommended)
```bash 
python -m venv venv
source venv/bin/activate # On Windows, use "venv\Scripts\activate"
```

# Usage

1. Launch Jupyter Notebook
```bash
jupyter notebook
```

2. In Jupyter Notebook interface, open 'food_image_classification.ipynb' file.

3. Click 'Cell'-> 'Run All' in the taskbar to run all the code or use shift+enter to run cells one at a time

