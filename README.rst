cosmobib
========


a curated bibliography list for cosmology

Use in Overleaf
---------------

1. Choose `File/Add from URL`.

2. Add the following bibtex files:

- Main : https://www.dropbox.com/s/t25p3aq92ndpl8y/cosmo.bib?dl=0

- Preprints : https://www.dropbox.com/s/5m12gkht1zh48h5/cosmo_preprints.bib?dl=0

3. Add the following macros (esp if you see errors on :code:`\mnras` or :code:`\apj`):

- AAS acronyms : https://www.dropbox.com/s/e2a6yy8cvtnn5ug/aas_macros.sty?dl=0

4. Refresh the Overleaf cache of files by right-clicking on the file name ane select `Refresh`.

Example
+++++++

.. code:: latex

    \documentclass{article}

    ...
    ...
    \usepackage{aas_macros}


    ...
    \begin{document}
    ...
    ...

    \bibliographystyle{revtex}
    \bibliography{cosmo,cosmo_preprints}
    ...
    \end{document}

    ...
    ...


