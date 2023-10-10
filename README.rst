Control Course with Python
=======

.. image:: assets/logo.png

How to Run the Notebooks on Google Colab
========

Step 1: Open Google Colab
Open Google Colab in your web browser by navigating to https://colab.research.google.com/. 
If you are not signed in to your Google account, you will be prompted to do so.

Step 2: Create a New Notebook 
In the Colab interface, click on the “New Notebook” button to create a new notebook. This will open a new notebook in a new tab.

Step 3: Mount Google Drive

To access the Github repository from Colab, you need to mount your Google Drive. 
To do this, run the following code snippet in the first cell of your notebook:

from google.colab import drive
drive.mount('/content/drive')

This will prompt you to give Colab permission to access your Google Drive. Follow the instructions to grant permission.

Step 4: Clone the Github Repository
With your Google Drive mounted, you can now clone the Github repository that contains the notebook you want to run. 
To do this, run the following code snippet in the next cell of your notebook:

!git clone https://github.com/Spogis/Control_Course.git

Step 5: Navigate to the Notebook
After cloning the repository, you need to navigate to the notebook you want to run. 
To do this, use the cd command to change to the directory where the Notebooks are located. 

%cd Control_Course/Notebooks

Step 6: Run the Notebook
With the notebook directory selected, you can now run the notebook in Colab. To do this, simply click on the notebook file in the file explorer on the left-hand side of the Colab interface. 
This will open the notebook in a new tab, where you can run the notebook cells as you would in a local Jupyter notebook.


Additionally, you can refer to examples in the `respective folder <Notebooks/>`_.


License
=======

This software is licensed under Apache license 2.0. See `LICENSE <LICENSE>`_.


How to cite in your publications
========================================

If you find my Control Notebooks to be useful, please consider citing it in your published work:

.. code-block:: python

    @misc{Control_Course,
      author = {Nicolas Spogis},
      title = {Control Course in Python},
      subtitle = {A Control Course in Python},
      note = "https://github.com/Spogis/Control_Course",
      year = {2023},
    }


Publications
============


References
==========



