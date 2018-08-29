# Jupyter

## 使用 apt-get 安裝
sudo apt-get install build-essential gfortran libatlas-base-dev python-pip python-dev
sudo apt install python3-numpy python3-scipy python3-matplotlib python3-opencv python3-pip


## 使用 python pip 安裝
apt-get install -y python3-pip
sudo python3 -m pip install --upgrade pip
sudo python3 -m pip install jupyter

sudo python3 -m pip install numpy
sudo python3 -m pip install matplotlib
sudo python3 -m pip install pandas
sudo python3 -m pip install scipy
sudo python3 -m pip install scikit-learn


## jupyter使用範例
jupyter --version
4.4.0

jupyter notebook --generate-config
jupyter notebook list
jupyter notebook --ip 192.168.123.158 --port 8888 --pylab
