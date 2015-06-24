============
Contributing
============

The `documentation <https://github.com/milieudefensie/vmd.documentation>`_ is hosted in a private repository on Github, just clone it and follow the `README <https://github.com/milieudefensie/vmd.documentation/blob/master/README.rst>`_ to start hacking.

Make sure that you have all dependencies installed.

::

	apt install build-essential python2.7-dev python-virtualenv


For above command apt.v2 is used, if you still prefer the old apt use *apt-get* instead of *apt*.

::

	git clone git@github.com:milieudefensie/vmd.documentation
	cd documentation.vmd
	virtualenv --python=python2.7 .
	source bin/activate
	pip install -r requirements.txt

All the documentation is located in the */source* directory.


