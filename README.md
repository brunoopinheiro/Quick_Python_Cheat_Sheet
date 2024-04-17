# Quick_Python_Cheat_Sheet
Repository made to easily store python snippets to ease of reference.
This project was heavily inspired by [Jason Roell](https://medium.com/@roelljr)'s post on Medium, [Ultimate Python Cheat Sheet: Practical Python for Everyday Tasks](https://medium.com/@roelljr/ultimate-python-cheat-sheet-practical-python-for-everyday-tasks-c267c1394ee8).

A lot of the snippets contained in the Jupyter Notebooks are initially from his article.

You can quickly go to a notebook, based on the main theme:

| Theme      | Description | Link |
|------------|-------------|------|
| Working With Files | General file Operations | [notebook](notebooks/working_with_files/working_with_files.ipynb) |
| Working With HTTP API | General HTTP Requests | [notebook](notebooks/working_http/working_with_http_api.ipynb) |
| Working With Lists | Basic List Operations | [notebook](notebooks/working_with_lists/working_with_lists.ipynb) |


## Running Locally
The idea behind this project is that you can check each code snippet directly on **GitHub**. If you want to run each of those snippets yourself, after cloning the project you should:
1. Initiate a virtual environment:
```powershell
python -m venv .venv
```
2. Activate the virtual environment:
 - (windows)
```powershell
.\venv\Scripts\activate
```
  - macOS and Linux:
```bash
source .venv/bin/activate
```
3. Install the dependencies:
```
pip install -r requirements.txt
```
**Remember:** Always deactivate your virtual environment when you're done coding. You can do this by simply typing:
```
deactivate
```