<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [plocate](#plocate)
  - [Install Requirements](#install-requirements)
  - [Install plocate](#install-plocate)
  - [Result](#result)
  - [Usage](#usage)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->




# plocate

## Install Requirements

```sh
sudo apt install meson
# sudo apt install ninja-build
sudo apt install libzstd-dev (1.3.3+dfsg-2ubuntu1.1)
sudo apt install zstd (1.3.3+dfsg-2ubuntu1.1)
```

## Install plocate

```sh
cd plocate
meson obj
cd obj
ninja
l
./plocate
./plocate x
sudo ninja install
```

## Result

The following files will be installed:

```
plocate                                               -> /usr/local/bin/plocate
plocate-build                                         -> /usr/local/sbin/plocate-build
/home/flow/temp/plocate-1.0.5/plocate.1               -> /usr/local/share/man/man1
/home/flow/temp/plocate-1.0.5/plocate-build.8         -> /usr/local/share/man/man8
/home/flow/temp/plocate-1.0.5/obj/update-plocate.sh   -> /etc/cron.daily
```

## Usage





