[malitashfeen@login01 ~]$ ls
cache                  finetune_43262481.err  finetune_43263020.out  finetune_43348532.err  finetune_43368914.out  finetuned_model       logs
finetune_43262409.err  finetune_43262481.out  finetune_43348488.err  finetune_43348532.out  finetune_43369065.err  finetune_slurm.sh     train_model.py
finetune_43262409.out  finetune_43263020.err  finetune_43348488.out  finetune_43368914.err  finetune_43369065.out  finetuning_data_json  transformers-pytorch-gpu_latest.sif
[malitashfeen@login01 ~]$ module
module              modulemd-validator  
[malitashfeen@login01 ~]$ module
module              modulemd-validator  
[malitashfeen@login01 ~]$ module list

Currently Loaded Modules:
  1) shared   2) cpu/0.17.3b (c)   3) slurm/expanse/23.02.7   4) sdsc/1.0   5) DefaultModules

  Where:
   c:  built natively for AMD Rome

 

[malitashfeen@login01 ~]$ conda
-bash: conda: command not found
[malitashfeen@login01 ~]$ module avail

------------------------------------------------------------------ /cm/shared/apps/spack/0.17.3/cpu/b/share/spack/lmod/linux-rocky8-x86_64/Core ------------------------------------------------------------------
   anaconda3/2021.05/q4munrg    cmake/3.21.4/n5jtjsf                  gh/2.0.0/mkz3uxl          intel/19.1.3.304/6pv46so    nvhpc/21.9/xxpthf5           rclone/1.56.2/mldjorr        ucx/1.10.1/wla3unl
   aocc/3.2.0/io3s466           entrezdirect/10.7.20190114/6pkkpx2    git-lfs/2.11.0/kmruniy    matlab/2022b/lefe4oq        parallel/20210922/sqru6rr    sratoolkit/2.10.9/rn4humf
   aria2/1.35.0/q32jtg2         gcc/10.2.0/npcyll4                    git/2.31.1/ldetm5y        mercurial/5.8/qmgrjvl       pigz/2.6/bgymyil             subversion/1.14.0/qpzq6zs

--------------------------------------------------------------------------------------------- /cm/local/modulefiles ----------------------------------------------------------------------------------------------
   shared (L)    singularitypro/3.11 (D)    singularitypro/4.1.2    slurm/expanse/23.02.7 (L)

--------------------------------------------------------------------------------------- /cm/shared/apps/access/modulefiles ---------------------------------------------------------------------------------------
   accessusage/0.5-1    cue-login-env

--------------------------------------------------------------------------------------------- /usr/share/modulefiles ---------------------------------------------------------------------------------------------
   DefaultModules (L)    cpu/0.15.4 (c)    cpu/0.17.3b (c,L,D)    gpu/0.15.4 (g)    gpu/0.17.3b (g,D)    nostack/0.15.4 (e)    nostack/0.17.3b (e,D)

--------------------------------------------------------------------------------------------- /cm/shared/modulefiles ---------------------------------------------------------------------------------------------
   AMDuProf/3.4.475    default-environment    sdsc/1.0 (L)    slurm/expanse/23.02.7

  Where:
   L:  Module is loaded
   c:  built natively for AMD Rome
   e:  not architecture specific
   g:  built natively for Intel Skylake
   D:  Default Module

Module defaults are chosen based on Find First Rules due to Name/Version/Version modules found in the module tree.
See https://lmod.readthedocs.io/en/latest/060_locating.html for details.

Use "module spider" to find all possible modules and extensions.
Use "module keyword key1 key2 ..." to search for all possible modules matching any of the "keys".


[malitashfeen@login01 ~]$ module load anaconda3/2021.05/q4munrg
[malitashfeen@login01 ~]$ 
[malitashfeen@login01 ~]$ conda
usage: conda [-h] [-V] command ...

conda is a tool for managing and deploying applications, environments and packages.

Options:

positional arguments:
  command
    clean        Remove unused packages and caches.
    compare      Compare packages between conda environments.
    config       Modify configuration values in .condarc. This is modeled after the git config command. Writes to the user .condarc file (/home/malitashfeen/.condarc) by default.
    create       Create a new conda environment from a list of specified packages.
    help         Displays a list of available conda commands and their help strings.
    info         Display information about current conda install.
    init         Initialize conda for shell interaction. [Experimental]
    install      Installs a list of packages into a specified conda environment.
    list         List linked packages in a conda environment.
    package      Low-level conda package utility. (EXPERIMENTAL)
    remove       Remove a list of packages from a specified conda environment.
    uninstall    Alias for conda remove.
    run          Run an executable in a conda environment. [Experimental]
    search       Search for packages and display associated information. The input is a MatchSpec, a query language for conda packages. See examples below.
    update       Updates conda packages to the latest compatible version.
    upgrade      Alias for conda update.

optional arguments:
  -h, --help     Show this help message and exit.
  -V, --version  Show the conda version number and exit.

conda commands available from other packages:
  build
  content-trust
  convert
  debug
  develop
  env
  index
  inspect
  metapackage
  render
  repo
  server
  skeleton
  token
  verify
[malitashfeen@login01 ~]$ module load anaconda3/2021.05/q4munrg
[malitashfeen@login01 ~]$ module load anaconda3/2021.05/q4munrg
[malitashfeen@login01 ~]$ module load anaconda3/2021.05/q4munrg
[malitashfeen@login01 ~]$ module load anaconda3/2021.05/q4munrg
[malitashfeen@login01 ~]$ 
[malitashfeen@login01 ~]$ 
[malitashfeen@login01 ~]$ conda
usage: conda [-h] [-V] command ...

conda is a tool for managing and deploying applications, environments and packages.

Options:

positional arguments:
  command
    clean        Remove unused packages and caches.
    compare      Compare packages between conda environments.
    config       Modify configuration values in .condarc. This is modeled after the git config command. Writes to the user .condarc file (/home/malitashfeen/.condarc) by default.
    create       Create a new conda environment from a list of specified packages.
    help         Displays a list of available conda commands and their help strings.
    info         Display information about current conda install.
    init         Initialize conda for shell interaction. [Experimental]
    install      Installs a list of packages into a specified conda environment.
    list         List linked packages in a conda environment.
    package      Low-level conda package utility. (EXPERIMENTAL)
    remove       Remove a list of packages from a specified conda environment.
    uninstall    Alias for conda remove.
    run          Run an executable in a conda environment. [Experimental]
    search       Search for packages and display associated information. The input is a MatchSpec, a query language for conda packages. See examples below.
    update       Updates conda packages to the latest compatible version.
    upgrade      Alias for conda update.

optional arguments:
  -h, --help     Show this help message and exit.
  -V, --version  Show the conda version number and exit.

conda commands available from other packages:
  build
  content-trust
  convert
  debug
  develop
  env
  index
  inspect
  metapackage
  render
  repo
  server
  skeleton
  token
  verify
[malitashfeen@login01 ~]$ 