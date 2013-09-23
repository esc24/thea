SOURCES=about_dialog_layout.ui source_code_dialog_layout.ui colorbar_dialog_layout.ui main_window_layout.ui
PY_SOURCES=$(SOURCES:.ui=.py)
.SUFFIXES: .ui .py

all: $(PY_SOURCES)

.ui.py:
	pyside-uic $< > $@

clean: 
	rm -f $(PY_SOURCES) $(PY_SOURCES:.py=.pyc)
