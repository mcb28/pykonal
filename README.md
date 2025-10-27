# Pykonal for Reconal
This repository is forked from https://github.com/malcolmw/pykonal, with fixes implemented for accurate refracted map generation using the [Reconal](https://github.com/philippwindischhofer/Reconal/tree/big_rays) travel-time calculator. Specifically, a version of the solver which only uses first-order finite differences is included to avoid edge effects from the existing second-order solver.

## Installation
```
git clone https://github.com/mcb28/pykonal.git
cd pykonal
pip install .
```