# 第三方库

```bash
sudo apt install liblcms2-dev
sudo apt install libtiff-dev
sudo apt install libgsl-dev
sudo apt install libvigraimpex-dev
sudo apt install libboost-dev
```

# 编译

```bash
cd enblend
#  make --makefile=Makefile.scm
mkdir build && cd build && cmake .. && make -j4
```
