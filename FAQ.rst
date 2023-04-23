.. image:: https://cdn.pixabay.com/photo/2017/01/31/23/00/faq-2027970_960_720.png
  :alt: FAQ 
  :target: https://www.pygame.org/ 


Frequently Asked Questions and Answers 
=======================================

Summary 
-------
The purpose of this document is to provide answers to the most frequently
asked questions of new users and contributors in Pygame. 

What is the license of Pygame?
------------------------------
Pygame is published under the GNU LESSER GENERAL PUBLIC LICENSE version2.1
which among others allows for the free and open distribution of the source
code and protects contributors from any liability if their code is being
used for another project. For more information visit the license page 
in the repository in the following link:
https://github.com/DeanDro/pygame_contr/blob/main/docs/LGPL.txt 


What if I am unable to install Pygame using pip?
------------------------------------------------
If you are running on Linux the easiest way to install Pygame using pip is
1. Install build dependencies:

``sudo apt-get build-dep python-pygame``

2. Install mercurial to use hg 

``sudo apt-get install mercurial``

Windows user can use the mercurial installer, which can be found at 
https://wiki.mercurial-scm.org/Download 

3. Use pip to install Pygame 

``pip install hg+http://bitbucket.org/pygame/pygame``

If the above command gives freetype-config: not found error then
try: sudo apt-get install libfreetype6-dev and repeat step 3. 


What is the easiest way of installing Pygame on Ubuntu?
--------------------------------------------------------------------
The easiest way of installing Pygame on Ubuntu is through apt. Specifically,
run the command ``sudo apt-get install python-pygame``. 

``pip`` is better for pure python dependencies or if you are using it 
in virtual environment. 


Where can I find tutorials for Pygame?
--------------------------------------
There are plenty of tutorials available in this repository that are also
available on the website version of Pygame. The links to these locations
are: https://github.com/DeanDro/pygame_contr/tree/main/docs/reST/tut 
and https://www.pygame.org/docs/  


How to create a virtual environment and install Pygame?
--------------------------------------------------------
The easiest way of using Pygame locally is by installing it within a virtual
environment.

If you work on Windows this is a simple process following these steps: 
1. Open ``Command Prompt`` and navigate in the folder you want to store your
project. 

2. Within the folder give the following command: 

``python -m venv <name_of_environment>``

3. Now you have created the virtal environment, but you need to move into
it. Give the command: ``cd <name_of_environmnt>``. 

Once you are inside the environment type: ``pip install pygame`` 

This will download pygame and install it in your environment for use. 

Optional 
~~~~~~~~~
It is common that our virtual environment is outdated using older versions
of the dependencies. To ensure that everything is up-to-date run the command
``venv --upgrade-deps`` 
This wll update pip and the setup tools to the latest version of PyPI. 
