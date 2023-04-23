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
sudo apt-get build-dep python-pygame

2. Install mercurial to use hg 
sudo apt-get install mercurial 

Windows user can use the mercurial installer, which can be found at 
https://wiki.mercurial-scm.org/Download 

3. Use pip to install Pygame 
pip install hg+http://bitbucket.org/pygame/pygame 
If the above command gives freetype-config: not found error then
try: sudo apt-get install libfreetype6-dev and repeat step 3. 


