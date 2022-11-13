
# Experimental Wheels for Python 3.11 for Windows on ARM64

This repository provides experimental binary wheels for open-source extension packages 
for [Python 3.11 for Windows on ARM64](https://www.python.org/downloads/windows/).

The files are experimental (meaning: unofficial, informal, unrecognized, unsupported, 
no warranty, no liability, provided "as is") and made available for testing and 
evaluation purposes.

Most binaries are built from source code found in the Python Package Index or 
the projects' public code repositories.

Refer to the documentation of the individual [packages](#wheels) and 
[libraries](#libraries) for license restrictions and dependencies.

Wheels can be downloaded from the 
[Releases](https://github.com/cgohlke/experimental-cp311-win_arm64.whl/releases) page.

## Release 2022.11.12

### Highlights

- Includes 200 wheels.
- Scipy stack: numpy, scipy, matplotlib, Pandas, h5py, scikit-image, scikit-learn, etc.
- GIS stack: gdal, netcdf4, pyproj, shapely, rasterio, basemap, Fiona, etc.
- Image IO and compression: Pillow, imagecodecs, aicspylibczi, glymur, zfpy, blosc2, cramjam, etc.
- Pymol-open-source.

### Known issues

- The packages and libraries underwent only limited testing.
- Numpy is not linked to OpenBLAS.
- OpenBLAS was built with an alpha version of flang.
- Scipy's Fortran bindings are unstable.
- Jupyter notebooks cannot connect to kernel.
- No GUI, CUDA, numba, napari packages.
- Few libraries do not compile, e.g., AVIF and VTK-m.
- Few compiler crashes during builds.

### Wheels

The following binary wheels are included in the
[release](https://github.com/cgohlke/experimental-cp311-win_arm64.whl/releases):

- [BTrees](https://pypi.org/project/BTrees/)-4.11.1-cp311-cp311-win_arm64.whl
- [Bottleneck](https://pypi.org/project/Bottleneck/)-1.3.5-cp311-cp311-win_arm64.whl
- [Brotli](https://pypi.org/project/Brotli/)-1.0.9-cp311-cp311-win_arm64.whl
- [Cheetah3](https://pypi.org/project/Cheetah3/)-3.2.6.post1-cp311-cp311-win_arm64.whl
- [Cython](https://pypi.org/project/Cython/)-0.29.32-cp311-cp311-win_arm64.whl
- [Fiona](https://pypi.org/project/Fiona/)-1.8.22-cp311-cp311-win_arm64.whl
- [GDAL](https://pypi.org/project/GDAL/)-3.5.3-cp311-cp311-win_arm64.whl
- [Glymur](https://pypi.org/project/Glymur/)-0.12.0-cp311-cp311-win_arm64.whl
- [JCC](https://pypi.org/project/JCC/)-3.13-cp311-cp311-win_arm64.whl
- [JPype1](https://pypi.org/project/JPype1/)-1.4.1-cp311-cp311-win_arm64.whl
- [MarkupSafe](https://pypi.org/project/MarkupSafe/)-2.1.1-cp311-cp311-win_arm64.whl
- [MeshPy](https://pypi.org/project/MeshPy/)-2022.1.3-cp311-cp311-win_arm64.whl
- [OpenEXR](https://pypi.org/project/OpenEXR/)-1.3.9-cp311-cp311-win_arm64.whl
- [Pillow](https://pypi.org/project/Pillow/)-9.3.0-cp311-cp311-win_arm64.whl
- [PyAudio](https://pypi.org/project/PyAudio/)-0.2.12-cp311-cp311-win_arm64.whl
- [PyCifRW](https://pypi.org/project/PyCifRW/)-4.4.3-cp311-cp311-win_arm64.whl
- [PyGreSQL](https://pypi.org/project/PyGreSQL/)-5.2.4-cp311-cp311-win_arm64.whl
- [PyICU](https://pypi.org/project/PyICU/)-2.10.2-cp311-cp311-win_arm64.whl
- [PyMCubes](https://pypi.org/project/PyMCubes/)-0.1.2-cp311-cp311-win_arm64.whl
- [PyNaCl](https://pypi.org/project/PyNaCl/)-1.5.0-cp311-cp311-win_arm64.whl
- [PyOpenGL](https://pypi.org/project/PyOpenGL/)-3.1.6-cp311-cp311-win_arm64.whl
- [PyOpenGL_accelerate](https://pypi.org/project/PyOpenGL_accelerate/)-3.1.6-cp311-cp311-win_arm64.whl
- [PyTurboJPEG](https://pypi.org/project/PyTurboJPEG/)-1.7.0-cp311-cp311-win_arm64.whl
- [PyWavelets](https://pypi.org/project/PyWavelets/)-1.4.1-cp311-cp311-win_arm64.whl
- [PyYAML](https://pypi.org/project/PyYAML/)-6.0-cp311-cp311-win_arm64.whl
- [Pycluster](https://pypi.org/project/Pycluster/)-1.59-cp311-cp311-win_arm64.whl
- [Rtree](https://pypi.org/project/Rtree/)-1.0.1-cp311-cp311-win_arm64.whl
- [SQLAlchemy](https://pypi.org/project/SQLAlchemy/)-1.4.44-cp311-cp311-win_arm64.whl
- [SciPy](https://pypi.org/project/SciPy/)-1.9.3-cp311-cp311-win_arm64.whl
- [Shapely](https://pypi.org/project/Shapely/)-1.8.5.post1-cp311-cp311-win_arm64.whl
- [SimpleParse](https://pypi.org/project/SimpleParse/)-2.2.3-cp311-cp311-win_arm64.whl
- [TA_Lib](https://pypi.org/project/TA_Lib/)-0.4.25-cp311-cp311-win_arm64.whl
- [VideoCapture](https://videocapture.sourceforge.net/)-0.9.5-cp311-cp311-win_arm64.whl
- [aggdraw](https://pypi.org/project/aggdraw/)-1.3.15-cp311-cp311-win_arm64.whl
- [ahds](https://pypi.org/project/ahds/)-0.2.4-cp311-cp311-win_arm64.whl
- [aicspylibczi](https://pypi.org/project/aicspylibczi/)-3.0.5-cp311-cp311-win_arm64.whl
- [aiohttp](https://pypi.org/project/aiohttp/)-3.8.3-cp311-cp311-win_arm64.whl
- [akima](https://pypi.org/project/akima/)-2022.9.12-cp311-cp311-win_arm64.whl
- [apsw](https://pypi.org/project/apsw/)-3.39.4.0-cp311-cp311-win_arm64.whl
- [argon2_cffi_bindings](https://pypi.org/project/argon2_cffi_bindings/)-21.2.0-cp311-abi3-win_arm64.whl
- [astropy](https://pypi.org/project/astropy/)-5.1.1-cp311-cp311-win_arm64.whl
- [atom](https://pypi.org/project/atom/)-0.8.2-cp311-cp311-win_arm64.whl
- [autobahn](https://pypi.org/project/autobahn/)-22.7.1-cp311-cp311-win_arm64.whl
- [basemap](https://pypi.org/project/basemap/)-1.3.6-cp311-cp311-win_arm64.whl
- [bcrypt](https://pypi.org/project/bcrypt/)-4.0.1-cp311-cp311-win_arm64.whl
- [bfloat16](https://pypi.org/project/bfloat16/)-1.1-cp311-cp311-win_arm64.whl
- [bintrees](https://pypi.org/project/bintrees/)-2.2.0-cp311-cp311-win_arm64.whl
- [biopython](https://pypi.org/project/biopython/)-1.79-cp311-cp311-win_arm64.whl
- [bitarray](https://pypi.org/project/bitarray/)-2.6.0-cp311-cp311-win_arm64.whl
- [bitshuffle](https://pypi.org/project/bitshuffle/)-0.4.2-cp311-cp311-win_arm64.whl
- [blis](https://pypi.org/project/blis/)-0.9.1-cp311-cp311-win_arm64.whl
- [blosc2](https://pypi.org/project/blosc2/)-0.5.2-cp311-cp311-win_arm64.whl
- [blosc](https://pypi.org/project/blosc/)-1.10.6-cp311-cp311-win_arm64.whl
- [bsddb3](https://pypi.org/project/bsddb3/)-6.2.9-cp311-cp311-win_arm64.whl
- [bsdiff4](https://pypi.org/project/bsdiff4/)-1.2.2-cp311-cp311-win_arm64.whl
- [cairocffi](https://pypi.org/project/cairocffi/)-1.4.0-cp311-cp311-win_arm64.whl
- [caterva](https://pypi.org/project/caterva/)-0.7.3-cp311-cp311-win_arm64.whl
- [centrosome](https://pypi.org/project/centrosome/)-1.2.1-cp311-cp311-win_arm64.whl
- [cf_units](https://pypi.org/project/cf_units/)-3.1.1-cp311-cp311-win_arm64.whl
- [cffi](https://pypi.org/project/cffi/)-1.15.1-cp311-cp311-win_arm64.whl
- [cftime](https://pypi.org/project/cftime/)-1.6.2-cp311-cp311-win_arm64.whl
- [chaco](https://pypi.org/project/chaco/)-5.1.0-cp311-cp311-win_arm64.whl
- [chebyfit](https://pypi.org/project/chebyfit/)-2022.9.29-cp311-cp311-win_arm64.whl
- [contourpy](https://pypi.org/project/contourpy/)-1.0.6-cp311-cp311-win_arm64.whl
- [coverage](https://pypi.org/project/coverage/)-6.5.0-cp311-cp311-win_arm64.whl
- [cramjam](https://pypi.org/project/cramjam/)-2.6.2-cp311-none-win_arm64.whl
- [cryptography](https://pypi.org/project/cryptography/)-38.0.3-cp311-cp311-win_arm64.whl
- [curses](https://github.com/python/cpython/issues/47138)-2.2.1-cp311-cp311-win_arm64.whl
- [discretize](https://pypi.org/project/discretize/)-0.8.2-cp311-cp311-win_arm64.whl
- [dulwich](https://pypi.org/project/dulwich/)-0.20.50-cp311-cp311-win_arm64.whl
- [elasticdeform](https://pypi.org/project/elasticdeform/)-0.5.0-cp311-cp311-win_arm64.whl
- [enable](https://pypi.org/project/enable/)-5.3.1-cp311-cp311-win_arm64.whl
- [enaml](https://pypi.org/project/enaml/)-0.15.2-cp311-cp311-win_arm64.whl
- [ephem](https://pypi.org/project/ephem/)-4.1.3-cp311-cp311-win_arm64.whl
- [fabio](https://pypi.org/project/fabio/)-0.14.0-cp311-cp311-win_arm64.whl
- [fast_histogram](https://pypi.org/project/fast_histogram/)-0.11-cp36-abi3-win_arm64.whl
- [fastparquet](https://pypi.org/project/fastparquet/)-0.8.3-cp311-cp311-win_arm64.whl
- [fastrlock](https://pypi.org/project/fastrlock/)-0.8.1-cp311-cp311-win_arm64.whl
- [fdint](https://pypi.org/project/fdint/)-2.0.2-cp311-cp311-win_arm64.whl
- [fpzip](https://pypi.org/project/fpzip/)-1.2.0-cp311-cp311-win_arm64.whl
- [freetype_py](https://pypi.org/project/freetype_py/)-2.3.0-cp311-cp311-win_arm64.whl
- [frozenlist](https://pypi.org/project/frozenlist/)-1.3.3-cp311-cp311-win_arm64.whl
- [gevent](https://pypi.org/project/gevent/)-22.10.2-cp311-cp311-win_arm64.whl
- [glcontext](https://pypi.org/project/glcontext/)-2.3.7-cp311-cp311-win_arm64.whl
- [glfw](https://pypi.org/project/glfw/)-2.5.5-cp311-cp311-win_arm64.whl
- [glumpy](https://pypi.org/project/glumpy/)-1.2.0-cp311-cp311-win_arm64.whl
- [greenlet](https://pypi.org/project/greenlet/)-2.0.1-cp311-cp311-win_arm64.whl
- [h5py](https://pypi.org/project/h5py/)-3.7.0-cp311-cp311-win_arm64.whl
- [imagecodecs](https://pypi.org/project/imagecodecs/)-2022.9.26-cp311-cp311-win_arm64.whl
- [imread](https://pypi.org/project/imread/)-0.7.4-cp311-cp311-win_arm64.whl
- [indexed_gzip](https://pypi.org/project/indexed_gzip/)-1.7.0-cp311-cp311-win_arm64.whl
- [intbitset](https://pypi.org/project/intbitset/)-3.0.1-cp311-cp311-win_arm64.whl
- [jellyfish](https://pypi.org/project/jellyfish/)-0.9.0-cp311-cp311-win_arm64.whl
- [jsonobject](https://pypi.org/project/jsonobject/)-2.1.0-cp311-cp311-win_arm64.whl
- [kiwisolver](https://pypi.org/project/kiwisolver/)-1.4.4-cp311-cp311-win_arm64.whl
- [lfdfiles](https://pypi.org/project/lfdfiles/)-2022.9.29-cp311-cp311-win_arm64.whl
- [line_profiler](https://pypi.org/project/line_profiler/)-4.0.0-cp311-cp311-win_arm64.whl
- [lmdb](https://pypi.org/project/lmdb/)-1.3.0-cp311-cp311-win_arm64.whl
- [lxml](https://pypi.org/project/lxml/)-4.9.1-cp311-cp311-win_arm64.whl
- [lz4](https://pypi.org/project/lz4/)-4.0.2-cp311-cp311-win_arm64.whl
- [mahotas](https://pypi.org/project/mahotas/)-1.4.13-cp311-cp311-win_arm64.whl
- [marisa_trie](https://pypi.org/project/marisa_trie/)-0.7.8-cp311-cp311-win_arm64.whl
- [matplotlib](https://pypi.org/project/matplotlib/)-3.6.2-cp311-cp311-win_arm64.whl
- [maturin](https://pypi.org/project/maturin/)-0.13.7-cp311-cp311-win_arm64.whl
- [mercurial](https://pypi.org/project/mercurial/)-6.2.3-cp311-cp311-win_arm64.whl
- [moderngl](https://pypi.org/project/moderngl/)-5.7.2-cp311-cp311-win_arm64.whl
- [mplcairo](https://pypi.org/project/mplcairo/)-0.5-cp311-cp311-win_arm64.whl
- [msgpack](https://pypi.org/project/msgpack/)-1.0.4-cp311-cp311-win_arm64.whl
- [multidict](https://pypi.org/project/multidict/)-6.0.2-cp311-cp311-win_arm64.whl
- [naturalneighbor](https://pypi.org/project/naturalneighbor/)-0.2.1-cp311-cp311-win_arm64.whl
- [ndimage](https://github.com/scipy/scipy/tree/main/scipy/ndimage)-1.3.1-cp311-cp311-win_arm64.whl
- [ndindex](https://pypi.org/project/ndindex/)-1.6-cp311-cp311-win_arm64.whl
- [netCDF4](https://pypi.org/project/netCDF4/)-1.6.1-cp311-cp311-win_arm64.whl
- [netifaces](https://pypi.org/project/netifaces/)-0.11.0-cp311-cp311-win_arm64.whl
- [noise](https://pypi.org/project/noise/)-1.2.3-cp311-cp311-win_arm64.whl
- [numcodecs](https://pypi.org/project/numcodecs/)-0.10.2-cp311-cp311-win_arm64.whl
- [numexpr](https://pypi.org/project/numexpr/)-2.8.4-cp311-cp311-win_arm64.whl
- [numpy](https://pypi.org/project/numpy/)-1.23.4-cp311-cp311-win_arm64.whl
- [numpy_quaternion](https://pypi.org/project/numpy_quaternion/)-2022.4.2-cp311-cp311-win_arm64.whl
- [numpy_stl](https://pypi.org/project/numpy_stl/)-2.17.1-cp311-cp311-win_arm64.whl
- [opencv_python](https://pypi.org/project/opencv_python/)-4.6.0-cp311-cp311-win_arm64.whl
- [orjson](https://pypi.org/project/orjson/)-3.8.1-cp311-none-win_arm64.whl
- [pandas](https://pypi.org/project/pandas/)-1.5.1-cp311-cp311-win_arm64.whl
- [persistent](https://pypi.org/project/persistent/)-4.9.2-cp311-cp311-win_arm64.whl
- [protobuf](https://pypi.org/project/protobuf/)-4.21.9-cp311-cp311-win_arm64.whl
- [psf](https://pypi.org/project/psf/)-2022.9.26-cp311-cp311-win_arm64.whl
- [psutil](https://pypi.org/project/psutil/)-5.9.4-cp311-abi3-win_arm64.whl
- [psycopg2](https://pypi.org/project/psycopg2/)-2.9.5-cp311-cp311-win_arm64.whl
- [psygnal](https://pypi.org/project/psygnal/)-0.6.0.post0-cp311-cp311-win_arm64.whl
- [pyRXP](https://pypi.org/project/pyRXP/)-3.0.1-cp311-cp311-win_arm64.whl
- [pyamg](https://pypi.org/project/pyamg/)-4.2.3-cp311-cp311-win_arm64.whl
- [pyasn](https://pypi.org/project/pyasn/)-1.6.1-cp311-cp311-win_arm64.whl
- [pycairo](https://pypi.org/project/pycairo/)-1.21.0-cp311-cp311-win_arm64.whl
- [pycares](https://pypi.org/project/pycares/)-4.2.2-cp311-cp311-win_arm64.whl
- [pycosat](https://pypi.org/project/pycosat/)-0.6.4-cp311-cp311-win_arm64.whl
- [pycryptodome](https://pypi.org/project/pycryptodome/)-3.15.0-cp35-abi3-win_arm64.whl
- [pycryptodomex](https://pypi.org/project/pycryptodomex/)-3.15.0-cp35-abi3-win_arm64.whl
- [pycurl](https://pypi.org/project/pycurl/)-7.45.1-cp311-cp311-win_arm64.whl
- [pydantic](https://pypi.org/project/pydantic/)-1.10.2-cp311-cp311-win_arm64.whl
- [pyeda](https://pypi.org/project/pyeda/)-0.28.0-cp311-cp311-win_arm64.whl
- [pyerfa](https://pypi.org/project/pyerfa/)-2.0.0.1-cp311-cp311-win_arm64.whl
- [pygeos](https://pypi.org/project/pygeos/)-0.13.0-cp311-cp311-win_arm64.whl
- [pygit2](https://pypi.org/project/pygit2/)-1.11.1-cp311-cp311-win_arm64.whl
- [pyhdf](https://pypi.org/project/pyhdf/)-0.10.5-cp311-cp311-win_arm64.whl
- [pyjnius](https://pypi.org/project/pyjnius/)-1.4.2-cp311-cp311-win_arm64.whl
- [pylibjpeg_libjpeg](https://pypi.org/project/pylibjpeg_libjpeg/)-1.3.2-cp311-cp311-win_arm64.whl
- [pylibjpeg_openjpeg](https://pypi.org/project/pylibjpeg_openjpeg/)-1.2.1-cp311-cp311-win_arm64.whl
- [pylibjpeg_rle](https://pypi.org/project/pylibjpeg_rle/)-1.3.0-cp311-cp311-win_arm64.whl
- [pymatgen](https://pypi.org/project/pymatgen/)-2022.11.7-cp311-cp311-win_arm64.whl
- [pymol](https://github.com/schrodinger/pymol-open-source)-2.6.0a0-cp311-cp311-win_arm64.whl
- [pymongo](https://pypi.org/project/pymongo/)-4.3.2-cp311-cp311-win_arm64.whl
- [pymssql](https://pypi.org/project/pymssql/)-2.2.5-cp311-cp311-win_arm64.whl
- [pyodbc](https://pypi.org/project/pyodbc/)-4.0.34-cp311-cp311-win_arm64.whl
- [pyopencl](https://pypi.org/project/pyopencl/)-2022.2.4-cp311-cp311-win_arm64.whl
- [pyproj](https://pypi.org/project/pyproj/)-3.4.0-cp311-cp311-win_arm64.whl
- [pyreadstat](https://pypi.org/project/pyreadstat/)-1.2.0-cp311-cp311-win_arm64.whl
- [pyrsistent](https://pypi.org/project/pyrsistent/)-0.19.2-cp311-cp311-win_arm64.whl
- [pystackreg](https://pypi.org/project/pystackreg/)-0.2.7-cp311-cp311-win_arm64.whl
- [python_javabridge](https://pypi.org/project/python_javabridge/)-4.0.3-cp311-cp311-win_arm64.whl
- [python_ldap](https://pypi.org/project/python_ldap/)-3.4.3-cp311-cp311-win_arm64.whl
- [python_lzf](https://pypi.org/project/python_lzf/)-0.2.4-cp311-cp311-win_arm64.whl
- [python_rapidjson](https://pypi.org/project/python_rapidjson/)-1.9-cp311-cp311-win_arm64.whl
- [python_snappy](https://pypi.org/project/python_snappy/)-0.6.1-cp311-cp311-win_arm64.whl
- [pywin32](https://pypi.org/project/pywin32/)-305-cp311-cp311-win_arm64.whl
- [pywinpty](https://pypi.org/project/pywinpty/)-2.0.9-cp311-none-win_arm64.whl
- [pyzmq](https://pypi.org/project/pyzmq/)-24.0.1-cp311-cp311-win_arm64.whl
- [rasterio](https://pypi.org/project/rasterio/)-1.3.3-cp311-cp311-win_arm64.whl
- [recordclass](https://pypi.org/project/recordclass/)-0.18.0.1-cp311-cp311-win_arm64.whl
- [regex](https://pypi.org/project/regex/)-2022.10.31-cp311-cp311-win_arm64.whl
- [reportlab](https://pypi.org/project/reportlab/)-3.6.12-cp311-cp311-win_arm64.whl
- [rtmidi_python](https://pypi.org/project/rtmidi_python/)-0.2.2-cp311-cp311-win_arm64.whl
- [ruamel.yaml.clib](https://pypi.org/project/ruamel.yaml.clib/)-0.2.7-cp311-cp311-win_arm64.whl
- [scikit_image](https://pypi.org/project/scikit_image/)-0.19.3-cp311-cp311-win_arm64.whl
- [scikit_learn](https://pypi.org/project/scikit_learn/)-1.1.3-cp311-cp311-win_arm64.whl
- [scikits.vectorplot](https://pypi.org/project/scikits.vectorplot/)-0.1.1-cp311-cp311-win_arm64.whl
- [setproctitle](https://pypi.org/project/setproctitle/)-1.3.2-cp311-cp311-win_arm64.whl
- [sfepy](https://pypi.org/project/sfepy/)-2022.3-cp311-cp311-win_arm64.whl
- [simplejson](https://pypi.org/project/simplejson/)-3.17.6-cp311-cp311-win_arm64.whl
- [spectrum](https://pypi.org/project/spectrum/)-0.8.1-cp311-cp311-win_arm64.whl
- [spglib](https://pypi.org/project/spglib/)-2.0.2-cp311-cp311-win_arm64.whl
- [statsmodels](https://pypi.org/project/statsmodels/)-0.13.5-cp311-cp311-win_arm64.whl
- [tables](https://pypi.org/project/tables/)-3.7.0-cp311-cp311-win_arm64.whl
- [thrift](https://pypi.org/project/thrift/)-0.16.0-cp311-cp311-win_arm64.whl
- [tornado](https://pypi.org/project/tornado/)-6.2-cp37-abi3-win_arm64.whl
- [traits](https://pypi.org/project/traits/)-6.4.1-cp311-cp311-win_arm64.whl
- [transformations](https://pypi.org/project/transformations/)-2022.9.26-cp311-cp311-win_arm64.whl
- [triangle](https://pypi.org/project/triangle/)-20220202-cp311-cp311-win_arm64.whl
- [udunits2](https://github.com/Unidata/UDUNITS-2)-2.2.28-cp311-cp311-win_arm64.whl
- [vidsrc](https://pypi.org/project/vidsrc/)-2022.9.28-cp311-cp311-win_arm64.whl
- [vispy](https://pypi.org/project/vispy/)-0.12.0-cp311-cp311-win_arm64.whl
- [win_arm64_runtime_dlls](https://github.com/cgohlke/experimental-cp311-win_arm64.whl)-2022.11.12+experimental-cp311-cp311-win_arm64.whl
- [wordcloud](https://pypi.org/project/wordcloud/)-1.8.2.2-cp311-cp311-win_arm64.whl
- [wrapt](https://pypi.org/project/wrapt/)-1.14.1-cp311-cp311-win_arm64.whl
- [xxhash](https://pypi.org/project/xxhash/)-3.1.0-cp311-cp311-win_arm64.whl
- [yarl](https://pypi.org/project/yarl/)-1.8.1-cp311-cp311-win_arm64.whl
- [yt](https://pypi.org/project/yt/)-4.1.1-cp311-cp311-win_arm64.whl
- [zfpy](https://pypi.org/project/zfpy/)-1.0.0-cp311-cp311-win_arm64.whl
- [zodbpickle](https://pypi.org/project/zodbpickle/)-2.5-cp311-cp311-win_arm64.whl
- [zope.interface](https://pypi.org/project/zope.interface/)-5.5.1-cp311-cp311-win_arm64.whl
- [zopflipy](https://pypi.org/project/zopflipy/)-1.8-cp311-cp311-win_arm64.whl
- [zstd](https://pypi.org/project/zstd/)-1.5.2.6-cp311-cp311-win_arm64.whl

### Libraries

The wheels include the following statically or dynamically linked libraries:

- [berkeleydb](https://github.com/berkeleydb/libdb/releases/download/v5.3.28/db-5.3.28.tar.gz)-5.3.28
- [boost](https://boostorg.jfrog.io/artifactory/main/release/1.80.0/source/boost_1_80_0.zip)-1_80_0
- [brotli](https://github.com/google/brotli)-v1.0.9
- [brunsli](https://github.com/google/brunsli)-v0.1
- [bzip2](https://sourceware.org/pub/bzip2/bzip2-1.0.8.tar.gz)-1.0.8
- [c-ares](https://c-ares.org/download/c-ares-1.18.1.tar.gz)-1.18.1
- [c-blosc2](https://github.com/Blosc/c-blosc2)-2.4.3
- [c-blosc](https://github.com/Blosc/c-blosc)-1.21.1
- [cairo](https://www.cairographics.org/releases/cairo-1.16.0.tar.xz)-1.16.0
- [cfitsio](http://heasarc.gsfc.nasa.gov/FTP/software/fitsio/c/cfitsio-3.49.tar.gz)-3.49
- [charls](https://github.com/team-charls/charls)-2.3.4
- [curl](https://curl.se/download/curl-7.86.0.tar.gz)-7.86.0
- [expat](https://github.com/libexpat/libexpat/releases/download/R_2_4_9/expat-2.4.9.tar.gz)-2.4.9
- [freeglut](https://github.com/FreeGLUTProject/freeglut)-3.4.0
- [freetds](https://www.freetds.org/files/stable/freetds-1.3.13.tar.gz)-1.3.13
- [freetype](https://download.savannah.gnu.org/releases/freetype/freetype-2.12.1.tar.gz)-2.12.1
- [freexl](https://www.gaia-gis.it/gaia-sins/freexl-1.0.6.tar.gz)-1.0.6
- [gdal](https://github.com/OSGeo/gdal)-1.3.0
- [geos](https://download.osgeo.org/geos/geos-3.11.0.tar.bz2)-3.11.0
- [giflib](https://sourceforge.net/projects/giflib/files/giflib-5.2.1.tar.gz)-5.2.1
- [gle](https://sourceforge.net/projects/gle/files/gle/gle-3.1.0/gle-3.1.0.tar.gz)-3.1.0
- [glew](https://github.com/nigels-com/glew/releases/download/glew-2.2.0/glew-2.2.0.tgz)-2.2.0
- [harfbuzz](https://github.com/harfbuzz/harfbuzz)-5.3.1
- [hdf4](https://github.com/HDFGroup/hdf4)-4.2.15
- [hdf5](https://support.hdfgroup.org/ftp/HDF5/releases/hdf5-1.10/hdf5-1.10.9/src/hdf5-1.10.9.tar.gz)-1.10.9
- [icu](https://github.com/unicode-org/icu/releases/download/release-72-1/icu4c-72_1-src.zip)-72.1
- [imath](https://github.com/AcademySoftwareFoundation/Imath)-3.1.5
- [jasper](https://github.com/jasper-software/jasper)-4.0.0
- [json-c](https://github.com/json-c/json-c)-0.16
- [jxrlib](http://deb.debian.org/debian/pool/main/j/jxrlib/jxrlib_1.1.orig.tar.gz)-1.1
- [lcms2](https://github.com/mm2/Little-CMS)-2.14
- [lerc](https://github.com/Esri/lerc)-4.0.0
- [libaec](https://gitlab.dkrz.de/k202009/libaec)-1.0.6
- [libdeflate](https://github.com/ebiggers/libdeflate)-1.14
- [libgeotiff](https://github.com/OSGeo/libgeotiff/releases/download/1.7.1/libgeotiff-1.7.1.tar.gz)-1.7.1
- [libgit2](https://github.com/libgit2/libgit2)-1.5.0
- [libjpeg-turbo](https://github.com/libjpeg-turbo/libjpeg-turbo)-2.1.4
- [libjxl](https://github.com/libjxl/libjxl)-0.7.0
- [libkml](https://github.com/libkml/libkml)-1.3.0
- [liblzf](http://dist.schmorp.de/liblzf/liblzf-3.6.tar.gz)-3.6
- [libpng](https://github.com/glennrp/libpng)-1.6.38
- [libsodium](https://download.libsodium.org/libsodium/releases/libsodium-1.0.18.tar.gz)-1.0.18
- [libspatialite](https://www.gaia-gis.it/gaia-sins/libspatialite-5.0.1.tar.gz)-5.0.1
- [libssh2](https://www.libssh2.org/download/libssh2-1.10.0.tar.gz)-1.10.0
- [libtiff](https://gitlab.com/libtiff/libtiff)-4.4.0
- [libwebp](https://github.com/webmproject/libwebp)-1.2.4
- [libxml2](https://gitlab.gnome.org/GNOME/libxml2)-2.10.3
- [libxslt](https://gitlab.gnome.org/GNOME/libxslt)-1.1.37
- [minizip-ng](https://github.com/zlib-ng/minizip-ng)-3.0.7
- [mozjpeg](https://github.com/mozilla/mozjpeg)-4.1.1
- [msgpack-c](https://github.com/msgpack/msgpack-c)-2.1.4
- [netcdf-c](https://downloads.unidata.ucar.edu/netcdf-c/4.8.1/netcdf-c-4.8.1.tar.gz)-4.8.1
- [openblas](https://github.com/xianyi/OpenBLAS/releases/download/v0.3.21/OpenBLAS-0.3.21.zip)-0.3.21
- [opencl-icd-loader](https://github.com/KhronosGroup/OpenCL-ICD-Loader)-2022.09.30
- [opencv](https://github.com/opencv/opencv)-4.6.0
- [openexr](https://github.com/AcademySoftwareFoundation/openexr)-3.1.5
- [openjpeg](https://github.com/uclouvain/openjpeg)-2.5.0
- [openldap](https://www.openldap.org/software/download/OpenLDAP/openldap-release/openldap-2.4.59.tgz)-2.4.59
- [openssl](https://github.com/openssl/openssl)-1.1.1s
- [pdcurses](https://github.com/wmcbrine/PDCurses)-3.9
- [pixman](https://www.cairographics.org/releases/pixman-0.42.2.tar.gz)-0.42.2
- [portaudio](http://files.portaudio.com/archives/pa_stable_v190700_20210406.tgz)-19.7
- [portmidi](https://sourceforge.net/projects/portmedia/files/portmidi/v2.0.2/portmidi-v2.0.2.zip)-2.0.2
- [postgresql](https://ftp.postgresql.org/pub/source/v15.0/postgresql-15.0.tar.gz)-15.0
- [proj](https://download.osgeo.org/proj/proj-9.1.0.tar.gz)-9.1.0
- [rtmidi](http://www.music.mcgill.ca/~gary/rtmidi/release/rtmidi-5.0.0.tar.gz)-5.0.0
- [snappy](https://github.com/google/snappy)-1.1.8
- [spatialindex](https://github.com/libspatialindex/libspatialindex/releases/download/1.9.3/spatialindex-src-1.9.3.tar.gz)-1.9.3
- [sqlite](https://github.com/sqlite/sqlite)-3.39.4
- [ta-lib](https://sourceforge.net/projects/ta-lib/files/ta-lib/0.4.0/ta-lib-0.4.0-msvc.zip)-0.4.0
- [udunits](https://artifacts.unidata.ucar.edu/repository/downloads-udunits/2.2.28/udunits-2.2.28.zip)-2.2.28
- [uriparser](https://github.com/uriparser/uriparser)-0.9.7
- [win-iconv](https://github.com/OgreTransporter/win-iconv)-master
- [winpty](https://github.com/rprichard/winpty)-master
- [xz-lzma](https://github.com/xz-mirror/xz)-v5.2.7
- [zfp](https://github.com/LLNL/zfp)-1.0.0
- [zlib-ng](https://github.com/zlib-ng/zlib-ng)-2.0.6
- [zlib](https://github.com/madler/zlib)-v1.2.13
- [zopfli](https://github.com/google/zopfli)-1.0.3

### Build system

- [Windows Dev Kit](https://learn.microsoft.com/en-us/windows/arm/dev-kit/) 2023
- [Visual Studio](https://visualstudio.microsoft.com/vs/community/) 2022 Community 17.4
- [Python](https://www.python.org/downloads/release/python-3110/) 3.11.0 (ARM64)
- [LLVM](https://github.com/llvm/llvm-project/releases/tag/llvmorg-15.0.3) 15.0.3-woa64
- [Flang](https://github.com/kaadam/flang/releases/tag/v0.3) 0.3
- [Rust](https://www.rust-lang.org/tools/install) 1.65.0
- [OpenJDK](https://learn.microsoft.com/en-us/java/openjdk/download) 17.0.5 LTS
- [Strawberry Perl](https://strawberryperl.com/) 5.32.1.1
- [MSYS2](https://www.msys2.org/) 20221028
- [Git](https://gitforwindows.org/) 2.38.1
- [CMake](https://cmake.org/download/) 3.24.3
- [DirectX SDK](https://www.microsoft.com/en-us/download/details.aspx?id=6812) 9.0c
