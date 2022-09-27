pip freeze > requirements.txt

pip install -r requirements.txt

- conda env commands

- create a new env --- conda create -n <env_name> python=3.7

- to check all the libraries present in a particular env - pip list

- to check what env is active - conda env list

- to activate new env - conda activate <env_name>

- to delete the env - first deactivate then conda env remove -n <env_name>