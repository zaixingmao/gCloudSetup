# gCloudSetup

####install basics
```bash
sudo apt-get update
sudo apt-get install bzip2
sudo apt-get install emacs
```
####install CUDA
```bash
sudo bash install-cuda.sh
# Check CUDA
nvidia-smi
```

####install Machine Learning related
```bash
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
```

####update jupyter configs for remote access
```bash
jupyter notebook --generate-config
emacs -nw ~/.jupyter/jupyter_notebook_config.py
```

#c = get_config()
#c.NotebookApp.ip = '*'
#c.NotebookApp.open_browser = False
#c.NotebookApp.port = 7000

####run jupyter
```bash
jupyter-notebook --no-browser --port=7000
```