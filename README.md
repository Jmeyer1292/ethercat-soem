## ethercat-soem

This package provides an EtherCAT Master implementation using a `catkinized` version of the [OpenEtherCAT Society's Master Library](https://github.com/OpenEtherCATsociety/SOEM) v1.30.

This library was forked from [Kelsey Hawkins' initial implementation](https://github.com/gt-ros-pkg/ethercat-soem).

## Notes

This library makes use of Linux raw sockets. On Ubuntu this likely means you will need to set certain permissions on any executable built using this library:  

```sudo setcap cap_net_raw+ep <binary>```