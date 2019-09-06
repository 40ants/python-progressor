===============================
 Python Progressor's Changelog
===============================

0.2.0 (2019-09-06)
==================

* Function ``progressor.p`` now accepts optional parameter ``id``.
  Use it to set a custom progress bar's id. This can be useful when
  starting many progresses in parallel threads, because by default
  ``id`` is generated as unix timestamp and progresses created in
  same second will conflict with each other.
