Practice 1

- Install numpy, pandas and jupyter notebook in a virtual environment. Remember you should have `python3-venv` and `python3-pip` installed. 

    - In order to do this, go to a folder where you want your virtual environment directory to be, and run the following command

            python3 -m venv name_of_your_virtual_environment
    - Once you have created your virtual environment, enter the environment

            source name_of_your_virtual_environment/bin/activate

        You will see something in your terminal that will tell you when the virtual environment is activated.

    - Update the pip version within the environment. Remember that, once you have activated your environment, every pip command you execute will modify **just the environment**, not your local installation.

            pip install --upgrade pip

    - Install the libraries

            pip install pandas numpy jupyter notebook

- Clone this repository

        git clone git@github.com:uzmargomez/practice_lessons.git

    This repo is public, so it won't matter if you do not have set up your ssh key, but you should have done it by this point.

- Open a Jupyter notebook instance, look for the notebook inside the directory `practice_lessons/practice_1/practice.ipynb`, and open it. To execute the Jupyter notebook instance, just run the following code  in your terminal, copy the web link (it starts with "http://localhost...") and paste it in a browser.

        jupyter notebook