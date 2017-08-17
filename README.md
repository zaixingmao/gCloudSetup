# gCloudSetup

sudo pip3 install keras
sudo apt-get install libcupti-dev
sudo apt-get install python3-pip python3-dev
pip3 install tensorflow-gpu
sudo apt-get install libcupti-dev


conda install scikit-learn
conda install pandas
conda install jupyter


conda install -c jjhelmus tensorflow-gpu=1.0.1

sudo apt-get update
sudo apt-get install bzip2
sudo apt-get install emacs
sudo bash install-cuda.sh
nvidia-smi

mkdir downloads
cd downloads
wget http://repo.continuum.io/archive/Anaconda3-4.0.0-Linux-x86_64.sh
bash Anaconda3-4.0.0-Linux-x86_64.sh
source ~/.bashrc

conda install -c conda-forge keras=2.0.2

conda install -c conda-forge matplotlib=2.0.2
conda install -c anaconda tensorflow-gpu=1.1.0
conda install -c conda-forge tensorflow=1.1.0
sudo apt-get install g++
sudo apt-get install unzip


jupyter notebook --generate-config
emacs -nw ~/.jupyter/jupyter_notebook_config.py

c = get_config()
c.NotebookApp.ip = '*'
c.NotebookApp.open_browser = False
c.NotebookApp.port = 7000


jupyter-notebook --no-browser --port=7000

sudo apt-get update && sudo apt-get install bazel
