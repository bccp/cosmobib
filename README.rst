cosmobib
========


a curated bibliography list for cosmology

Use in Overleaf
---------------

1. Choose `File/Add from URL`.

2. Add the following bibtex files:

- Main : https://raw.githubusercontent.com/bccp/cosmobib/master/cosmo.bib

- Preprints : https://raw.githubusercontent.com/bccp/cosmobib/master/cosmo_preprints.bib

3. Add the following macros (esp if you see errors on `\mnras` or `apj`):

- AAS acronyms : https://raw.githubusercontent.com/bccp/cosmobib/master/aas_macros.sty

Example latex script

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
