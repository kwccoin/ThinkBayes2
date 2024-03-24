Last login: Sun Mar 24 13:56:19 on ttys002
ngcchk@ngcchk-m2air ThinkBayes2 % make
conda create -y --name ThinkBayes2 python=3.10 pymc
make: conda: No such file or directory
make: *** [create_environment] Error 1
ngcchk@ngcchk-m2air ThinkBayes2 % ls
CHANGES.txt			install_test.py
LICENSE.txt			jb
Makefile			notebooks
README.md			papers
ThinkBayes2Notebooks.zip	requirements-dev.txt
book				requirements.txt
data				scripts
docs				soln
environment.yml			workshop
examples
ngcchk@ngcchk-m2air ThinkBayes2 % mkdir ThinkBaues2
ngcchk@ngcchk-m2air ThinkBayes2 % make             
conda create -y --name ThinkBayes2 python=3.10 pymc
make: conda: No such file or directory
make: *** [create_environment] Error 1
ngcchk@ngcchk-m2air ThinkBayes2 % conda
usage: conda [-h] [-v] [--no-plugins] [-V] COMMAND ...

conda is a tool for managing and deploying applications, environments and packages.

options:
  -h, --help          Show this help message and exit.
  -v, --verbose       Can be used multiple times. Once for detailed output,
                      twice for INFO logging, thrice for DEBUG logging, four
                      times for TRACE logging.
  --no-plugins        Disable all plugins that are not built into conda.
  -V, --version       Show the conda version number and exit.

commands:
  The following built-in and plugins subcommands are available.

  COMMAND
    activate          Activate a conda environment.
    clean             Remove unused packages and caches.
    compare           Compare packages between conda environments.
    config            Modify configuration values in .condarc.
    content-trust     See `conda content-trust --help`.
    create            Create a new conda environment from a list of specified
                      packages.
    deactivate        Deactivate the current active conda environment.
    doctor            Display a health report for your environment.
    info              Display information about current conda install.
    init              Initialize conda for shell interaction.
    install           Install a list of packages into a specified conda
                      environment.
    list              List installed packages in a conda environment.
    notices           Retrieve latest channel notifications.
    package           Create low-level conda packages. (EXPERIMENTAL)
    remove (uninstall)
                      Remove a list of packages from a specified conda
                      environment.
    rename            Rename an existing environment.
    repoquery         Advanced search for repodata.
    run               Run an executable in a conda environment.
    search            Search for packages and display associated information
                      using the MatchSpec format.
    update (upgrade)  Update conda packages to the latest compatible version.
ngcchk@ngcchk-m2air ThinkBayes2 % conda create --name TB2 python=3.10 pymc
Retrieving notices: ...working... done
Channels:
 - defaults
Platform: osx-arm64
Collecting package metadata (repodata.json): done
Solving environment: done

## Package Plan ##

  environment location: /Users/ngcchk/miniconda3/envs/TB2

  added / updated specs:
    - pymc
    - python=3.10


The following packages will be downloaded:

    package                    |            build
    ---------------------------|-----------------
    arviz-0.16.0               |  py310hca03da5_0         1.7 MB
    bottleneck-1.3.7           |  py310hbda83bc_0         111 KB
    bzip2-1.0.8                |       h80987f9_5         129 KB
    ca-certificates-2024.3.11  |       hca03da5_0         128 KB
    cachetools-4.2.2           |     pyhd3eb1b0_0          13 KB
    cloudpickle-2.2.1          |  py310hca03da5_0          43 KB
    cons-0.4.6                 |  py310hca03da5_0          18 KB
    contourpy-1.2.0            |  py310h48ca7d4_0         238 KB
    etuples-0.3.9              |  py310hca03da5_0          23 KB
    fastprogress-1.0.0         |     pyhb85f177_0          16 KB
    filelock-3.13.1            |  py310hca03da5_0          22 KB
    h5netcdf-1.2.0             |  py310hca03da5_0          84 KB
    h5py-3.9.0                 |  py310haafd478_0         1.1 MB
    hdf5-1.12.1                |       h05c076b_3         5.3 MB
    kiwisolver-1.4.4           |  py310h313beb8_0          61 KB
    lerc-3.0                   |       hc377ac9_0         115 KB
    libdeflate-1.17            |       h80987f9_1          55 KB
    libtiff-4.5.1              |       h313beb8_0         496 KB
    libwebp-base-1.3.2         |       h80987f9_0         297 KB
    logical-unification-0.4.6  |  py310hca03da5_0          26 KB
    matplotlib-base-3.8.0      |  py310h46d7db6_0         6.8 MB
    minikanren-1.0.3           |  py310hca03da5_0          43 KB
    multipledispatch-0.6.0     |  py310hca03da5_0          23 KB
    numexpr-2.8.7              |  py310hecc3335_0         126 KB
    numpy-1.26.4               |  py310h3b2db8e_0          12 KB
    numpy-base-1.26.4          |  py310ha9811e2_0         5.8 MB
    packaging-23.2             |  py310hca03da5_0         147 KB
    pandas-2.2.1               |  py310h313beb8_0        12.3 MB
    pillow-10.2.0              |  py310h80987f9_0         706 KB
    pip-23.3.1                 |  py310hca03da5_0         2.7 MB
    pymc-5.6.1                 |  py310hea593b9_0         630 KB
    pyparsing-3.0.9            |  py310hca03da5_0         151 KB
    pytensor-2.12.3            |  py310h46d7db6_0         2.3 MB
    python-3.10.14             |       hb885b13_0        13.0 MB
    pytz-2023.3.post1          |  py310hca03da5_0         212 KB
    scipy-1.12.0               |  py310h20cbe94_0        21.0 MB
    setuptools-68.2.2          |  py310hca03da5_0         942 KB
    toolz-0.12.0               |  py310hca03da5_0         109 KB
    typing-extensions-4.9.0    |  py310hca03da5_1          10 KB
    typing_extensions-4.9.0    |  py310hca03da5_1          55 KB
    tzdata-2024a               |       h04d1e81_0         116 KB
    wheel-0.41.2               |  py310hca03da5_0         107 KB
    xarray-2023.6.0            |  py310hca03da5_0         1.7 MB
    xarray-einstats-0.6.0      |  py310hca03da5_0          51 KB
    xz-5.4.6                   |       h80987f9_0         372 KB
    ------------------------------------------------------------
                                           Total:        79.2 MB

The following NEW packages will be INSTALLED:

  arviz              pkgs/main/osx-arm64::arviz-0.16.0-py310hca03da5_0 
  blas               pkgs/main/osx-arm64::blas-1.0-openblas 
  bottleneck         pkgs/main/osx-arm64::bottleneck-1.3.7-py310hbda83bc_0 
  brotli             pkgs/main/osx-arm64::brotli-1.0.9-h1a28f6b_7 
  brotli-bin         pkgs/main/osx-arm64::brotli-bin-1.0.9-h1a28f6b_7 
  bzip2              pkgs/main/osx-arm64::bzip2-1.0.8-h80987f9_5 
  c-ares             pkgs/main/osx-arm64::c-ares-1.19.1-h80987f9_0 
  ca-certificates    pkgs/main/osx-arm64::ca-certificates-2024.3.11-hca03da5_0 
  cachetools         pkgs/main/noarch::cachetools-4.2.2-pyhd3eb1b0_0 
  cloudpickle        pkgs/main/osx-arm64::cloudpickle-2.2.1-py310hca03da5_0 
  cons               pkgs/main/osx-arm64::cons-0.4.6-py310hca03da5_0 
  contourpy          pkgs/main/osx-arm64::contourpy-1.2.0-py310h48ca7d4_0 
  cycler             pkgs/main/noarch::cycler-0.11.0-pyhd3eb1b0_0 
  etuples            pkgs/main/osx-arm64::etuples-0.3.9-py310hca03da5_0 
  fastprogress       pkgs/main/noarch::fastprogress-1.0.0-pyhb85f177_0 
  filelock           pkgs/main/osx-arm64::filelock-3.13.1-py310hca03da5_0 
  fonttools          pkgs/main/noarch::fonttools-4.25.0-pyhd3eb1b0_0 
  freetype           pkgs/main/osx-arm64::freetype-2.12.1-h1192e45_0 
  h5netcdf           pkgs/main/osx-arm64::h5netcdf-1.2.0-py310hca03da5_0 
  h5py               pkgs/main/osx-arm64::h5py-3.9.0-py310haafd478_0 
  hdf5               pkgs/main/osx-arm64::hdf5-1.12.1-h05c076b_3 
  jpeg               pkgs/main/osx-arm64::jpeg-9e-h80987f9_1 
  kiwisolver         pkgs/main/osx-arm64::kiwisolver-1.4.4-py310h313beb8_0 
  krb5               pkgs/main/osx-arm64::krb5-1.20.1-hf3e1bf2_1 
  lcms2              pkgs/main/osx-arm64::lcms2-2.12-hba8e193_0 
  lerc               pkgs/main/osx-arm64::lerc-3.0-hc377ac9_0 
  libbrotlicommon    pkgs/main/osx-arm64::libbrotlicommon-1.0.9-h1a28f6b_7 
  libbrotlidec       pkgs/main/osx-arm64::libbrotlidec-1.0.9-h1a28f6b_7 
  libbrotlienc       pkgs/main/osx-arm64::libbrotlienc-1.0.9-h1a28f6b_7 
  libcurl            pkgs/main/osx-arm64::libcurl-8.5.0-h3e2b118_0 
  libcxx             pkgs/main/osx-arm64::libcxx-14.0.6-h848a8c0_0 
  libdeflate         pkgs/main/osx-arm64::libdeflate-1.17-h80987f9_1 
  libedit            pkgs/main/osx-arm64::libedit-3.1.20230828-h80987f9_0 
  libev              pkgs/main/osx-arm64::libev-4.33-h1a28f6b_1 
  libffi             pkgs/main/osx-arm64::libffi-3.4.4-hca03da5_0 
  libgfortran        pkgs/main/osx-arm64::libgfortran-5.0.0-11_3_0_hca03da5_28 
  libgfortran5       pkgs/main/osx-arm64::libgfortran5-11.3.0-h009349e_28 
  libnghttp2         pkgs/main/osx-arm64::libnghttp2-1.57.0-h62f6fdd_0 
  libopenblas        pkgs/main/osx-arm64::libopenblas-0.3.21-h269037a_0 
  libpng             pkgs/main/osx-arm64::libpng-1.6.39-h80987f9_0 
  libssh2            pkgs/main/osx-arm64::libssh2-1.10.0-h02f6b3c_2 
  libtiff            pkgs/main/osx-arm64::libtiff-4.5.1-h313beb8_0 
  libwebp-base       pkgs/main/osx-arm64::libwebp-base-1.3.2-h80987f9_0 
  llvm-openmp        pkgs/main/osx-arm64::llvm-openmp-14.0.6-hc6e5704_0 
  logical-unificati~ pkgs/main/osx-arm64::logical-unification-0.4.6-py310hca03da5_0 
  lz4-c              pkgs/main/osx-arm64::lz4-c-1.9.4-h313beb8_0 
  matplotlib-base    pkgs/main/osx-arm64::matplotlib-base-3.8.0-py310h46d7db6_0 
  minikanren         pkgs/main/osx-arm64::minikanren-1.0.3-py310hca03da5_0 
  multipledispatch   pkgs/main/osx-arm64::multipledispatch-0.6.0-py310hca03da5_0 
  munkres            pkgs/main/noarch::munkres-1.1.4-py_0 
  ncurses            pkgs/main/osx-arm64::ncurses-6.4-h313beb8_0 
  numexpr            pkgs/main/osx-arm64::numexpr-2.8.7-py310hecc3335_0 
  numpy              pkgs/main/osx-arm64::numpy-1.26.4-py310h3b2db8e_0 
  numpy-base         pkgs/main/osx-arm64::numpy-base-1.26.4-py310ha9811e2_0 
  openjpeg           pkgs/main/osx-arm64::openjpeg-2.3.0-h7a6adac_2 
  openssl            pkgs/main/osx-arm64::openssl-3.0.13-h1a28f6b_0 
  packaging          pkgs/main/osx-arm64::packaging-23.2-py310hca03da5_0 
  pandas             pkgs/main/osx-arm64::pandas-2.2.1-py310h313beb8_0 
  pillow             pkgs/main/osx-arm64::pillow-10.2.0-py310h80987f9_0 
  pip                pkgs/main/osx-arm64::pip-23.3.1-py310hca03da5_0 
  pymc               pkgs/main/osx-arm64::pymc-5.6.1-py310hea593b9_0 
  pyparsing          pkgs/main/osx-arm64::pyparsing-3.0.9-py310hca03da5_0 
  pytensor           pkgs/main/osx-arm64::pytensor-2.12.3-py310h46d7db6_0 
  python             pkgs/main/osx-arm64::python-3.10.14-hb885b13_0 
  python-dateutil    pkgs/main/noarch::python-dateutil-2.8.2-pyhd3eb1b0_0 
  python-tzdata      pkgs/main/noarch::python-tzdata-2023.3-pyhd3eb1b0_0 
  pytz               pkgs/main/osx-arm64::pytz-2023.3.post1-py310hca03da5_0 
  readline           pkgs/main/osx-arm64::readline-8.2-h1a28f6b_0 
  scipy              pkgs/main/osx-arm64::scipy-1.12.0-py310h20cbe94_0 
  setuptools         pkgs/main/osx-arm64::setuptools-68.2.2-py310hca03da5_0 
  six                pkgs/main/noarch::six-1.16.0-pyhd3eb1b0_1 
  sqlite             pkgs/main/osx-arm64::sqlite-3.41.2-h80987f9_0 
  tk                 pkgs/main/osx-arm64::tk-8.6.12-hb8d0fd4_0 
  toolz              pkgs/main/osx-arm64::toolz-0.12.0-py310hca03da5_0 
  typing-extensions  pkgs/main/osx-arm64::typing-extensions-4.9.0-py310hca03da5_1 
  typing_extensions  pkgs/main/osx-arm64::typing_extensions-4.9.0-py310hca03da5_1 
  tzdata             pkgs/main/noarch::tzdata-2024a-h04d1e81_0 
  wheel              pkgs/main/osx-arm64::wheel-0.41.2-py310hca03da5_0 
  xarray             pkgs/main/osx-arm64::xarray-2023.6.0-py310hca03da5_0 
  xarray-einstats    pkgs/main/osx-arm64::xarray-einstats-0.6.0-py310hca03da5_0 
  xz                 pkgs/main/osx-arm64::xz-5.4.6-h80987f9_0 
  zlib               pkgs/main/osx-arm64::zlib-1.2.13-h5a0b063_0 
  zstd               pkgs/main/osx-arm64::zstd-1.5.5-hd90d995_0 


Proceed ([y]/n)? y


Downloading and Extracting Packages:
                                                                                
Preparing transaction: done                                                     
Verifying transaction: done                                                     
Executing transaction: done                                                     
#                                                                               
# To activate this environment, use                                             
#                                                                               
#     $ conda activate TB2                                                      
#                                                                               
# To deactivate an active environment, use                                      
#                                                                               
#     $ conda deactivate                                                        
                                                                                
ngcchk@ngcchk-m2air ThinkBayes2 % conda activate TB2
(TB2) ngcchk@ngcchk-m2air ThinkBayes2 % which python
/Users/ngcchk/miniconda3/envs/TB2/bin/python
(TB2) ngcchk@ngcchk-m2air ThinkBayes2 % python --version
Python 3.10.14
(TB2) ngcchk@ngcchk-m2air ThinkBayes2 % python -m pip install -U pip setuptools wheel
Requirement already satisfied: pip in /Users/ngcchk/miniconda3/envs/TB2/lib/python3.10/site-packages (23.3.1)
Collecting pip
  Downloading pip-24.0-py3-none-any.whl.metadata (3.6 kB)
Requirement already satisfied: setuptools in /Users/ngcchk/miniconda3/envs/TB2/lib/python3.10/site-packages (68.2.2)
Collecting setuptools
  Downloading setuptools-69.2.0-py3-none-any.whl.metadata (6.3 kB)
Requirement already satisfied: wheel in /Users/ngcchk/miniconda3/envs/TB2/lib/python3.10/site-packages (0.41.2)
Collecting wheel
  Using cached wheel-0.43.0-py3-none-any.whl.metadata (2.2 kB)
Downloading pip-24.0-py3-none-any.whl (2.1 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.1/2.1 MB 1.7 MB/s eta 0:00:00
Downloading setuptools-69.2.0-py3-none-any.whl (821 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 821.5/821.5 kB 3.3 MB/s eta 0:00:00
Using cached wheel-0.43.0-py3-none-any.whl (65 kB)
Installing collected packages: wheel, setuptools, pip
  Attempting uninstall: wheel
    Found existing installation: wheel 0.41.2
    Uninstalling wheel-0.41.2:
      Successfully uninstalled wheel-0.41.2
  Attempting uninstall: setuptools
    Found existing installation: setuptools 68.2.2
    Uninstalling setuptools-68.2.2:
      Successfully uninstalled setuptools-68.2.2
  Attempting uninstall: pip
    Found existing installation: pip 23.3.1
    Uninstalling pip-23.3.1:
      Successfully uninstalled pip-23.3.1
Successfully installed pip-24.0 setuptools-69.2.0 wheel-0.43.0
(TB2) ngcchk@ngcchk-m2air ThinkBayes2 % python -m pip install -r requirements.txt
Collecting jupyter (from -r requirements.txt (line 1))
  Downloading jupyter-1.0.0-py2.py3-none-any.whl.metadata (995 bytes)
Collecting nbclassic (from -r requirements.txt (line 2))
  Downloading nbclassic-1.0.0-py3-none-any.whl.metadata (4.0 kB)
Collecting seaborn (from -r requirements.txt (line 3))
  Downloading seaborn-0.13.2-py3-none-any.whl.metadata (5.4 kB)
Collecting statsmodels (from -r requirements.txt (line 4))
  Downloading statsmodels-0.14.1-cp310-cp310-macosx_11_0_arm64.whl.metadata (9.5 kB)
Collecting lxml (from -r requirements.txt (line 5))
  Downloading lxml-5.1.0-cp310-cp310-macosx_11_0_arm64.whl.metadata (3.5 kB)
Collecting xlrd (from -r requirements.txt (line 6))
  Downloading xlrd-2.0.1-py2.py3-none-any.whl.metadata (3.4 kB)
Collecting html5lib (from -r requirements.txt (line 7))
  Downloading html5lib-1.1-py2.py3-none-any.whl.metadata (16 kB)
Collecting tables (from -r requirements.txt (line 8))
  Downloading tables-3.9.2.tar.gz (4.7 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 4.7/4.7 MB 2.4 MB/s eta 0:00:00
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
  Preparing metadata (pyproject.toml) ... done
Collecting empiricaldist (from -r requirements.txt (line 9))
  Downloading empiricaldist-0.7.2.tar.gz (12 kB)
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
  Installing backend dependencies ... done
  Preparing metadata (pyproject.toml) ... done
Collecting notebook (from jupyter->-r requirements.txt (line 1))
  Downloading notebook-7.1.2-py3-none-any.whl.metadata (10 kB)
Collecting qtconsole (from jupyter->-r requirements.txt (line 1))
  Downloading qtconsole-5.5.1-py3-none-any.whl.metadata (5.1 kB)
Collecting jupyter-console (from jupyter->-r requirements.txt (line 1))
  Downloading jupyter_console-6.6.3-py3-none-any.whl.metadata (5.8 kB)
Collecting nbconvert (from jupyter->-r requirements.txt (line 1))
  Downloading nbconvert-7.16.3-py3-none-any.whl.metadata (8.2 kB)
Collecting ipykernel (from jupyter->-r requirements.txt (line 1))
  Downloading ipykernel-6.29.3-py3-none-any.whl.metadata (6.3 kB)
Collecting ipywidgets (from jupyter->-r requirements.txt (line 1))
  Downloading ipywidgets-8.1.2-py3-none-any.whl.metadata (2.4 kB)
Collecting jinja2 (from nbclassic->-r requirements.txt (line 2))
  Downloading Jinja2-3.1.3-py3-none-any.whl.metadata (3.3 kB)
Collecting tornado>=6.1 (from nbclassic->-r requirements.txt (line 2))
  Downloading tornado-6.4-cp38-abi3-macosx_10_9_universal2.whl.metadata (2.5 kB)
Collecting pyzmq>=17 (from nbclassic->-r requirements.txt (line 2))
  Downloading pyzmq-25.1.2-cp310-cp310-macosx_10_15_universal2.whl.metadata (4.9 kB)
Collecting argon2-cffi (from nbclassic->-r requirements.txt (line 2))
  Using cached argon2_cffi-23.1.0-py3-none-any.whl.metadata (5.2 kB)
Collecting traitlets>=4.2.1 (from nbclassic->-r requirements.txt (line 2))
  Downloading traitlets-5.14.2-py3-none-any.whl.metadata (10 kB)
Collecting jupyter-core>=4.6.1 (from nbclassic->-r requirements.txt (line 2))
  Downloading jupyter_core-5.7.2-py3-none-any.whl.metadata (3.4 kB)
Collecting jupyter-client>=6.1.1 (from nbclassic->-r requirements.txt (line 2))
  Downloading jupyter_client-8.6.1-py3-none-any.whl.metadata (8.3 kB)
Collecting ipython-genutils (from nbclassic->-r requirements.txt (line 2))
  Downloading ipython_genutils-0.2.0-py2.py3-none-any.whl.metadata (755 bytes)
Collecting jupyter-server>=1.8 (from nbclassic->-r requirements.txt (line 2))
  Downloading jupyter_server-2.13.0-py3-none-any.whl.metadata (8.4 kB)
Collecting nbformat (from nbclassic->-r requirements.txt (line 2))
  Downloading nbformat-5.10.3-py3-none-any.whl.metadata (3.6 kB)
Collecting notebook-shim>=0.2.3 (from nbclassic->-r requirements.txt (line 2))
  Downloading notebook_shim-0.2.4-py3-none-any.whl.metadata (4.0 kB)
Collecting nest-asyncio>=1.5 (from nbclassic->-r requirements.txt (line 2))
  Downloading nest_asyncio-1.6.0-py3-none-any.whl.metadata (2.8 kB)
Collecting Send2Trash>=1.8.0 (from nbclassic->-r requirements.txt (line 2))
  Downloading Send2Trash-1.8.2-py3-none-any.whl.metadata (4.0 kB)
Collecting terminado>=0.8.3 (from nbclassic->-r requirements.txt (line 2))
  Downloading terminado-0.18.1-py3-none-any.whl.metadata (5.8 kB)
Collecting prometheus-client (from nbclassic->-r requirements.txt (line 2))
  Downloading prometheus_client-0.20.0-py3-none-any.whl.metadata (1.8 kB)
Requirement already satisfied: numpy!=1.24.0,>=1.20 in /Users/ngcchk/miniconda3/envs/TB2/lib/python3.10/site-packages (from seaborn->-r requirements.txt (line 3)) (1.26.4)
Requirement already satisfied: pandas>=1.2 in /Users/ngcchk/miniconda3/envs/TB2/lib/python3.10/site-packages (from seaborn->-r requirements.txt (line 3)) (2.2.1)
Requirement already satisfied: matplotlib!=3.6.1,>=3.4 in /Users/ngcchk/miniconda3/envs/TB2/lib/python3.10/site-packages (from seaborn->-r requirements.txt (line 3)) (3.8.0)
Requirement already satisfied: scipy!=1.9.2,>=1.4 in /Users/ngcchk/miniconda3/envs/TB2/lib/python3.10/site-packages (from statsmodels->-r requirements.txt (line 4)) (1.12.0)
Collecting patsy>=0.5.4 (from statsmodels->-r requirements.txt (line 4))
  Downloading patsy-0.5.6-py2.py3-none-any.whl.metadata (3.5 kB)
Requirement already satisfied: packaging>=21.3 in /Users/ngcchk/miniconda3/envs/TB2/lib/python3.10/site-packages (from statsmodels->-r requirements.txt (line 4)) (23.2)
Requirement already satisfied: six>=1.9 in /Users/ngcchk/miniconda3/envs/TB2/lib/python3.10/site-packages (from html5lib->-r requirements.txt (line 7)) (1.16.0)
Collecting webencodings (from html5lib->-r requirements.txt (line 7))
  Downloading webencodings-0.5.1-py2.py3-none-any.whl.metadata (2.1 kB)
Requirement already satisfied: numexpr>=2.6.2 in /Users/ngcchk/miniconda3/envs/TB2/lib/python3.10/site-packages (from tables->-r requirements.txt (line 8)) (2.8.7)
Collecting py-cpuinfo (from tables->-r requirements.txt (line 8))
  Using cached py_cpuinfo-9.0.0-py3-none-any.whl.metadata (794 bytes)
Collecting blosc2>=2.3.0 (from tables->-r requirements.txt (line 8))
  Using cached blosc2-2.5.1-cp310-cp310-macosx_11_0_arm64.whl.metadata (9.2 kB)
Collecting ndindex>=1.4 (from blosc2>=2.3.0->tables->-r requirements.txt (line 8))
  Using cached ndindex-1.8-py3-none-any.whl.metadata (3.4 kB)
Collecting msgpack (from blosc2>=2.3.0->tables->-r requirements.txt (line 8))
  Using cached msgpack-1.0.8-cp310-cp310-macosx_11_0_arm64.whl.metadata (9.1 kB)
Requirement already satisfied: python-dateutil>=2.8.2 in /Users/ngcchk/miniconda3/envs/TB2/lib/python3.10/site-packages (from jupyter-client>=6.1.1->nbclassic->-r requirements.txt (line 2)) (2.8.2)
Collecting platformdirs>=2.5 (from jupyter-core>=4.6.1->nbclassic->-r requirements.txt (line 2))
  Downloading platformdirs-4.2.0-py3-none-any.whl.metadata (11 kB)
Collecting anyio>=3.1.0 (from jupyter-server>=1.8->nbclassic->-r requirements.txt (line 2))
  Downloading anyio-4.3.0-py3-none-any.whl.metadata (4.6 kB)
Collecting jupyter-events>=0.9.0 (from jupyter-server>=1.8->nbclassic->-r requirements.txt (line 2))
  Downloading jupyter_events-0.10.0-py3-none-any.whl.metadata (5.9 kB)
Collecting jupyter-server-terminals (from jupyter-server>=1.8->nbclassic->-r requirements.txt (line 2))
  Downloading jupyter_server_terminals-0.5.3-py3-none-any.whl.metadata (5.6 kB)
Collecting overrides (from jupyter-server>=1.8->nbclassic->-r requirements.txt (line 2))
  Downloading overrides-7.7.0-py3-none-any.whl.metadata (5.8 kB)
Collecting websocket-client (from jupyter-server>=1.8->nbclassic->-r requirements.txt (line 2))
  Downloading websocket_client-1.7.0-py3-none-any.whl.metadata (7.9 kB)
Requirement already satisfied: contourpy>=1.0.1 in /Users/ngcchk/miniconda3/envs/TB2/lib/python3.10/site-packages (from matplotlib!=3.6.1,>=3.4->seaborn->-r requirements.txt (line 3)) (1.2.0)
Requirement already satisfied: cycler>=0.10 in /Users/ngcchk/miniconda3/envs/TB2/lib/python3.10/site-packages (from matplotlib!=3.6.1,>=3.4->seaborn->-r requirements.txt (line 3)) (0.11.0)
Requirement already satisfied: fonttools>=4.22.0 in /Users/ngcchk/miniconda3/envs/TB2/lib/python3.10/site-packages (from matplotlib!=3.6.1,>=3.4->seaborn->-r requirements.txt (line 3)) (4.25.0)
Requirement already satisfied: kiwisolver>=1.0.1 in /Users/ngcchk/miniconda3/envs/TB2/lib/python3.10/site-packages (from matplotlib!=3.6.1,>=3.4->seaborn->-r requirements.txt (line 3)) (1.4.4)
Requirement already satisfied: pillow>=6.2.0 in /Users/ngcchk/miniconda3/envs/TB2/lib/python3.10/site-packages (from matplotlib!=3.6.1,>=3.4->seaborn->-r requirements.txt (line 3)) (10.2.0)
Requirement already satisfied: pyparsing>=2.3.1 in /Users/ngcchk/miniconda3/envs/TB2/lib/python3.10/site-packages (from matplotlib!=3.6.1,>=3.4->seaborn->-r requirements.txt (line 3)) (3.0.9)
Collecting beautifulsoup4 (from nbconvert->jupyter->-r requirements.txt (line 1))
  Downloading beautifulsoup4-4.12.3-py3-none-any.whl.metadata (3.8 kB)
Collecting bleach!=5.0.0 (from nbconvert->jupyter->-r requirements.txt (line 1))
  Using cached bleach-6.1.0-py3-none-any.whl.metadata (30 kB)
Collecting defusedxml (from nbconvert->jupyter->-r requirements.txt (line 1))
  Downloading defusedxml-0.7.1-py2.py3-none-any.whl.metadata (32 kB)
Collecting jupyterlab-pygments (from nbconvert->jupyter->-r requirements.txt (line 1))
  Downloading jupyterlab_pygments-0.3.0-py3-none-any.whl.metadata (4.4 kB)
Collecting markupsafe>=2.0 (from nbconvert->jupyter->-r requirements.txt (line 1))
  Downloading MarkupSafe-2.1.5-cp310-cp310-macosx_10_9_universal2.whl.metadata (3.0 kB)
Collecting mistune<4,>=2.0.3 (from nbconvert->jupyter->-r requirements.txt (line 1))
  Using cached mistune-3.0.2-py3-none-any.whl.metadata (1.7 kB)
Collecting nbclient>=0.5.0 (from nbconvert->jupyter->-r requirements.txt (line 1))
  Downloading nbclient-0.10.0-py3-none-any.whl.metadata (7.8 kB)
Collecting pandocfilters>=1.4.1 (from nbconvert->jupyter->-r requirements.txt (line 1))
  Downloading pandocfilters-1.5.1-py2.py3-none-any.whl.metadata (9.0 kB)
Collecting pygments>=2.4.1 (from nbconvert->jupyter->-r requirements.txt (line 1))
  Downloading pygments-2.17.2-py3-none-any.whl.metadata (2.6 kB)
Collecting tinycss2 (from nbconvert->jupyter->-r requirements.txt (line 1))
  Downloading tinycss2-1.2.1-py3-none-any.whl.metadata (3.0 kB)
Collecting fastjsonschema (from nbformat->nbclassic->-r requirements.txt (line 2))
  Downloading fastjsonschema-2.19.1-py3-none-any.whl.metadata (2.1 kB)
Collecting jsonschema>=2.6 (from nbformat->nbclassic->-r requirements.txt (line 2))
  Downloading jsonschema-4.21.1-py3-none-any.whl.metadata (7.8 kB)
Requirement already satisfied: pytz>=2020.1 in /Users/ngcchk/miniconda3/envs/TB2/lib/python3.10/site-packages (from pandas>=1.2->seaborn->-r requirements.txt (line 3)) (2023.3.post1)
Requirement already satisfied: tzdata>=2022.7 in /Users/ngcchk/miniconda3/envs/TB2/lib/python3.10/site-packages (from pandas>=1.2->seaborn->-r requirements.txt (line 3)) (2023.3)
Collecting ptyprocess (from terminado>=0.8.3->nbclassic->-r requirements.txt (line 2))
  Downloading ptyprocess-0.7.0-py2.py3-none-any.whl.metadata (1.3 kB)
Collecting argon2-cffi-bindings (from argon2-cffi->nbclassic->-r requirements.txt (line 2))
  Downloading argon2_cffi_bindings-21.2.0-cp38-abi3-macosx_10_9_universal2.whl.metadata (6.7 kB)
Collecting appnope (from ipykernel->jupyter->-r requirements.txt (line 1))
  Downloading appnope-0.1.4-py2.py3-none-any.whl.metadata (908 bytes)
Collecting comm>=0.1.1 (from ipykernel->jupyter->-r requirements.txt (line 1))
  Downloading comm-0.2.2-py3-none-any.whl.metadata (3.7 kB)
Collecting debugpy>=1.6.5 (from ipykernel->jupyter->-r requirements.txt (line 1))
  Downloading debugpy-1.8.1-py2.py3-none-any.whl.metadata (1.1 kB)
Collecting ipython>=7.23.1 (from ipykernel->jupyter->-r requirements.txt (line 1))
  Downloading ipython-8.22.2-py3-none-any.whl.metadata (4.8 kB)
Collecting matplotlib-inline>=0.1 (from ipykernel->jupyter->-r requirements.txt (line 1))
  Downloading matplotlib_inline-0.1.6-py3-none-any.whl.metadata (2.8 kB)
Collecting psutil (from ipykernel->jupyter->-r requirements.txt (line 1))
  Using cached psutil-5.9.8-cp38-abi3-macosx_11_0_arm64.whl.metadata (21 kB)
Collecting widgetsnbextension~=4.0.10 (from ipywidgets->jupyter->-r requirements.txt (line 1))
  Downloading widgetsnbextension-4.0.10-py3-none-any.whl.metadata (1.6 kB)
Collecting jupyterlab-widgets~=3.0.10 (from ipywidgets->jupyter->-r requirements.txt (line 1))
  Downloading jupyterlab_widgets-3.0.10-py3-none-any.whl.metadata (4.1 kB)
Collecting prompt-toolkit>=3.0.30 (from jupyter-console->jupyter->-r requirements.txt (line 1))
  Downloading prompt_toolkit-3.0.43-py3-none-any.whl.metadata (6.5 kB)
Collecting jupyterlab-server<3,>=2.22.1 (from notebook->jupyter->-r requirements.txt (line 1))
  Downloading jupyterlab_server-2.25.4-py3-none-any.whl.metadata (5.9 kB)
Collecting jupyterlab<4.2,>=4.1.1 (from notebook->jupyter->-r requirements.txt (line 1))
  Downloading jupyterlab-4.1.5-py3-none-any.whl.metadata (15 kB)
Collecting qtpy>=2.4.0 (from qtconsole->jupyter->-r requirements.txt (line 1))
  Downloading QtPy-2.4.1-py3-none-any.whl.metadata (12 kB)
Collecting idna>=2.8 (from anyio>=3.1.0->jupyter-server>=1.8->nbclassic->-r requirements.txt (line 2))
  Using cached idna-3.6-py3-none-any.whl.metadata (9.9 kB)
Collecting sniffio>=1.1 (from anyio>=3.1.0->jupyter-server>=1.8->nbclassic->-r requirements.txt (line 2))
  Using cached sniffio-1.3.1-py3-none-any.whl.metadata (3.9 kB)
Collecting exceptiongroup>=1.0.2 (from anyio>=3.1.0->jupyter-server>=1.8->nbclassic->-r requirements.txt (line 2))
  Downloading exceptiongroup-1.2.0-py3-none-any.whl.metadata (6.6 kB)
Requirement already satisfied: typing-extensions>=4.1 in /Users/ngcchk/miniconda3/envs/TB2/lib/python3.10/site-packages (from anyio>=3.1.0->jupyter-server>=1.8->nbclassic->-r requirements.txt (line 2)) (4.9.0)
Collecting decorator (from ipython>=7.23.1->ipykernel->jupyter->-r requirements.txt (line 1))
  Downloading decorator-5.1.1-py3-none-any.whl.metadata (4.0 kB)
Collecting jedi>=0.16 (from ipython>=7.23.1->ipykernel->jupyter->-r requirements.txt (line 1))
  Using cached jedi-0.19.1-py2.py3-none-any.whl.metadata (22 kB)
Collecting stack-data (from ipython>=7.23.1->ipykernel->jupyter->-r requirements.txt (line 1))
  Using cached stack_data-0.6.3-py3-none-any.whl.metadata (18 kB)
Collecting pexpect>4.3 (from ipython>=7.23.1->ipykernel->jupyter->-r requirements.txt (line 1))
  Downloading pexpect-4.9.0-py2.py3-none-any.whl.metadata (2.5 kB)
Collecting attrs>=22.2.0 (from jsonschema>=2.6->nbformat->nbclassic->-r requirements.txt (line 2))
  Downloading attrs-23.2.0-py3-none-any.whl.metadata (9.5 kB)
Collecting jsonschema-specifications>=2023.03.6 (from jsonschema>=2.6->nbformat->nbclassic->-r requirements.txt (line 2))
  Downloading jsonschema_specifications-2023.12.1-py3-none-any.whl.metadata (3.0 kB)
Collecting referencing>=0.28.4 (from jsonschema>=2.6->nbformat->nbclassic->-r requirements.txt (line 2))
  Downloading referencing-0.34.0-py3-none-any.whl.metadata (2.8 kB)
Collecting rpds-py>=0.7.1 (from jsonschema>=2.6->nbformat->nbclassic->-r requirements.txt (line 2))
  Downloading rpds_py-0.18.0-cp310-cp310-macosx_11_0_arm64.whl.metadata (4.1 kB)
Collecting python-json-logger>=2.0.4 (from jupyter-events>=0.9.0->jupyter-server>=1.8->nbclassic->-r requirements.txt (line 2))
  Downloading python_json_logger-2.0.7-py3-none-any.whl.metadata (6.5 kB)
Collecting pyyaml>=5.3 (from jupyter-events>=0.9.0->jupyter-server>=1.8->nbclassic->-r requirements.txt (line 2))
  Downloading PyYAML-6.0.1-cp310-cp310-macosx_11_0_arm64.whl.metadata (2.1 kB)
Collecting rfc3339-validator (from jupyter-events>=0.9.0->jupyter-server>=1.8->nbclassic->-r requirements.txt (line 2))
  Downloading rfc3339_validator-0.1.4-py2.py3-none-any.whl.metadata (1.5 kB)
Collecting rfc3986-validator>=0.1.1 (from jupyter-events>=0.9.0->jupyter-server>=1.8->nbclassic->-r requirements.txt (line 2))
  Downloading rfc3986_validator-0.1.1-py2.py3-none-any.whl.metadata (1.7 kB)
Collecting async-lru>=1.0.0 (from jupyterlab<4.2,>=4.1.1->notebook->jupyter->-r requirements.txt (line 1))
  Using cached async_lru-2.0.4-py3-none-any.whl.metadata (4.5 kB)
Collecting httpx>=0.25.0 (from jupyterlab<4.2,>=4.1.1->notebook->jupyter->-r requirements.txt (line 1))
  Downloading httpx-0.27.0-py3-none-any.whl.metadata (7.2 kB)
Collecting jupyter-lsp>=2.0.0 (from jupyterlab<4.2,>=4.1.1->notebook->jupyter->-r requirements.txt (line 1))
  Downloading jupyter_lsp-2.2.4-py3-none-any.whl.metadata (1.8 kB)
Collecting tomli (from jupyterlab<4.2,>=4.1.1->notebook->jupyter->-r requirements.txt (line 1))
  Downloading tomli-2.0.1-py3-none-any.whl.metadata (8.9 kB)
Collecting babel>=2.10 (from jupyterlab-server<3,>=2.22.1->notebook->jupyter->-r requirements.txt (line 1))
  Downloading Babel-2.14.0-py3-none-any.whl.metadata (1.6 kB)
Collecting json5>=0.9.0 (from jupyterlab-server<3,>=2.22.1->notebook->jupyter->-r requirements.txt (line 1))
  Downloading json5-0.9.24-py3-none-any.whl.metadata (30 kB)
Collecting requests>=2.31 (from jupyterlab-server<3,>=2.22.1->notebook->jupyter->-r requirements.txt (line 1))
  Using cached requests-2.31.0-py3-none-any.whl.metadata (4.6 kB)
Collecting wcwidth (from prompt-toolkit>=3.0.30->jupyter-console->jupyter->-r requirements.txt (line 1))
  Downloading wcwidth-0.2.13-py2.py3-none-any.whl.metadata (14 kB)
Collecting cffi>=1.0.1 (from argon2-cffi-bindings->argon2-cffi->nbclassic->-r requirements.txt (line 2))
  Downloading cffi-1.16.0-cp310-cp310-macosx_11_0_arm64.whl.metadata (1.5 kB)
Collecting soupsieve>1.2 (from beautifulsoup4->nbconvert->jupyter->-r requirements.txt (line 1))
  Using cached soupsieve-2.5-py3-none-any.whl.metadata (4.7 kB)
Collecting pycparser (from cffi>=1.0.1->argon2-cffi-bindings->argon2-cffi->nbclassic->-r requirements.txt (line 2))
  Downloading pycparser-2.21-py2.py3-none-any.whl.metadata (1.1 kB)
Collecting certifi (from httpx>=0.25.0->jupyterlab<4.2,>=4.1.1->notebook->jupyter->-r requirements.txt (line 1))
  Using cached certifi-2024.2.2-py3-none-any.whl.metadata (2.2 kB)
Collecting httpcore==1.* (from httpx>=0.25.0->jupyterlab<4.2,>=4.1.1->notebook->jupyter->-r requirements.txt (line 1))
  Downloading httpcore-1.0.4-py3-none-any.whl.metadata (20 kB)
Collecting h11<0.15,>=0.13 (from httpcore==1.*->httpx>=0.25.0->jupyterlab<4.2,>=4.1.1->notebook->jupyter->-r requirements.txt (line 1))
  Downloading h11-0.14.0-py3-none-any.whl.metadata (8.2 kB)
Collecting parso<0.9.0,>=0.8.3 (from jedi>=0.16->ipython>=7.23.1->ipykernel->jupyter->-r requirements.txt (line 1))
  Downloading parso-0.8.3-py2.py3-none-any.whl.metadata (7.5 kB)
Collecting fqdn (from jsonschema[format-nongpl]>=4.18.0->jupyter-events>=0.9.0->jupyter-server>=1.8->nbclassic->-r requirements.txt (line 2))
  Downloading fqdn-1.5.1-py3-none-any.whl.metadata (1.4 kB)
Collecting isoduration (from jsonschema[format-nongpl]>=4.18.0->jupyter-events>=0.9.0->jupyter-server>=1.8->nbclassic->-r requirements.txt (line 2))
  Downloading isoduration-20.11.0-py3-none-any.whl.metadata (5.7 kB)
Collecting jsonpointer>1.13 (from jsonschema[format-nongpl]>=4.18.0->jupyter-events>=0.9.0->jupyter-server>=1.8->nbclassic->-r requirements.txt (line 2))
  Using cached jsonpointer-2.4-py2.py3-none-any.whl.metadata (2.5 kB)
Collecting uri-template (from jsonschema[format-nongpl]>=4.18.0->jupyter-events>=0.9.0->jupyter-server>=1.8->nbclassic->-r requirements.txt (line 2))
  Using cached uri_template-1.3.0-py3-none-any.whl.metadata (8.8 kB)
Collecting webcolors>=1.11 (from jsonschema[format-nongpl]>=4.18.0->jupyter-events>=0.9.0->jupyter-server>=1.8->nbclassic->-r requirements.txt (line 2))
  Downloading webcolors-1.13-py3-none-any.whl.metadata (2.6 kB)
Collecting charset-normalizer<4,>=2 (from requests>=2.31->jupyterlab-server<3,>=2.22.1->notebook->jupyter->-r requirements.txt (line 1))
  Downloading charset_normalizer-3.3.2-cp310-cp310-macosx_11_0_arm64.whl.metadata (33 kB)
Collecting urllib3<3,>=1.21.1 (from requests>=2.31->jupyterlab-server<3,>=2.22.1->notebook->jupyter->-r requirements.txt (line 1))
  Using cached urllib3-2.2.1-py3-none-any.whl.metadata (6.4 kB)
Collecting executing>=1.2.0 (from stack-data->ipython>=7.23.1->ipykernel->jupyter->-r requirements.txt (line 1))
  Downloading executing-2.0.1-py2.py3-none-any.whl.metadata (9.0 kB)
Collecting asttokens>=2.1.0 (from stack-data->ipython>=7.23.1->ipykernel->jupyter->-r requirements.txt (line 1))
  Downloading asttokens-2.4.1-py2.py3-none-any.whl.metadata (5.2 kB)
Collecting pure-eval (from stack-data->ipython>=7.23.1->ipykernel->jupyter->-r requirements.txt (line 1))
  Downloading pure_eval-0.2.2-py3-none-any.whl.metadata (6.2 kB)
Collecting arrow>=0.15.0 (from isoduration->jsonschema[format-nongpl]>=4.18.0->jupyter-events>=0.9.0->jupyter-server>=1.8->nbclassic->-r requirements.txt (line 2))
  Using cached arrow-1.3.0-py3-none-any.whl.metadata (7.5 kB)
Collecting types-python-dateutil>=2.8.10 (from arrow>=0.15.0->isoduration->jsonschema[format-nongpl]>=4.18.0->jupyter-events>=0.9.0->jupyter-server>=1.8->nbclassic->-r requirements.txt (line 2))
  Downloading types_python_dateutil-2.9.0.20240316-py3-none-any.whl.metadata (1.8 kB)
Using cached jupyter-1.0.0-py2.py3-none-any.whl (2.7 kB)
Downloading nbclassic-1.0.0-py3-none-any.whl (10.0 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 10.0/10.0 MB 3.4 MB/s eta 0:00:00
Downloading seaborn-0.13.2-py3-none-any.whl (294 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 294.9/294.9 kB 3.2 MB/s eta 0:00:00
Downloading statsmodels-0.14.1-cp310-cp310-macosx_11_0_arm64.whl (10.1 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 10.1/10.1 MB 3.3 MB/s eta 0:00:00
Downloading lxml-5.1.0-cp310-cp310-macosx_11_0_arm64.whl (4.5 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 4.5/4.5 MB 3.3 MB/s eta 0:00:00
Downloading xlrd-2.0.1-py2.py3-none-any.whl (96 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 96.5/96.5 kB 2.7 MB/s eta 0:00:00
Downloading html5lib-1.1-py2.py3-none-any.whl (112 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 112.2/112.2 kB 3.2 MB/s eta 0:00:00
Using cached blosc2-2.5.1-cp310-cp310-macosx_11_0_arm64.whl (3.5 MB)
Downloading jupyter_client-8.6.1-py3-none-any.whl (105 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 105.9/105.9 kB 2.3 MB/s eta 0:00:00
Downloading jupyter_core-5.7.2-py3-none-any.whl (28 kB)
Downloading jupyter_server-2.13.0-py3-none-any.whl (383 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 383.2/383.2 kB 3.3 MB/s eta 0:00:00
Downloading nbconvert-7.16.3-py3-none-any.whl (257 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 257.4/257.4 kB 3.0 MB/s eta 0:00:00
Downloading Jinja2-3.1.3-py3-none-any.whl (133 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 133.2/133.2 kB 2.7 MB/s eta 0:00:00
Downloading nbformat-5.10.3-py3-none-any.whl (78 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 78.4/78.4 kB 3.0 MB/s eta 0:00:00
Downloading nest_asyncio-1.6.0-py3-none-any.whl (5.2 kB)
Downloading notebook_shim-0.2.4-py3-none-any.whl (13 kB)
Downloading patsy-0.5.6-py2.py3-none-any.whl (233 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 233.9/233.9 kB 3.1 MB/s eta 0:00:00
Downloading pyzmq-25.1.2-cp310-cp310-macosx_10_15_universal2.whl (1.9 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.9/1.9 MB 3.4 MB/s eta 0:00:00
Using cached Send2Trash-1.8.2-py3-none-any.whl (18 kB)
Downloading terminado-0.18.1-py3-none-any.whl (14 kB)
Downloading tornado-6.4-cp38-abi3-macosx_10_9_universal2.whl (433 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 433.1/433.1 kB 3.2 MB/s eta 0:00:00
Downloading traitlets-5.14.2-py3-none-any.whl (85 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 85.4/85.4 kB 3.4 MB/s eta 0:00:00
Using cached argon2_cffi-23.1.0-py3-none-any.whl (15 kB)
Downloading ipykernel-6.29.3-py3-none-any.whl (117 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 117.1/117.1 kB 2.5 MB/s eta 0:00:00
Using cached ipython_genutils-0.2.0-py2.py3-none-any.whl (26 kB)
Downloading ipywidgets-8.1.2-py3-none-any.whl (139 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 139.4/139.4 kB 2.9 MB/s eta 0:00:00
Using cached jupyter_console-6.6.3-py3-none-any.whl (24 kB)
Downloading notebook-7.1.2-py3-none-any.whl (5.0 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 5.0/5.0 MB 3.4 MB/s eta 0:00:00
Downloading prometheus_client-0.20.0-py3-none-any.whl (54 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 54.5/54.5 kB 3.5 MB/s eta 0:00:00
Using cached py_cpuinfo-9.0.0-py3-none-any.whl (22 kB)
Downloading qtconsole-5.5.1-py3-none-any.whl (123 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 123.4/123.4 kB 3.1 MB/s eta 0:00:00
Using cached webencodings-0.5.1-py2.py3-none-any.whl (11 kB)
Downloading anyio-4.3.0-py3-none-any.whl (85 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 85.6/85.6 kB 3.0 MB/s eta 0:00:00
Using cached bleach-6.1.0-py3-none-any.whl (162 kB)
Downloading comm-0.2.2-py3-none-any.whl (7.2 kB)
Downloading debugpy-1.8.1-py2.py3-none-any.whl (4.8 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 4.8/4.8 MB 3.4 MB/s eta 0:00:00
Downloading ipython-8.22.2-py3-none-any.whl (811 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 812.0/812.0 kB 3.3 MB/s eta 0:00:00
Downloading jsonschema-4.21.1-py3-none-any.whl (85 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 85.5/85.5 kB 3.1 MB/s eta 0:00:00
Downloading jupyter_events-0.10.0-py3-none-any.whl (18 kB)
Downloading jupyterlab-4.1.5-py3-none-any.whl (11.4 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 11.4/11.4 MB 3.4 MB/s eta 0:00:00
Downloading jupyterlab_server-2.25.4-py3-none-any.whl (58 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 59.0/59.0 kB 2.5 MB/s eta 0:00:00
Downloading jupyterlab_widgets-3.0.10-py3-none-any.whl (215 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 215.0/215.0 kB 3.3 MB/s eta 0:00:00
Downloading MarkupSafe-2.1.5-cp310-cp310-macosx_10_9_universal2.whl (18 kB)
Using cached matplotlib_inline-0.1.6-py3-none-any.whl (9.4 kB)
Using cached mistune-3.0.2-py3-none-any.whl (47 kB)
Downloading nbclient-0.10.0-py3-none-any.whl (25 kB)
Using cached ndindex-1.8-py3-none-any.whl (91 kB)
Downloading pandocfilters-1.5.1-py2.py3-none-any.whl (8.7 kB)
Downloading platformdirs-4.2.0-py3-none-any.whl (17 kB)
Downloading prompt_toolkit-3.0.43-py3-none-any.whl (386 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 386.1/386.1 kB 3.1 MB/s eta 0:00:00
Downloading pygments-2.17.2-py3-none-any.whl (1.2 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.2/1.2 MB 3.3 MB/s eta 0:00:00
Downloading QtPy-2.4.1-py3-none-any.whl (93 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 93.5/93.5 kB 3.1 MB/s eta 0:00:00
Downloading widgetsnbextension-4.0.10-py3-none-any.whl (2.3 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.3/2.3 MB 3.4 MB/s eta 0:00:00
Downloading appnope-0.1.4-py2.py3-none-any.whl (4.3 kB)
Using cached argon2_cffi_bindings-21.2.0-cp38-abi3-macosx_10_9_universal2.whl (53 kB)
Downloading beautifulsoup4-4.12.3-py3-none-any.whl (147 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 147.9/147.9 kB 3.0 MB/s eta 0:00:00
Using cached defusedxml-0.7.1-py2.py3-none-any.whl (25 kB)
Downloading fastjsonschema-2.19.1-py3-none-any.whl (23 kB)
Downloading jupyter_server_terminals-0.5.3-py3-none-any.whl (13 kB)
Downloading jupyterlab_pygments-0.3.0-py3-none-any.whl (15 kB)
Using cached msgpack-1.0.8-cp310-cp310-macosx_11_0_arm64.whl (84 kB)
Downloading overrides-7.7.0-py3-none-any.whl (17 kB)
Using cached psutil-5.9.8-cp38-abi3-macosx_11_0_arm64.whl (249 kB)
Using cached ptyprocess-0.7.0-py2.py3-none-any.whl (13 kB)
Using cached tinycss2-1.2.1-py3-none-any.whl (21 kB)
Downloading websocket_client-1.7.0-py3-none-any.whl (58 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 58.5/58.5 kB 3.4 MB/s eta 0:00:00
Using cached async_lru-2.0.4-py3-none-any.whl (6.1 kB)
Downloading attrs-23.2.0-py3-none-any.whl (60 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 60.8/60.8 kB 3.0 MB/s eta 0:00:00
Downloading Babel-2.14.0-py3-none-any.whl (11.0 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 11.0/11.0 MB 3.1 MB/s eta 0:00:00
Downloading cffi-1.16.0-cp310-cp310-macosx_11_0_arm64.whl (176 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 176.8/176.8 kB 3.0 MB/s eta 0:00:00
Downloading exceptiongroup-1.2.0-py3-none-any.whl (16 kB)
Downloading httpx-0.27.0-py3-none-any.whl (75 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 75.6/75.6 kB 3.0 MB/s eta 0:00:00
Downloading httpcore-1.0.4-py3-none-any.whl (77 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 77.8/77.8 kB 3.5 MB/s eta 0:00:00
Downloading idna-3.6-py3-none-any.whl (61 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 61.6/61.6 kB 2.8 MB/s eta 0:00:00
Using cached jedi-0.19.1-py2.py3-none-any.whl (1.6 MB)
Downloading json5-0.9.24-py3-none-any.whl (30 kB)
Downloading jsonschema_specifications-2023.12.1-py3-none-any.whl (18 kB)
Downloading jupyter_lsp-2.2.4-py3-none-any.whl (69 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 69.1/69.1 kB 2.6 MB/s eta 0:00:00
Downloading pexpect-4.9.0-py2.py3-none-any.whl (63 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 63.8/63.8 kB 2.7 MB/s eta 0:00:00
Using cached python_json_logger-2.0.7-py3-none-any.whl (8.1 kB)
Downloading PyYAML-6.0.1-cp310-cp310-macosx_11_0_arm64.whl (169 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 169.3/169.3 kB 3.1 MB/s eta 0:00:00
Downloading referencing-0.34.0-py3-none-any.whl (26 kB)
Using cached requests-2.31.0-py3-none-any.whl (62 kB)
Using cached rfc3986_validator-0.1.1-py2.py3-none-any.whl (4.2 kB)
Downloading rpds_py-0.18.0-cp310-cp310-macosx_11_0_arm64.whl (330 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 330.7/330.7 kB 3.2 MB/s eta 0:00:00
Using cached sniffio-1.3.1-py3-none-any.whl (10 kB)
Using cached soupsieve-2.5-py3-none-any.whl (36 kB)
Using cached decorator-5.1.1-py3-none-any.whl (9.1 kB)
Using cached rfc3339_validator-0.1.4-py2.py3-none-any.whl (3.5 kB)
Using cached stack_data-0.6.3-py3-none-any.whl (24 kB)
Using cached tomli-2.0.1-py3-none-any.whl (12 kB)
Downloading wcwidth-0.2.13-py2.py3-none-any.whl (34 kB)
Downloading asttokens-2.4.1-py2.py3-none-any.whl (27 kB)
Using cached certifi-2024.2.2-py3-none-any.whl (163 kB)
Downloading charset_normalizer-3.3.2-cp310-cp310-macosx_11_0_arm64.whl (120 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 120.4/120.4 kB 2.8 MB/s eta 0:00:00
Downloading executing-2.0.1-py2.py3-none-any.whl (24 kB)
Using cached jsonpointer-2.4-py2.py3-none-any.whl (7.8 kB)
Using cached parso-0.8.3-py2.py3-none-any.whl (100 kB)
Using cached urllib3-2.2.1-py3-none-any.whl (121 kB)
Using cached webcolors-1.13-py3-none-any.whl (14 kB)
Using cached fqdn-1.5.1-py3-none-any.whl (9.1 kB)
Using cached isoduration-20.11.0-py3-none-any.whl (11 kB)
Using cached pure_eval-0.2.2-py3-none-any.whl (11 kB)
Using cached pycparser-2.21-py2.py3-none-any.whl (118 kB)
Using cached uri_template-1.3.0-py3-none-any.whl (11 kB)
Using cached arrow-1.3.0-py3-none-any.whl (66 kB)
Downloading h11-0.14.0-py3-none-any.whl (58 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 58.3/58.3 kB 2.7 MB/s eta 0:00:00
Downloading types_python_dateutil-2.9.0.20240316-py3-none-any.whl (9.7 kB)
Building wheels for collected packages: tables, empiricaldist
  Building wheel for tables (pyproject.toml) ... done
  Created wheel for tables: filename=tables-3.9.2-cp310-cp310-macosx_11_0_arm64.whl size=3440032 sha256=9a772f2c820e5055e0371306dfcf6ab47ab0e0639a1cad77cc289257a324c9d3
  Stored in directory: /Users/ngcchk/Library/Caches/pip/wheels/a5/72/b4/27e55a809cb5eeacfbc682f7bac92535bea82518bd4c96c76f
  Building wheel for empiricaldist (pyproject.toml) ... done
  Created wheel for empiricaldist: filename=empiricaldist-0.7.2-py3-none-any.whl size=12205 sha256=d9dac686a174c40f1764920e8ff864ef2d49f1b076e02f23597f81418d1428ae
  Stored in directory: /Users/ngcchk/Library/Caches/pip/wheels/e9/57/8a/15b864f4d5dc20cef626e3a015fec88b19df385ef30a8364cc
Successfully built tables empiricaldist
Installing collected packages: webencodings, wcwidth, py-cpuinfo, pure-eval, ptyprocess, ipython-genutils, fastjsonschema, empiricaldist, xlrd, widgetsnbextension, websocket-client, webcolors, urllib3, uri-template, types-python-dateutil, traitlets, tornado, tomli, tinycss2, soupsieve, sniffio, Send2Trash, rpds-py, rfc3986-validator, rfc3339-validator, qtpy, pyzmq, pyyaml, python-json-logger, pygments, pycparser, psutil, prompt-toolkit, prometheus-client, platformdirs, pexpect, patsy, parso, pandocfilters, overrides, nest-asyncio, ndindex, msgpack, mistune, markupsafe, lxml, jupyterlab-widgets, jupyterlab-pygments, jsonpointer, json5, idna, html5lib, h11, fqdn, executing, exceptiongroup, defusedxml, decorator, debugpy, charset-normalizer, certifi, bleach, babel, attrs, async-lru, asttokens, appnope, terminado, stack-data, requests, referencing, matplotlib-inline, jupyter-core, jinja2, jedi, httpcore, comm, cffi, blosc2, beautifulsoup4, arrow, anyio, tables, statsmodels, seaborn, jupyter-server-terminals, jupyter-client, jsonschema-specifications, isoduration, ipython, httpx, argon2-cffi-bindings, jsonschema, ipywidgets, ipykernel, argon2-cffi, qtconsole, nbformat, jupyter-console, nbclient, jupyter-events, nbconvert, jupyter-server, notebook-shim, jupyterlab-server, jupyter-lsp, nbclassic, jupyterlab, notebook, jupyter
Successfully installed Send2Trash-1.8.2 anyio-4.3.0 appnope-0.1.4 argon2-cffi-23.1.0 argon2-cffi-bindings-21.2.0 arrow-1.3.0 asttokens-2.4.1 async-lru-2.0.4 attrs-23.2.0 babel-2.14.0 beautifulsoup4-4.12.3 bleach-6.1.0 blosc2-2.5.1 certifi-2024.2.2 cffi-1.16.0 charset-normalizer-3.3.2 comm-0.2.2 debugpy-1.8.1 decorator-5.1.1 defusedxml-0.7.1 empiricaldist-0.7.2 exceptiongroup-1.2.0 executing-2.0.1 fastjsonschema-2.19.1 fqdn-1.5.1 h11-0.14.0 html5lib-1.1 httpcore-1.0.4 httpx-0.27.0 idna-3.6 ipykernel-6.29.3 ipython-8.22.2 ipython-genutils-0.2.0 ipywidgets-8.1.2 isoduration-20.11.0 jedi-0.19.1 jinja2-3.1.3 json5-0.9.24 jsonpointer-2.4 jsonschema-4.21.1 jsonschema-specifications-2023.12.1 jupyter-1.0.0 jupyter-client-8.6.1 jupyter-console-6.6.3 jupyter-core-5.7.2 jupyter-events-0.10.0 jupyter-lsp-2.2.4 jupyter-server-2.13.0 jupyter-server-terminals-0.5.3 jupyterlab-4.1.5 jupyterlab-pygments-0.3.0 jupyterlab-server-2.25.4 jupyterlab-widgets-3.0.10 lxml-5.1.0 markupsafe-2.1.5 matplotlib-inline-0.1.6 mistune-3.0.2 msgpack-1.0.8 nbclassic-1.0.0 nbclient-0.10.0 nbconvert-7.16.3 nbformat-5.10.3 ndindex-1.8 nest-asyncio-1.6.0 notebook-7.1.2 notebook-shim-0.2.4 overrides-7.7.0 pandocfilters-1.5.1 parso-0.8.3 patsy-0.5.6 pexpect-4.9.0 platformdirs-4.2.0 prometheus-client-0.20.0 prompt-toolkit-3.0.43 psutil-5.9.8 ptyprocess-0.7.0 pure-eval-0.2.2 py-cpuinfo-9.0.0 pycparser-2.21 pygments-2.17.2 python-json-logger-2.0.7 pyyaml-6.0.1 pyzmq-25.1.2 qtconsole-5.5.1 qtpy-2.4.1 referencing-0.34.0 requests-2.31.0 rfc3339-validator-0.1.4 rfc3986-validator-0.1.1 rpds-py-0.18.0 seaborn-0.13.2 sniffio-1.3.1 soupsieve-2.5 stack-data-0.6.3 statsmodels-0.14.1 tables-3.9.2 terminado-0.18.1 tinycss2-1.2.1 tomli-2.0.1 tornado-6.4 traitlets-5.14.2 types-python-dateutil-2.9.0.20240316 uri-template-1.3.0 urllib3-2.2.1 wcwidth-0.2.13 webcolors-1.13 webencodings-0.5.1 websocket-client-1.7.0 widgetsnbextension-4.0.10 xlrd-2.0.1
(TB2) ngcchk@ngcchk-m2air ThinkBayes2 % python install_test.py
Traceback (most recent call last):
  File "/Users/ngcchk/Documents/Github/ThinkBayes2/install_test.py", line 15, in <module>
    import thinkbayes2
ModuleNotFoundError: No module named 'thinkbayes2'
(TB2) ngcchk@ngcchk-m2air ThinkBayes2 % 


-------------------------------

(TB2) ngcchk@ngcchk-m2air ThinkBayes2 % jupyter notebook 
[W 2024-03-24 14:13:51.801 ServerApp] A `_jupyter_server_extension_points` function was not found in nbclassic. Instead, a `_jupyter_server_extension_paths` function was found and will be used for now. This function name will be deprecated in future releases of Jupyter Server.
[I 2024-03-24 14:13:51.802 ServerApp] jupyter_lsp | extension was successfully linked.
[I 2024-03-24 14:13:51.803 ServerApp] jupyter_server_terminals | extension was successfully linked.
[I 2024-03-24 14:13:51.805 ServerApp] jupyterlab | extension was successfully linked.
[I 2024-03-24 14:13:51.806 ServerApp] nbclassic | extension was successfully linked.
[I 2024-03-24 14:13:51.808 ServerApp] notebook | extension was successfully linked.
[I 2024-03-24 14:13:52.333 ServerApp] notebook_shim | extension was successfully linked.
[I 2024-03-24 14:13:52.363 ServerApp] notebook_shim | extension was successfully loaded.
[I 2024-03-24 14:13:52.364 ServerApp] jupyter_lsp | extension was successfully loaded.
[I 2024-03-24 14:13:52.365 ServerApp] jupyter_server_terminals | extension was successfully loaded.
[I 2024-03-24 14:13:52.367 LabApp] JupyterLab extension loaded from /Users/ngcchk/miniconda3/envs/TB2/lib/python3.10/site-packages/jupyterlab
[I 2024-03-24 14:13:52.367 LabApp] JupyterLab application directory is /Users/ngcchk/miniconda3/envs/TB2/share/jupyter/lab
[I 2024-03-24 14:13:52.367 LabApp] Extension Manager is 'pypi'.
[I 2024-03-24 14:13:52.389 ServerApp] jupyterlab | extension was successfully loaded.

  _   _          _      _
 | | | |_ __  __| |__ _| |_ ___
 | |_| | '_ \/ _` / _` |  _/ -_)
  \___/| .__/\__,_\__,_|\__\___|
       |_|
                                                                           
Read the migration plan to Notebook 7 to learn about the new features and the actions to take if you are using extensions.

https://jupyter-notebook.readthedocs.io/en/latest/migrate_to_notebook7.html

Please note that updating to Notebook 7 might break some of your extensions.

[I 2024-03-24 14:13:52.392 ServerApp] nbclassic | extension was successfully loaded.
[I 2024-03-24 14:13:52.393 ServerApp] notebook | extension was successfully loaded.
[I 2024-03-24 14:13:52.394 ServerApp] Serving notebooks from local directory: /Users/ngcchk/Documents/Github/ThinkBayes2
[I 2024-03-24 14:13:52.394 ServerApp] Jupyter Server 2.13.0 is running at:
[I 2024-03-24 14:13:52.394 ServerApp] http://localhost:8888/tree?token=90d586610ef42473d80bc64c0ac9aca347d3c9be79350d55
[I 2024-03-24 14:13:52.394 ServerApp]     http://127.0.0.1:8888/tree?token=90d586610ef42473d80bc64c0ac9aca347d3c9be79350d55
[I 2024-03-24 14:13:52.394 ServerApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
[C 2024-03-24 14:13:52.400 ServerApp] 
    
    To access the server, open this file in a browser:
        file:///Users/ngcchk/Library/Jupyter/runtime/jpserver-6732-open.html
    Or copy and paste one of these URLs:
        http://localhost:8888/tree?token=90d586610ef42473d80bc64c0ac9aca347d3c9be79350d55
        http://127.0.0.1:8888/tree?token=90d586610ef42473d80bc64c0ac9aca347d3c9be79350d55
[I 2024-03-24 14:13:53.112 ServerApp] Skipped non-installed server(s): bash-language-server, dockerfile-language-server-nodejs, javascript-typescript-langserver, jedi-language-server, julia-language-server, pyright, python-language-server, python-lsp-server, r-languageserver, sql-language-server, texlab, typescript-language-server, unified-language-server, vscode-css-languageserver-bin, vscode-html-languageserver-bin, vscode-json-languageserver-bin, yaml-language-server
[W 2024-03-24 14:14:01.510 ServerApp] Notebook notebooks/chap04.ipynb is not trusted
[W 2024-03-24 14:14:01.844 ServerApp] Notebook notebooks/chap04.ipynb is not trusted
[I 2024-03-24 14:14:02.431 ServerApp] Kernel started: 65a959e8-597b-4f2b-89f3-746aed347d22
[I 2024-03-24 14:14:03.259 ServerApp] Connecting to kernel 65a959e8-597b-4f2b-89f3-746aed347d22.
[I 2024-03-24 14:14:03.260 ServerApp] Connecting to kernel 65a959e8-597b-4f2b-89f3-746aed347d22.
[I 2024-03-24 14:14:03.271 ServerApp] Connecting to kernel 65a959e8-597b-4f2b-89f3-746aed347d22.
[I 2024-03-24 14:14:05.534 ServerApp] Connecting to kernel 65a959e8-597b-4f2b-89f3-746aed347d22.

