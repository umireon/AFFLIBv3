DISTCLEANFILES = Makefile.in
EXTRA_DIST = README afflib.pxd pyaff.pxd pyaff.pyx pyaff.c setup.py

if HAVE_PYTHON
install-pyaff:
	$(PYTHON) setup.py build
	$(PYTHON) setup.py install
endif
