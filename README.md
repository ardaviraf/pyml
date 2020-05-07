sudo docker run -it ubuntu

apt-get update

apt-get install wget nano unzip pkg-config gfortran libatlas-base-dev libfreetype6-dev libblas-dev liblapack-dev python3 python3-pip libhdf5-dev

pip3 install cython numpy scipy matplotlib pandas scikit-learn bidict h5py biosppy python-periphery

sudo docker run -it --privileged ubuntu-pi4-py-pip-ml

sudo docker cp /home/pi/Desktop/v3.zip 2e78fe5c0ff3:/home

../Train_models/myModel4/

python3 ECG_application.py s0 f1 p1 m1 RP4

wget http://anzanpour.com/ml/v9.zip

wget https://github.com/ardaviraf/pyml/raw/master/models/v6-arm-models.zip


echo "21" > /sys/class/gpio/export

echo "out" > /sys/class/gpio/gpio21/direction

gpio readall

gpio -g write 21 1

gpio -g write 21 0

echo "21" > /sys/class/gpio/unexport
