# 2020-06-08-uproot-awkward-columnar-hats

Tutorials for Uproot Awkward Columnar HATS, a hands-on tutorial hosted by the [Fermilab LPC](https://lpc.fnal.gov) on June 8, 2020 from 2 to 5pm U.S. Central.

See the [event page for videoconferencing details](https://indico.cern.ch/event/917675).

## How to participate

Run the JupyterLab code with us, altering examples and asking "what if" questions along the way.

The preferred way to run these notebooks is through a public cloud service called Binder:

<p align="center">
  <a href="https://mybinder.org/v2/gh/jpivarski/2020-06-08-uproot-awkward-columnar-hats/1.2?urlpath=lab">
    <img src="https://mybinder.org/badge_logo.svg" alt="Launch Binder" height="40">
  </a>
</p>

Navigate in the JupyterLab file view (left sidebar) to the desired lesson. Note that Binder cannot save data permanently (reloading your web browser will take you to a new instance), and it may take up to a minute to start up.

## Running everything on your own computer

This course will not cover installation of the software, but everything can be installed with pip or conda, standard mechanisms for installing Python packages. See [requirements.txt](requirements.txt) for a list of pip package names.

Note that [uproot4](https://github.com/scikit-hep/uproot4) is extremely provisional and its interfaces will likely change. Use [version 0.0.8](https://github.com/scikit-hep/uproot4/releases/tag/0.0.8) for compatibility with these notebooks, but a newer version for real work.

## Browsing the material online

The cells of the JupyterLab notebooks are deliberately unevaluated—we will discover their output during the tutorial. However, if you're coming here after the event and want to look up how we did something, see the [evaluated](evaluated) directory for evaluated versions of both notebooks.

## Uprooting hats that are awkwardly columnar

<p align="center"><img src="img/blog1841_TheBuriedGnome800.jpg" width="400"></p>

[(Used with permission.)](https://bagelhot.blogspot.com/2007/02/web-daze.html)
