---
layout: post
title: STM8EF Envirment setup
---

a} OS X
1) SDCC tool chain installation (installation instructions for SDCC & stm8flash are in the [Wiki](https://github.com/TG9541/stm8ef/wiki/STM8S-Programming#problems--solutions))

```bash
brew install sdcc
```

2) stm8flash

```bash
git clone https://github.com/vdudouyt/stm8flash.git

cd stm8flash/

make

sudo make install
```

b} linux
see stm8ef wiki above
