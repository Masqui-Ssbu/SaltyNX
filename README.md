# SaltyNX
Background process for the Nintendo Switch for file/code modification

For libtwili: (depends on this to work)

```
git clone https://github.com/misson20000/twili-libnx.git && cd twili-libnx
make
sudo -E DESTDIR=/opt/devkitpro/portlibs/switch make install
```

Also edit your ``` twili.h``` file to include ```switch_min.h``` rather than ```switch.h```.
