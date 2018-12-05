# netboot
iPXE based network boot environment from my home lab

# Using
```
git pull
git submodule update --rebase --recursive
make world
make install PREFIX=/srv/netboot/

cd /srv/netboot
./bin/start.sh
```

# Future
This should be a jailfs example and will be in the future.

This repo will be pulled into the jailfs tree under example/netboot/ at some future time...
