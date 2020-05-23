# Setup this repo
1. Create a parent folder for this repo. `mkdir template_trunk`
2. initialize it as a virtual environment. `virtualenv --python=python3 template_trunk`
3. navigate into parent `cd template_trunk`
4. clone the repo: `git clone git@github.com:ianliu-johnston/template.git`
5. navigate into repo: `cd template`
6. activate the virtual env: `source ../bin/activate`
7. link the activate script here. `ln -s ../bin/activate .`
8. change "template" to your program name in setup.py
9. install pip requirements: `pip install -r requirements.txt`
10. Setup pytest: `pip install -e .`
11. Setup precommit hooks
