# got_network_viz_python

Exploring different options to visualize network data in Python (here Game of Thrones network)

Complimentary code for the medium Article ["Visualizing Networks in Python
"](https://mohitmayank.medium.com/visualizing-networks-in-python-d70f4cbeb259)

Contents, 
- Files
  1. **GoT_Network.ipynb:** Jupyter notebook with code for Option 1 and 2 from article.
  2. **dash_app.py:** Dash app for option 3 in article.

- Directory
  1. **data:** contains Game of Thrones network data in csv format for the first 5 books

# How to use
1. [Recommended] : use a virtual environment to avoid conflicting with your main installation `python -m venv .venv`
2. [Recommended] : activate the environnement : [ShellCommands] : `source ./.venv/bin/activate`
3. Install packages : `pip install -r requirements.txt`
4. Run the script : `python ./dash_app.py`