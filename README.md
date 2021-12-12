# Microstack-on-Ubuntu-EC2-AzureVM

Setting up Microstack on AWS EC2 or Azure Virtual Machine = ubuntu

Requirements:-

ubuntu 18.04 or 20.04 LTS

RAM: more than 8GB

Storage: 30 GB

### Spin up the instance and try below commands


## Setting up basic updates on Ubuntu server

sudo apt-get update

sudo apt-get upgrade

sudo apt install xrdp 

sudo apt install ubuntu-desktop

sudo apt install snapd (must be pre-installed)

sudo apt install nginx 

sudo apt-get install openvswitch-switch-dpdk

## Run the ubuntu instance

Install openstack as explained in previuos repository

Open RDP and paste the Ipv4 address of your running instance to access ubuntu desktop

