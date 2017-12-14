# Using the LSST DM Stack from Python - Firefly edition

The Jupyter Notebook in this repository is a self-guided tutorial that walks the reader through writing a simple processing script using LSST Data Management Python libraries. This tutorial was originally set up for the LSST2017 Project
and Community Workshop.

The `tutorial-firefly.ipynb` notebook is a modified form of the notebook that gives Firefly equivalents to the
matplotlib displays used in the original version. This notebook is based on the "answers" version of the tutorial,
in which the solutions to the exercises have been included.

As of mid-December 2017, the necessary Firefly packages are included in `lsst_distrib`. It is possible to
run the notebook in a Docker container, following the 
[developer instructions for Docker](https://pipelines.lsst.io/install/docker.html#docker-tags).

Here are Docker commands used to test this notebook:

```
docker run -itd -p 9745:9745 -v `pwd`:/home/vagrant/mnt --name lsst2 lsstsqre/centos:7-stack-lsst_distrib-d_2017_12_14

docker exec -it lsst2 /bin/bash
```

Then in the shell inside the container:
```
source loadLSST.bash

conda  install jupyter notebook ipython

cd /home/vagrant/mnt/lsst2017

jupyter notebook --ip 0.0.0.0 --port 9745
```

Then on the host machine, open a browser to [http://localhost:9745](http://localhost:9745).
