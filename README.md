- install dependent packages

  ```
  pacman -Sy fakeroot binutils python-six autoconf automake libtool make gcc elfutils nss cpio python-setuptools xmlto python2-setuptools numactl
  ```
- build and install systemtap package

  ```
  cd systemtap
  makepkg
  pacman -U systemtap-4.7-1-x86_64.pkg.tar.zst 
  ```
- build openvswitch

  ```
  cd ovs
  makepkg
  ```
