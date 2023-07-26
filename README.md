# go-cmake
Building Golang project with CMake

## How to build

```bash
$ git clone https://github.com/joshuadahlunr/go-cmake.git
$ cd go-cmake
$ mkdir build
$ cd build
$ cmake ../
$ sudo make install
```

**Note that in some cases the go module step will find versioning issues, CMake will identify this as failure and stop the build!** If this happens simply rerun make and the build should finish as normal!


