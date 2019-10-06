# SPARK
Code for the ISMRM abstract "Scan-specific, Parameter-free Artifact Reduction in K-space (SPARK)". Reproduces Figure 3.

A list of all the packages in the conda environment that the code was written and tested:

Name                    Version                   Build  Channel
_libgcc_mutex             0.1                        main
_tflow_select             2.1.0                       gpu
absl-py                   0.7.1                    py37_0
aniso8601                 7.0.0                    pypi_0    pypi
ansi2html                 1.5.2                    pypi_0    pypi
arrow                     0.14.2                   pypi_0    pypi
asn1crypto                0.24.0                py37_1003    conda-forge
astor                     0.7.1                    py37_0
astroid                   2.2.5                    pypi_0    pypi
attrs                     19.1.0                   py37_1
backcall                  0.1.0                    py37_0
blas                      1.0                         mkl
bleach                    3.1.0                    py37_0
c-ares                    1.15.0               h7b6447c_1
ca-certificates           2019.5.15                     1
cairo                     1.14.12              h8948797_3
certifi                   2019.6.16                py37_1
cffi                      1.12.3           py37h2e261b9_0
chardet                   3.0.4                    pypi_0    pypi
click                     7.0                      pypi_0    pypi
cryptography              2.7              py37h72c5cf5_0    conda-forge
cudatoolkit               10.0.130                      0
cudnn                     7.6.0                cuda10.0_0
cupti                     10.0.130                      0
cycler                    0.10.0                   py37_0
dbus                      1.13.6               h746ee38_0
decorator                 4.4.0                    py37_1
defusedxml                0.6.0                      py_0
entrypoints               0.3                      py37_0
expat                     2.2.6                he6710b0_0
flask                     1.0.3                    pypi_0    pypi
flask-restful             0.3.7                    pypi_0    pypi
fontconfig                2.13.0               h9420a91_0
freetype                  2.9.1                h8a8886c_1
fribidi                   1.0.5                h7b6447c_0
future                    0.17.1                   py37_0
gast                      0.2.2                    py37_0
glib                      2.56.2               hd408876_0
gmp                       6.1.2                h6c8ec71_1
graphite2                 1.3.13               h23475e2_0
graphviz                  2.40.1               h21bd128_2
grpcio                    1.16.1           py37hf8bcb03_1
gst-plugins-base          1.14.0               hbbd80ab_1
gstreamer                 1.14.0               hb453b48_1
h5py                      2.9.0            py37h7918eee_0
harfbuzz                  1.8.8                hffaf4a1_0
hdf5                      1.10.4               hb1b8bf9_0
icu                       58.2                 h9c2bf20_1
idna                      2.8                      pypi_0    pypi
intel-openmp              2019.4                      243
ipykernel                 5.1.1            py37h39e3cac_0
ipython                   7.5.0            py37h39e3cac_0
ipython_genutils          0.2.0                    py37_0
ipywidgets                7.4.2                    py37_0
isort                     4.3.21                   pypi_0    pypi
itsdangerous              1.1.0                    pypi_0    pypi
jedi                      0.13.3                   py37_0
jinja2                    2.10.1                   py37_0
jpeg                      9b                   h024ee3a_2
jsonschema                3.0.1                    py37_0
jupyter                   1.0.0                    py37_7
jupyter_client            5.2.4                    py37_0
jupyter_console           6.0.0                    py37_0
jupyter_contrib_core      0.3.3                      py_2    conda-forge
jupyter_contrib_nbextensions 0.5.1                    py37_0    conda-forge
jupyter_core              4.4.0                    py37_0
jupyter_highlight_selected_word 0.2.0                 py37_1000    conda-forge
jupyter_latex_envs        1.4.4                 py37_1000    conda-forge
jupyter_nbextensions_configurator 0.4.1                    py37_0    conda-forge
jupyterlab                0.35.6                   py37_0    conda-forge
jupyterlab_server         0.2.0                      py_0    conda-forge
jupyterthemes             0.20.0                   pypi_0    pypi
keras-applications        1.0.8                      py_0
keras-base                2.2.4                    py37_0
keras-gpu                 2.2.4                         0
keras-preprocessing       1.1.0                      py_1
kiwisolver                1.1.0            py37he6710b0_0
lazy-object-proxy         1.4.2                    pypi_0    pypi
lesscpy                   0.13.0                   pypi_0    pypi
libedit                   3.1.20181209         hc058e9b_0
libffi                    3.2.1                hd88cf55_4
libgcc-ng                 9.1.0                hdf63c60_0
libgfortran-ng            7.3.0                hdf63c60_0
libpng                    1.6.37               hbc83047_0
libprotobuf               3.8.0                hd408876_0
libsodium                 1.0.16               h1bed415_0
libstdcxx-ng              9.1.0                hdf63c60_0
libtiff                   4.0.10               h2733197_2
libuuid                   1.0.3                h1bed415_2
libxcb                    1.13                 h1bed415_1
libxml2                   2.9.9                he19cac6_0
libxslt                   1.1.32            h4785a14_1002    conda-forge
lxml                      4.3.4            py37h7ec2d77_0    conda-forge
markdown                  3.1.1                    py37_0
markupsafe                1.1.1            py37h7b6447c_0
matplotlib                3.1.0            py37h5429711_0
mccabe                    0.6.1                    pypi_0    pypi
mistune                   0.8.4            py37h7b6447c_0
mkl                       2019.4                      243
mkl_fft                   1.0.12           py37ha843d7b_0
mkl_random                1.0.2            py37hd81dba3_0
mock                      3.0.5                    py37_0
nbconvert                 5.5.0                      py_0
nbformat                  4.4.0                    py37_0
ncurses                   6.1                  he6710b0_1
ninja                     1.9.0            py37hfd86e86_0
notebook                  5.7.8                    py37_0
numpy                     1.16.4           py37h7e9f1db_0
numpy-base                1.16.4           py37hde5b4d6_0
nvgpu                     0.8.0                    pypi_0    pypi
olefile                   0.46                     py37_0
openssl                   1.1.1c               h7b6447c_1
pandas                    0.24.2           py37he6710b0_0
pandoc                    2.2.3.2                       0
pandocfilters             1.4.2                    py37_1
pango                     1.42.4               h049681c_0
parso                     0.4.0                      py_0
pcre                      8.43                 he6710b0_0
pexpect                   4.7.0                    py37_0
pickleshare               0.7.5                    py37_0
pillow                    6.0.0            py37h34e0f95_0
pip                       19.1.1                   py37_0
pixman                    0.38.0               h7b6447c_0
ply                       3.11                     pypi_0    pypi
prometheus_client         0.6.0                    py37_0
prompt_toolkit            2.0.9                    py37_0
protobuf                  3.8.0            py37he6710b0_0
psutil                    5.6.3                    pypi_0    pypi
ptvsd                     4.3.2                    pypi_0    pypi
ptyprocess                0.6.0                    py37_0
pycparser                 2.19                     py37_0
pygments                  2.4.2                      py_0
pylint                    2.3.1                    pypi_0    pypi
pynvml                    8.0.1                    pypi_0    pypi
pyopenssl                 19.0.0                   py37_0    conda-forge
pyparsing                 2.4.0                      py_0
pyqt                      5.9.2            py37h05f1152_2
pyrsistent                0.14.11          py37h7b6447c_0
pysocks                   1.7.0                    py37_0    conda-forge
python                    3.7.3                h0371630_0
python-dateutil           2.8.0                    py37_0
python-graphviz           0.11                     pypi_0    pypi
pytorch                   1.2.0           py3.7_cuda10.0.130_cudnn7.6.2_0    pytorch
pytz                      2019.1                     py_0
pyyaml                    5.1              py37h7b6447c_0
pyzmq                     18.0.0           py37he6710b0_0
qt                        5.9.7                h5867ecd_1
qtconsole                 4.5.1                      py_0
readline                  7.0                  h7b6447c_5
requests                  2.22.0                   py37_0    conda-forge
scipy                     1.2.1            py37h7c811a0_0
send2trash                1.5.0                    py37_0
setuptools                41.0.1                   py37_0
sip                       4.19.8           py37hf484d3e_0
six                       1.12.0                   py37_0
sqlite                    3.28.0               h7b6447c_0
tabulate                  0.8.3                    pypi_0    pypi
tb-nightly                1.15.0a20190818          pypi_0    pypi
tensorboard               1.13.1           py37hf484d3e_0
tensorflow                1.13.1          gpu_py37hc158e3b_0
tensorflow-base           1.13.1          gpu_py37h8d69cac_0
tensorflow-estimator      1.13.0                     py_0
tensorflow-gpu            1.13.1               h0d30ee6_0
termcolor                 1.1.0                    py37_1
terminado                 0.8.2                    py37_0
testpath                  0.4.2                    py37_0
tk                        8.6.8                hbc83047_0
torchfile                 0.1.0                      py_0    conda-forge
torchsummary              1.5.1                    pypi_0    pypi
torchvision               0.4.0                py37_cu100    pytorch
torchviz                  0.0.1                    pypi_0    pypi
tornado                   6.0.2            py37h7b6447c_0
traitlets                 4.3.2                    py37_0
typed-ast                 1.4.0                    pypi_0    pypi
urllib3                   1.25.3                   pypi_0    pypi
visdom                    0.1.8.8                       0    conda-forge
wcwidth                   0.1.7                    py37_0
webencodings              0.5.1                    py37_1
websocket-client          0.56.0                   py37_0    conda-forge
werkzeug                  0.15.4                     py_0
wheel                     0.33.4                   py37_0
widgetsnbextension        3.4.2                    py37_0
wrapt                     1.11.2                   pypi_0    pypi
xz                        5.2.4                h14c3975_4
yaml                      0.1.7                had09818_2
zeromq                    4.3.1                he6710b0_3
zlib                      1.2.11               h7b6447c_3
zstd                      1.3.7                h0b5b093_0


