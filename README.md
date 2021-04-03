# Coursework materials

<!--ts-->
   
* [Completing in a cloud without installation](#completing-in-a-cloud-without-installation)
* [Completing on your personal computer](#completing-on-your-personal-computer)
* [Reporting problems and issues](#reporting-problems-and-issues)

<!-- Added by: Ilya Kisil, at: 2019-02-19T18:19+00:00 -->

<!--te-->

## Completing on your personal computer
 
1.  Install Anaconda - [installation file](https://www.anaconda.com/download/) (use `python 3.7`).

2.  Install JupyterLab in the base environment - [instructions](https://github.com/jupyterlab/jupyterlab#installation). Normally, it comes with Anaconda installation by default.

3.  Get source files.

    you can download a ZIP folder with all materials for this assignment by using the `Clone or Download` button (in green color) at the top of this page. 
    
4.  Bootstrap virtual environment. 
    
    If you are on Unix, then execute in terminal:
    ```bash
    cd dpm-coursework

    ./boostrap-venv.sh
    ```
    
    If you are on Windows, then open Anaconda prompt:
    ```bash
    cd dpm-coursework
    conda create -y --name "dpm-coursework" python=3.6.5
    conda activate "dpm-coursework"
    pip install binder\coursework
    python -m ipykernel install --user --name "dpm-coursework" --display-name "dpm-coursework"    
    ```
    
5.  Start JupyterLab and open a notebook with table of contents. You can find it under the `notebooks` directory. 

、
