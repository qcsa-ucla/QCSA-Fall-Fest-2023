# QCSA Workshop/Tutorial Preparation
If you’d like to follow along with our workshops, particularly those that follow a Jupyter notebook, we suggest getting things set up ahead of time so that you can learn to write and run code during the workshop or follow along with a tutorial. These steps should get you started relatively quickly.

## Steps to Prepare
1. **Install Anaconda:** The simplest way to get Python on your computer and be able to run a Jupyter notebook right away is using [Anaconda](https://www.anaconda.com/products/distribution), which is free. Installation instructions are on their website, and some basics on using Jupyter notebooks can be found [here](https://docs.anaconda.com/ae-notebooks/user-guide/basic-tasks/apps/jupyter/index.html).
2. **Import the notebook:** The notebook we’ll be using for the workshop should have been sent out with the workshop announcement. Just click on the Jupyter notebook icon, which is probably under an Anaconda folder on your desktop or wherever applications are stored. This should open Jupyter in your browser, and use the upload button in the upper right hand corner of the page to upload the notebook.
3. **Install packages:** If you’re using Anaconda, click on the Anaconda prompt icon, again in the Anaconda folder. Type into the prompt ‘conda install’ then the package name. If that doesn’t work, try ‘pip install’ then the package name instead. Do each package separately. Below are the necessary packages for each of our workshops/tutorials:
    - **Intro to Quantum Computing:** numpy, matplotlib, qutip, scipy, and qiskit
    - **Intro to Qiskit:** qiskit, numpy, and matplotlib
    - **Intro to Qutip:** numpy, matplotlib, qutip
4. **Make necessary accounts:** Some of our workshops will require accounts with various companies, particularly to run circuits on real machines. Below are instructions for each workshop where you’ll need to set something else up.
    - **Intro to Qiskit:** If you’d like to run circuits on hardware or different simulators, make a free account with IBM here. They might ask for a credit card and make a temporary $1 transaction, but note that the machines we’ll be using are completely free, so this should be reversed. You should see an option to copy an API token, so do that and paste it into the cell that asks for the API token, near the end of the workshop notebook.
5. **Test imports:** We suggest trying to run the imports cell at the top of the notebook, just in case something went wrong. Run the cell by clicking on it and using the shift and enter keys. If you get an error message, do your best to troubleshoot with Google. If it does run with no errors, you should be all set!

All of our workshops are run using code written in Python. If you’re not familiar with programming or with Python, we suggest taking a few hours and following some basic online tutorials, just to get an idea of the basics and learn how to step through and follow a block of code.