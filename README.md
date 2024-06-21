# setupp-basic

This is an ultra-basic variation of the [setupp](https://github.com/rscherrer/setupp) configuration for C++ programs using CMake. This version has no tests, not even a specialized source code directory (`src`) and may be used for toy programs. It is destined for beginner computational biologists who want a simple C++ program up-and-running fast. The pre-requisites are the same as in [setupp](https://github.com/rscherrer/setupp).

To use it, simply download this repository, change its name, change `basic` to whatever your project name is in `CMakeLists.txt`, get rid of the documentation if superfluous, and run the following (assuming Linux or MacOS but check the original repository above for how slightly different it is on Windows):

```bash
git clone https://github.com/rscherrer/setupp-basic
cd setupp-basic
mkdir build & cd build
cmake ..
cmake --build .
```

This will create a `build/` folder and locate the compiled executable in a `bin/` folder, both in the root directory of the present repository.
