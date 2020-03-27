# Ubuntu Setup
Script and files to rapidly customize a fresh install of ubuntu (16.04 so far) the way I like it. 

To use it all you need to do is run from terminal the following:
```
sudo apt update
sudo apt install git -y
git clone https://github.com/m-tartari/ubuntu_setup.git
./ubuntu_setup/ubuntu_setup.sh
```

If it fails to start you might need to make it executable the run it again:
```
chmod +x ./ubuntu_setup/ubuntu_setup.sh
./ubuntu_setup/ubuntu_setup.sh
```