This fork exists simply to make sure that the original never gets taken down.

***Works on macOS 10.12 Sierra***

This is the macOS binary for the stable release gcc-6.3.0, this file is provided for your convenience, if you prefer to compile yourself gcc-6.3.0 visit the tutorial webpage for build instructions:

[https://solarianprogrammer.com/2016/09/22/compiling-gcc-6-macos/](https://solarianprogrammer.com/2016/09/22/compiling-gcc-6-macos/)

**Clone (download) the archive on your machine with:**

git clone https://github.com/sol-prog/gcc-osx-binary

In order to install this binary extract gcc-6.3.0.zip and copy the extracted folder (gcc-6.3.0) in your /usr/local folder.

Using the new compilers (gcc-6.3.0, g++-6.3.0 and gfortran-6.3.0) require that you modify your path, paste the next line in a Terminal session:

export PATH=/usr/local/gcc-6.3.0/bin:$PATH

The above will modify temporarily your path (closing the Terminal will revert to the default path). If you want to add this permanently to your path add the above line in the .bash_profile file from your Home.

Compiling a C++14 code is as simple as:

g++-6.3.0 file_name.cpp -o file_name:

If you need more help leave me a comment at:

[https://solarianprogrammer.com/2016/09/22/compiling-gcc-6-macos/](https://solarianprogrammer.com/2016/09/22/compiling-gcc-6-macos/)
