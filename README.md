###RL with python (virtualenv)

sudo apt-get install python-pip python-dev

export TF_BINARY_URL=https://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-0.10.0rc0-cp27-none-linux_x86_64.whl

sudo pip install –upgrade $TF_BINARY_URL

pip install –upgrade https://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-0.8.0-cp27-none-linux_x86_64.whl    

sudo apt-get install python-pip python-dev python-virtualenv

mkdir tensorflow

mkdir virtualenv

virtualenv --system-site-packages virtualenv

source ./virtualenv/bin/activate

pip install --upgrade  http://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-1.0.1-cp27-none-linux_x86_64.whl

source ./virtualenv/bin/activate

sudo apt-get install zlib1g-dev

sudo -H pip install gym

git clone https://github.com/hunkim/ReinforcementZeroToAll.git

sudo apt-get install libblas-dev liblapack-dev libatlas-base-dev gfortran

sudo pip install scipy

pip install numpy -I

xvfb-run -s "-screen 0 1920x1080x24" python 02_random_frozenkake_det.py
