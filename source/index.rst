.. Computational Software documentation master file, created by
   sphinx-quickstart on Tue Mar 31 12:45:28 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.
.. figure:: img/CompSoft_banner.png

Welcome to the Introduction to Computer-based Physical Modeling Course!
========================================================================

The Python programming language is useful for all kinds of scientific and engineering tasks. You can use it to analyze and plot data. You can also use it to numerically solve scientific problems that are difficult or even impossible to solve analytically. Python is freely available and has been, due to its modular structure, extended with a nearly infinite number of different purpose modules.

This course intends to introduce you into the programming with Python. It is aimed more to the beginner but we hope that more advanced users find it interesting as well.
We will start the course with and introduction to the Jupyter Notebook environment, which we will be using throughout the course. Starting from there we will provide some introduction into Python and then show you some basic functionalities, like plotting and analyzing data by curve fitting, reading and writing of files which are some of the tasks you will encounter during your physics studies. We will also show you some more advanced topics of animating inside Jupyter and simulating physical processes in

* mechanics
* electrostatics
* waves
* quantum mechanics
* optics

At the end of the course we will also add some basic introduction into **machine learning** which is now becoming an important tool even in physics.

We will not present a comprehensive list of numerical simulation schemes, but use the examples to stimulate your curiosity. As there are slight differences in the syntax of different Python versions, we will in the following always refer to **Python 3** standards.


.. raw:: html

    <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; height: auto;">
        <iframe src="https://www.youtube.com/embed/lSIwZFeRpfQ" frameborder="0" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe>
    </div>

|
|

.. toctree::
   :maxdepth: 2
   :caption: Course Information:

   course-info/website.rst
   course-info/schedule.rst
   course-info/assignments.rst
   course-info/exam.rst
   course-info/resources.rst
   course-info/instructor.rst

.. toctree::
   :maxdepth: 2
   :caption: Jupyter Notebooks:

   lectures/Intro/overview.rst
   notebooks/Intro/1_Introduction2Jupyter.ipynb
   notebooks/Intro/2_NotebookEditor.ipynb
   notebooks/Intro/3_EditCells.ipynb


.. toctree::
   :maxdepth: 2
   :caption: Example Lecture 1:

   lectures/L4/overview_4.rst
   notebooks/L4/1_classes.ipynb
   notebooks/L4/2_brownian_motion.ipynb   
   notebooks/L4/3_animations.ipynb  
   lectures/L4/assignment_4.rst

   
.. toctree::
   :maxdepth: 2
   :caption: Example Lecture 2:

   lectures/L10/overview_10.rst
   notebooks/L10/1_quantum_mechanics.ipynb
   notebooks/L10/2_particle_in_a_box.ipynb
   notebooks/L10/3_harmonic_oscillator.ipynb
   notebooks/L10/4_periodic_potential.ipynb
   
   
Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
