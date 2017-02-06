# cosmobib
a curated bibliography list for cosmology

## Overleaf

Choose add file from URL:

- Main : `https://raw.githubusercontent.com/bccp/cosmobib/master/cosmo.bib`

- Preprints : `https://raw.githubusercontent.com/bccp/cosmobib/master/cosmo_preprints.bib`

Useful Latex macros (If you see errors on `\mnras` or `apj`):

- AAS acronyms : `https://raw.githubusercontent.com/bccp/cosmobib/master/aas_macros.sty`

```
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
```
