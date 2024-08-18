# Chest-Cancer-Classification-MLOPs

## Steps:

1. Created template.py so that it will create the neccessary folder so that the project will be in the modular way. We'll also have init files in every folder as a constructor file.

2. python3 template.py run this template to create the file structure.

3. create a virtual env : conda create -n cancer python=3.8 -y

4. conda activate cancer

5. Now let's write requirements to this project in the requirements.txt

6. Now write setup.py so that the pacakages can be found to the src as root and for other meta data. This will be runned when -e is triggered in the requirements.txt

7. For logging purposes we need to write in _init_.py so that we will save the running logs how they created and from what modulesor files they came from.

8. You can test this by accessing logger from cnnClassifer and try logging it.

9. Now we need utility, we will create common.py where we will write the functinalities which are frequently used.

10. pip install python-box, pip install ensure. Here python-box will make the accessing of the variables easy by dict.key. On other hand ensure annotations will make sure we the paramters are of same data type as expected.

11. 

## Workflows

1. update config.yaml
2. Update secrets.yaml [optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. Update the dvc.yaml


12. pip install gdown

