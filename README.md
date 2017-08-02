IPython notebooks for master thesis student to get their master thesis started

Installing and opening Jupyter Notebook using Anaconda on Windows
=================================================================

1. Download Anaconda for Windows from https://www.continuum.io/downloads. This may take a
   few minutes. Pay attention to the following:

   - Python version: select the latest Python version (>= 3.6).

   - CPU architecture (32-bit or 64-bit). You can check your CPU architecture by going to `Configuration Panel` > `System and Security` > `System`.

2. Install the version of Anaconda that you downloaded, following the instructions on the
   download page. If you already have a version of Python on your computer, untick the box
   stating “Register Anaconda as my default Python x.x”.

3. Congratulations, you have installed Anaconda and, with it, Jupyter Notebook. To start
   the program, navigate to the folder containing the provided notebooks, open a terminal
   window, and simply type `jupyter notebook`. Alternatively, you can also open the program
   Anaconda Navigator, select jupyter notebook, and navigate to the folder to the location
   where the notebooks are stored. Click on the first notebook to get started.


Installing and opening Jupyter Notebook using Anaconda on Linux
===============================================================

1. Download Anaconda for Linux from https://www.continuum.io/downloads. This may take a
   few minutes. Pay attention to the following:

    - Python version: select the latest Python version (>= 3.6).

    - CPU architecture (32-bit or 64-bit). Open a terminal window and type `uname -i`.
      This will give as output `Intel 80386` or `i386` for a 32-bit system, and `x86_64`
      for a 64-bit system. Do not download the Power8 variant.

2. Install the version of Anaconda that you downloaded by running: `bash Anaconda3-4.4.0-Linux-x86_64.sh`. (The filename may be different if you have downloaded a newer version.) Follow the
   instructions that appear on screen. When asked to updated `.bashrc`, type `yes`. When
   you're done, open a new terminal window for the new settings to take effect.

3. Congratulations, you have installed Anaconda and, with it, Jupyter Notebook. Now run `jupyter notebook`. A browser window should open. Click on the first notebook to get started.


Installing and opening Jupyter Notebook using Anaconda on macOS
===============================================================

1. Download Anaconda for macOS from https://www.continuum.io/downloads. This may take a
   few minutes. Pay attention to the following:

    - Python version: select the latest Python version (>= 3.6)

    - CPU architecture (32-bit or 64-bit). You can check your CPU architecture by going to `System Profiler` > `Contents` > `Software`. The line `64-bit Kernel and Extensions` will say `Yes` if you are running the 64-bit kernel and `No` if you are running the 32-bit kernel. Note that `System Profiler` was renamed to `System Information` in OS X 10.7.

2. Install the version of Anaconda that you downloaded, following the instructions on the
   download page. If you already have a version of Python on your computer, untick the box
   stating “Register Anaconda as my default Python x.x”.

3. Congratulations, you have installed Anaconda and, with it, Jupyter Notebook. To start
   the program, navigate to the folder containing the provided notebooks, open a terminal
   window, and simply type `jupyter notebook`. Alternatively, you can also open the program
   Anaconda Navigator, select jupyter notebook, and navigate to the folder to the location
   where the notebooks are stored. Click on the first notebook to get started.


TODO
====

- Add link to download notebooks to point 3. Once this repository (or part of it) is public, github provides a download URL.