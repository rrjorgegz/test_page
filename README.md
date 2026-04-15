# Sphinx

## Create project

sphinx-quickstart

## Pasos para ejecutar

make -C docs clean && make -C docs html

## Developtment

sphinx-build -b html docs/source docs/_build/html -c docs/source

sphinx-autobuild docs/source docs/_build/html -c docs/source

## Github

1 - Ve a Settings/Pages[GitHub Pages]/Branch. Select  gh-pages and /(root) , click en Save
2 - url = https://{user}.github.io/{repos}/. Ej: <https://rrjorgegz.github.io/test_page>
3 - Edit About [Page Test, Website]
