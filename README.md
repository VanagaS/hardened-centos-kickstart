# hardened-centos-kickstart
Independent customizable files to target a hardened CentOS installation that consider fine control over repositories, accounts, partitions and follow secure guidelines from SCAP Security Guide (SSG). It also includes tools like Google two factor authentication, RKHunter, Maldet, ClamAV etc.,. that are configured by default.

The influence for this project and majority of code relevant to SSG guidelines is from Frank Caviggia's hardened-centos7-kickstart project located at https://github.com/fcaviggia/hardened-centos7-kickstart

# Description

Each server in a network needs different tools and settings. This project enables to automate a kickstart configuration per server (based on the requirements) with minimal changes to required files while keeping majority of security guidelines and hardening is place. 

With the help of a PXE server, and little changes to the files in this project, each server can be automatically setup with desired configuration.
