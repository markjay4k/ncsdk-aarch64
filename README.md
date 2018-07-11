# Intel® Movidius™ Neural Compute SDK
## Modified to install on rock64 (aarch64 with ubuntu 18.04)

### This README is a modified version of the original NCSDK repo

This Intel® Movidius™ Neural Compute software developer kit (NCSDK) is provided for users of the [Intel® Movidius™ Neural Compute Stick](https://developer.movidius.com/) (Intel® Movidius™ NCS). It includes software tools, an API, and examples, so developers can create software that takes advantage of the accelerated neural network capability provided by the Intel Movidius NCS hardware.

-------

# Installation
The provided Makefile helps with installation. Clone this repository and then run the following command to install the NCSDK:

```bash
git clone https://github.com/markjay4k/ncsdk-aarch64.git
cd ncsdk-aarch64
sudo make install
source ~/.bashrc
sudo make api
```
## Install Tensorflow (optional)
```bash
git clone https://github.com/markjay4k/Tensorflow-1.9rc0-py36-aarch64.git
pip3 install Tensorflow-1.9rc0-py36-aarch64/tensorflow-1.9.0rc0-cp36-cp36m-linux_aarch64.whl
```

# Examples
The Neural Compute SDK also includes examples. Plug the NCS in and run the following command to install the examples:
```
sudo make examples
```

## NCAPPZOO Examples
For additional examples, please see the Neural Compute App Zoo available at [http://www.github.com/movidius/ncappzoo](http://www.github.com/movidius/ncappzoo). The ncappzoo is a valuable resource for NCS users and includes community developed applications and neural networks for the NCS.

# Documentation
The complete Intel Movidius Neural Compute SDK documentation can be viewed at [https://movidius.github.io/ncsdk/](https://movidius.github.io/ncsdk/)

# Getting Started Video
For installation and general instructions to get started with the NCSDK, take a look at this [video](https://www.youtube.com/watch?v=fESFVNcQVVA)

# Troubleshooting and Tech Support
Be sure to check the [NCS Troubleshooting Guide](https://ncsforum.movidius.com/discussion/370/intel-ncs-troubleshooting-help-and-guidelines#latest) if you run into any issues with the NCS or NCSDK.

Also for general tech support issues the [NCS User Forum](https://developer.movidius.com/forums) is recommended and contains community discussions on many issues and resolutions.
