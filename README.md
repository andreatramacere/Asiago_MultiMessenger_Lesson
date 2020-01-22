# Asiago_MultiMessenger_Lesson

## git repo with notebooks 

- to get the notebooks:
  `git clone https://github.com/andreatramacere/Asiago_MultiMessenger_Lesson`

OR if you don't have git installed on your machine

- download visiting https://github.com/andreatramacere/Asiago_MultiMessenger_Lesson

## instructions To install the code

- be sure to have jupyter-notebook, matplotlib and ipython installed on your machine, and in the same environment where you install jetset.
  
- to install jetset: visit https://jetset.readthedocs.io/en/latest/install.html

- general documentation on JetSeT https://jetset.readthedocs.io/en/latest/index.html

#

**ONLY For those not being able to install, in particular WINDOWS users, use binder**

 you can run all the notebooks on a remote server just press the link below (no need to download notebooks in this case)

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/andreatramacere/Asiago_MultiMessenger_Lesson/master)

#

**ONLY For those having issues with Linux and the F_sync.dat file:**

	If you used binaries from ANACONDA on LINUX:  

		1) download this file: https://drive.google.com/file/d/1ZRnq9TLUM4tdWLTl7xNqAl56Hv20m6cA/view?usp=sharing
		3) untar
		4) cd jetset-patch
		2) uninstall jetset: conda uninstall jetset
		4) conda install --file requirements.txt (or conda install -c astropy --file requirements.txt)
		3) conda install  --yes --offline jetset-1.1.1-0.tar.bz2
		4) python -c 'from jetset.tests import test_functions; test_functions.test_short()'

	If you installed from source on LINUX:
	
		1) download https://github.com/andreatramacere/jetset/archive/testubuntu.tar.gz
		2) untar
		3) cd jetset-testubuntu
		4) conda install --file requirements.txt
		5) python setup.py clean
		5) python setup.py install
		6) cd ..
		7) python -c 'from jetset.tests import test_functions; test_functions.test_short()'
	

