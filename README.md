# LMs_Session

This is the introduction to Language Models session notebook for use at WANDISCO. 

## Running in Colab

Open [google colab](https://colab.research.google.com/) and navigate to the GitHub tab. Search for "wrmthorne" and select `LMs_Session` in the dropdown and open the notebook `lms_notebook.ipynb`. You can then run through the notebook as normal.

## Running Locally with VSCode

Clone the git repo. From here, you can either install the packages to your global python install (not recommended but easier) or install them to a virtual environment (recommeded but a couple more steps). To just use your global python install, select the python 3.x.x kernel in the top right of VSCode after opening the notebook. Then run the notebook as normal. To install to a virtual environment:

1. Open a terminal window in the repo directory on your machine
2. Enter the command
```bash
python3 -m venv lms_venv
```
3. Open the notebook in VSCode and select the virtual environment in the top right

    a) If this doesn't appear, press `CTRL + SHIFT + P` and type "interpreter" in the search bar

    b) Select "Python: Select Interpreter" from the dropdown
    
    c) If the environment appears in the list, select it, if not select "Enter interpreter path" and then find.
    
    d) Navigate to "lms_venv/bin/python3.x" (where x is the version you are using) and select it
    
    e) Restart VSCode and select it in the top right 
    
4. Run the notebook as normal from now on