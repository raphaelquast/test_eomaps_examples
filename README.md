# test_eomaps_examples
A binder container to get a quick look at the capabilities of EOmaps.

NOTE: this is just a test-repo that is subject to change!

Jupyter-Notebook integration is still in an early stage and there are some issues
that are not yet resolved (see below).


- https://mybinder.org/v2/gh/raphaelquast/test_eomaps_examples/HEAD


### ❗ things that do NOT work nicely at the moment
Blitting is still only partially supported by the `ipympl` backend, which results
in some problems for some features.

-❌ callbacks that draw on mouse-movement
  - the functionalities work, but there's an annoying lag with `ipympl`

-❌ callbacks that would open popup-windows (or additional plots not created as a `MapsGrid`)
