# Receiver Functions - Probing Crust and Mantle with Earthquake Records
Receiver Functions are one way to get an idea of some of the properties in the Solid Earth. Essentially, they exploit the fact that an elastic wave crossing an impedance contrast (i.e., a boundary at which the seismic velocity and/or the material's mass density changes) is refracted. For example, a pressure/P-wave produces not only a refracted P but also S-wave(s).

In practice, we can use receiver functions to infer depth and position of **discrete boundaries** of **elastic** material properties. They work well for sudden strong changes in velocity and density. They are not very informative for smooth transitions, for which seismologists tend to use so-called tomographies. Changes in material properties that do not have any influence on mass density or the wave's velocity/phase speed will not be visible
## Before the Practical: Installation and preparation
To make this practical go as smooth as possible, please install some programs and download the sample data before coming to the lecture.

Here is the list of resources:

1. Download the installation files from GitHub: 
1. Install miniforge or anaconda: you can find the instructions on how to install minforge for your operating system here: [https://conda-forge.org/download/](https://conda-forge.org/download/). We use this environment to easily install and remove python packages and manage installations.
2. Open a terminal (on Windows: search for ``cmd`` and execute; on Linux/Mac: open ``terminal``). Navigate to you downloads folder with ``cd /path/to/the/what/you/downloaded/above`` Now type: ``conda create -f environment.yml`` and press enter. This will take a small moment.
3. Now, we type ``conda activate rf-practical`` to switch to the new environment.
4. Start Jupyter: Type ``jupyter notebook`. You can open the exercise notebook.
