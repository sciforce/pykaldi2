# pykaldi2

PyKaldi2 is a speech toolkit that is built based on Kaldi and PyTorch. It relies on (PyKaldi) [click here](https://github.com/pykaldi/pykaldi) -- the Python wrapper of Kaldi, to access Kaldi functionalities. The key features of PyKaldi2 are one-the-fly lattice generation for lattice-based sequence training, on-the-fly data simulation and on-the-fly alignment gereation. 

##How to install

PyKaldi2 runs on top of Horovod and PyKaldi libraries. The dockerfile is provided to customarize the envriorment. To build the docker image, simply run

  ```
    docker build -t horovod-pykaldi -f docker/dockerfile 
  ```


