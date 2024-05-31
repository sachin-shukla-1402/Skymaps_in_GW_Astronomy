# Gravitational Wave Astronomy Sky Maps

Welcome to the repository. This repository contains all the relevant code that can be used to plot skymaps useful in Gravitational Wave(GW) Astronomy & Data Analysis. The codes presented here are intended to simplify the process of generating simple GW skymaps, and were developed as a part of my research work at IIT Gandhinagar, India.

## Installations
To run the scripts and notebooks, ensure that you have the following:

* Required Installations: Python (version > 3.10)
* Required packages: PyCBC, ligo.skymap

Install PyCBC:

    $ git clone https://github.com/gwastro/pycbc.git
    $ cd pycbc
    $ pip install -r requirements.txt
    $ pip install -r companion.txt
    $ pip install .
    
Install ligo.skymap:
    
    $ pip install --upgrade pip
    $ pip install ligo.skymap
      
## Contents

The repository contains the following main directories:

1)```basic_skymaps```: The directory contains the code to generate different types of skymaps with a single detector network for a gravitational wave event.

2)```multiple_networks_overlay```: The directory contains the code to generate different types of skymap overlay when observing the same gravitational wave event with different detector networks. With some modifications, the same code can be used to plot skymap overlays corresponding to different gravitational wave events.

## Acknowledgements

- [ligo.skymap](https://github.com/lpsinger/ligo.skymap)
