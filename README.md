# OReillyAI-Gamebots

This is the Git repo with the code and slides from the O'Reilly AI Conference NY for the sessions "Building Game bots using OpenAI's gym and Universe".

# Dependencies

* Python 2.7 or 3.5
* [Golang](https://golang.org/doc/install)
* [six](https://pypi.python.org/pypi/six) (for py2/3 compatibility)
* [TensorFlow](https://www.tensorflow.org/)
* [tmux](https://tmux.github.io/) (the start script opens up a tmux session with multiple windows)
* [htop](https://hisham.hm/htop/) (shown in one of the tmux windows)
* [gym](https://pypi.python.org/pypi/gym)
* atari-py
* libjpeg-turbo (`brew install libjpeg-turbo`)
* [universe](https://pypi.python.org/pypi/universe)
* [opencv-python](https://pypi.python.org/pypi/opencv-python)
* [numpy](https://pypi.python.org/pypi/numpy)
* [scipy](https://pypi.python.org/pypi/scipy)

# Getting Started

The following are required for the universe-starter-agent demo.

```
conda create --name universe-starter-agent python=2.7
source activate universe-starter-agent

brew install tmux htop cmake golang libjpeg-turbo      # On Linux use sudo apt-get install -y tmux htop cmake golang libjpeg-dev

pip install "gym[atari]"
pip install universe
pip install six
pip install tensorflow
conda install -y -c https://conda.binstar.org/menpo opencv3
conda install -y numpy
conda install -y scipy
```

# Other Approaches

* [NEAT](https://github.com/HackerHouseYT/OpenAI-NEAT)
* [EWC](https://deepmind.com/blog/enabling-continual-learning-in-neural-networks/)
