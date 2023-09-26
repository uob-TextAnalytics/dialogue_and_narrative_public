# dialogue_and_narrative_private

Repository containing the lab sheets and answers.

Use the script make_public_nb.py to make a version of the notebook without answers.

# Setup


We recommend using ```conda``` to create an environment with the correct versions of all the packages you need for these labs. You can install either Anaconda or Miniconda, which will include the ```conda``` program. 

We provide a dialogue_and_narrative.yml file in this repository, which lists all the packages you will need, and the versions that we have tested the labs with. You can use this file to create your environment as follows.

* Open a terminal. Use the command line to navigate to the directory containing this notebook and the file ```dialogue_and_narrative.yml```. You can use the command ```cd``` to change directory on the command line.
* Run the conda program by typing ```conda env create -f dialogue_and_narrative.yml```, then answer any questions that appear on the command line.
* Activate the environment by running the command ```conda activate dialogue_and_narrative```.
* Make kernel available in Jupyter: ```python -m ipykernel install --user --name=dialogue_and_narrative```.
* Relaunch Jupyter: shutdown any running instances, and then type ```jupyter lab``` into your command line.
* When you open a notebook, go to the top menu and check you are using the kernel corresponding to your dialogue_and_narrative environment: click on 'Kernel'--> 'Change kernel' --> dialogue_and_narrative.

