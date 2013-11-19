--- 
layout: default
title: Documentation
---

**Spike API** [doxygen](spikegpu.github.io/docs/index.html)

**Building examples**

The [SpikeLibrary](https://github.com/spikegpu/SpikeLibrary) uses CMake to build the example executables found under `examples`. You must have a recent version of [CMake](http://www.cmake.org/) and [Nvidia's CUDA](http://www.nvidia.com/cuda) installed in order to build.

First, grab the source code from the Git repositories:
<pre>git clone git@github.com:spikegpu/SpikeLibrary.git</pre>

<br />

Next, create a build directory and cd into it:
<pre>mkdir SpikeLibrary/build
cd SpikeLibrary/build</pre>

<br />

Open CMake, select the source (`examples`) and build (`build`) directories, and configure the build. If all goes well, CMake should automatically find CUDA and configure the build. If no warnings are shown, go ahead and generate the build files.

Go to the build directory and run `make`. If successful, you should now have a few example executables. See the README file in the source directory for more information on how to run.
