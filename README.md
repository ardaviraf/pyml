sudo docker run -it ubuntu

apt-get update

apt-get install nano unzip pkg-config gfortran libatlas-base-dev libfreetype6-dev libblas-dev liblapack-dev python3 python3-pip libhdf5-dev

pip3 install cython numpy scipy matplotlib pandas scikit-learn bidict h5py biosppy

sudo docker cp /home/pi/Desktop/v3.zip 2e78fe5c0ff3:/home
