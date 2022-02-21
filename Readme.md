# HomeWork

the image normal with the duck triangulated mense and the death star:
![](https://github.com/ge8u/tinyraytracer/blob/main/out_normal.jpg)

the image anaglyph with the duck triangulated mense and the death star:
![](https://github.com/ge8u/tinyraytracer/blob/main/out_anaglyph.jpg)

All the boring code (image/obj files serializer etc) is already there; to obtain the above image it suffices to add 10-20 lines of code.


## compilation
```sh
git clone https://github.com/ge8u/tinyraytracer.git
cd tinyraytracer
git submodule update --init
mkdir build
cd build
cmake ..  
make
```
