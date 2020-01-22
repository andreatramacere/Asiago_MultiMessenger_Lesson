# Asiago_MultiMessenger_Lesson

git repo with notebooks: https://github.com/andreatramacere/Asiago_MultiMessenger_Lesson


## instructions

To install jetset: https://jetset.readthedocs.io/en/latest/install.html


general documentation on JetSeT https://jetset.readthedocs.io/en/latest/index.html

to run on binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/andreatramacere/Asiago_MultiMessenger_Lesson/master)


**For those having issues with Linux and the F_sync.dat file:**

	If you used binaries from ANACONDA on LINUX

		1) download this file: https://drive.google.com/file/d/12uZBCxZH1IJg5CWjvqvaONiUMT3SfdRD/view?usp=sharing
		2) uninstall jetset: conda uninstall jetset
		3) conda install  --yes --offline jetset-1.1.1-0.tar.bz2
		4) python -c 'from jetset.tests import test_functions; test_functions.test_short()'

	If you installed from source on LINUX:
	
		1) download https://github.com/andreatramacere/jetset/archive/testubuntu.tar.gz
		2) untar
		3) cd jetset-testubuntu
		4) python setup.py clean
		5) python setup.py install
		6) cd ..
		7) python -c 'from jetset.tests import test_functions; test_functions.test_short()'
	

