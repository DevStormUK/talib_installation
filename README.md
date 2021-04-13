Dependences:

sudo apt-get update
sudo apt-get install build-essential
apt-get install python-dev
sudo pip install -U setuptools

Steps:

download from https://mrjbq7.github.io/ta-lib/install.html

    untar tar -xvf ta-lib-0.4.0-src.tar.gz

cd /../ta-lib

./configure --prefix=/usr

make

sudo make install

sudo apt upgrade

pip install ta-lib or pip install TA-Lib

Check import talib
