This repository contains an easy-to-read Python implementation of the seamless image cloning method in the paper <a href='http://www.cs.jhu.edu/~misha/Fall07/Papers/Perez03.pdf'>Poisson Image Editing</a>. To solve the sparse least-squares problem arising in this method, I provide an implementation that uses the default scipy.sparse solver, as well as an implementation that uses a hand-written geometric Jacobi solver.

This code can be browsed online with the <a href='http://nbviewer.ipython.org/'>IPython Notebook Viewer</a> using the links below.

- <a href='http://nbviewer.ipython.org/urls/raw.github.com/mroberts3000/PoissonImageEditing/master/IPython/SeamlessImageCloningAlgebraic.ipynb'>default scipy.sparse solver</a>
- <a href='http://nbviewer.ipython.org/urls/raw.github.com/mroberts3000/PoissonImageEditing/master/IPython/SeamlessImageCloningGeometric.ipynb'>hand-written geometric Jacobi solver</a>
