# Meg
on-demand ephemeral OpenVPN server deployment tool using Docker.

##What is it and why does it exist?

Meg is a tool for deploying ephemeral OpenVPN server nodes automatically to your own infrastructure or your favorite cloud provider(s). Meg grew out of the need to defend against the detection and subsquent blocking of OpenVPN servers, usually by governments which monitor and restrict the use of the Internet. While Meg does not explicitly prevent the detection of VPN use, it permits the user to shut down an old node and spin a new one on a fresh IP rapidly. 

##Requirements
+ A VPS with [Docker](https://docs.docker.com/installation/#installation) and [Docker-compose](https://docs.docker.com/compose/install/) installed. 
+ A built and configured OpenVPN Docker Container such as: [kylemanna/openvpn](https://registry.hub.docker.com/u/kylemanna/openvpn/)

##Getting Started

