# Experimental Wheels for Python for Windows on ARM64

This repository provides experimental binary wheels for open-source extension packages
for [Python for Windows on ARM64](https://www.python.org/downloads/windows/).

The files are experimental (meaning: unofficial, informal, unrecognized, unsupported,
no warranty, no liability, provided "as is") and made available for testing and
evaluation purposes. They are not intended for production use.

Most binaries are built from source code found in the Python Package Index or
the projects' public code repositories.

Refer to the documentation of the individual [packages](#wheels) and
[libraries](#libraries) for license restrictions and dependencies.

The wheels can be downloaded from the
[Releases](https://github.com/cgohlke/win_arm64-wheels/releases) page.

## Release 2023.12.6

### Highlights

- Many updates and rebuilds.

### Wheels

Binary wheels for the following packages for Python 3.11 are included in the
[release](https://github.com/cgohlke/win_arm64-wheels/releases/tag/v2023.12.6):

<details>
  <summary>Details</summary>

- [aggdraw](https://pypi.org/project/aggdraw/) 1.3.18
- [aiohttp](https://pypi.org/project/aiohttp/) 3.9.1
- [apsw](https://pypi.org/project/apsw/) 3.44.2.0
- [astropy](https://pypi.org/project/astropy/) 5.3.4
- [atom](https://pypi.org/project/atom/) 0.10.3
- [basemap](https://pypi.org/project/basemap/) 1.3.8
- [bcrypt](https://pypi.org/project/bcrypt/) 4.1.1
- [bitarray](https://pypi.org/project/bitarray/) 2.8.4
- [blosc2](https://pypi.org/project/blosc2/) 2.3.2
- [bsdiff4](https://pypi.org/project/bsdiff4/) 1.2.4
- [BTrees](https://pypi.org/project/BTrees/) 5.1
- [Cartopy](https://pypi.org/project/Cartopy/) 0.22.0
- [casa_formats_io](https://pypi.org/project/casa_formats_io/) 0.2.2
- [cftime](https://pypi.org/project/cftime/) 1.6.3
- [contourpy](https://pypi.org/project/contourpy/) 1.2.0
- [coverage](https://pypi.org/project/coverage/) 7.3.2
- [Cython](https://pypi.org/project/Cython/) 3.0.6
- [discretize](https://pypi.org/project/discretize/) 0.10.0
- [dtaidistance](https://pypi.org/project/dtaidistance/) 2.3.11
- [dulwich](https://pypi.org/project/dulwich/) 0.21.7
- [enaml](https://pypi.org/project/enaml/) 0.17.0
- [ephem](https://pypi.org/project/ephem/) 4.1.5
- [fabio](https://pypi.org/project/fabio/) 2023.10.0
- [fastparquet](https://pypi.org/project/fastparquet/) 2023.10.1
- [fiona](https://pypi.org/project/fiona/) 1.9.5
- [fonttools](https://pypi.org/project/fonttools/) 4.44.0
- [GDAL](https://pypi.org/project/GDAL/) 3.7.3
- [glcontext](https://pypi.org/project/glcontext/) 2.5.0
- [glfw](https://pypi.org/project/glfw/) 2.6.3
- [glumpy](https://pypi.org/project/glumpy/) 1.2.1
- [greenlet](https://pypi.org/project/greenlet/) 3.0.1
- [h5py](https://pypi.org/project/h5py/) 3.10.0
- [imread](https://pypi.org/project/imread/) 0.7.5
- [indexed_gzip](https://pypi.org/project/indexed_gzip/) 1.8.7
- [jellyfish](https://pypi.org/project/jellyfish/) 1.0.3
- [JPype1](https://pypi.org/project/JPype1/) 1.4.1
- [line_profiler](https://pypi.org/project/line_profiler/) 4.1.2
- [llvmlite](https://pypi.org/project/llvmlite/) 0.41.1
- [Logbook](https://pypi.org/project/Logbook/) 1.7.0.post0
- [lru_dict](https://pypi.org/project/lru_dict/) 1.3.0
- [marisa_trie](https://pypi.org/project/marisa_trie/) 1.1.0
- [matplotlib](https://pypi.org/project/matplotlib/) 3.8.2
- [maturin](https://pypi.org/project/maturin/) 1.4.0
- [mercurial](https://pypi.org/project/mercurial/) 6.5.3
- [moderngl](https://pypi.org/project/moderngl/) 5.9.0
- [netCDF4](https://pypi.org/project/netCDF4/) 1.6.5
- [numba](https://pypi.org/project/numba/) 0.58.1
- [numcodecs](https://pypi.org/project/numcodecs/) 0.12.1
- [numpy](https://pypi.org/project/numpy/) 1.26.2
- [numpy_quaternion](https://pypi.org/project/numpy_quaternion/) 2022.4.4
- [numpy_stl](https://pypi.org/project/numpy_stl/) 3.1.1
- [openTSNE](https://pypi.org/project/openTSNE/) 1.0.1
- [orjson](https://pypi.org/project/orjson/) 3.9.10
- [pandas](https://pypi.org/project/pandas/) 2.1.3
- [Pillow](https://pypi.org/project/Pillow/) 10.1.0
- [pillow_avif_plugin](https://pypi.org/project/pillow_avif_plugin/) 1.4.1
- [psutil](https://pypi.org/project/psutil/) 5.9.6
- [psycopg2](https://pypi.org/project/psycopg2/) 2.9.9
- [ptufile](https://pypi.org/project/ptufile/) 2023.11.16
- [PyAudio](https://pypi.org/project/PyAudio/) 0.2.14
- [pycairo](https://pypi.org/project/pycairo/) 1.25.1
- [pycares](https://pypi.org/project/pycares/) 4.4.0
- [PyCifRW](https://pypi.org/project/PyCifRW/) 4.4.6
- [pycosat](https://pypi.org/project/pycosat/) 0.6.6
- [pydantic_core](https://pypi.org/project/pydantic_core/) 2.11.0
- [pyeda](https://pypi.org/project/pyeda/) 0.29.0
- [pyerfa](https://pypi.org/project/pyerfa/) 2.0.1.1
- [pygeos](https://pypi.org/project/pygeos/) 0.14.0
- [pygit2](https://pypi.org/project/pygit2/) 1.13.3
- [PyICU](https://pypi.org/project/PyICU/) 2.12
- [pyjnius](https://pypi.org/project/pyjnius/) 1.6.1
- [pylibtiff](https://pypi.org/project/pylibtiff/) 0.6.1
- [pymatgen](https://pypi.org/project/pymatgen/) 2023.11.12
- [pymongo](https://pypi.org/project/pymongo/) 4.6.1
- [pymssql](https://pypi.org/project/pymssql/) 2.2.11
- [PyNaCl](https://pypi.org/project/PyNaCl/) 1.5.0
- [pyodbc](https://pypi.org/project/pyodbc/) 5.0.1
- [pyopencl](https://pypi.org/project/pyopencl/) 2023.1.4
- [PyOpenGL](https://pypi.org/project/PyOpenGL/) 3.1.7
- [PyOpenGL_accelerate](https://pypi.org/project/PyOpenGL_accelerate/) 3.1.7
- [pyproj](https://pypi.org/project/pyproj/) 3.6.1
- [pyreadstat](https://pypi.org/project/pyreadstat/) 1.2.5
- [pyrsistent](https://pypi.org/project/pyrsistent/) 0.20.0
- [pytensor](https://pypi.org/project/pytensor/) 2.18.1
- [python_ldap](https://pypi.org/project/python_ldap/) 3.4.4
- [python_rapidjson](https://pypi.org/project/python_rapidjson/) 1.13
- [PyTurboJPEG](https://pypi.org/project/PyTurboJPEG/) 1.7.3
- [pywavelets](https://pypi.org/project/pywavelets/) 1.5.0
- [pywinpty](https://pypi.org/project/pywinpty/) 2.0.12
- [pyzmq](https://pypi.org/project/pyzmq/) 25.1.2
- [rasterio](https://pypi.org/project/rasterio/) 1.3.9
- [recordclass](https://pypi.org/project/recordclass/) 0.21.1
- [regex](https://pypi.org/project/regex/) 2023.10.3
- [rpds_py](https://pypi.org/project/rpds_py/) 0.13.2
- [Rtree](https://pypi.org/project/Rtree/) 1.1.0
- [ruamel.yaml.clib](https://pypi.org/project/ruamel.yaml.clib/) 0.2.8
- [scikit_image](https://pypi.org/project/scikit_image/) 0.22.0
- [scikit_learn](https://pypi.org/project/scikit_learn/) 1.3.2
- [SciPy](https://pypi.org/project/SciPy/) 1.11.4
- [setproctitle](https://pypi.org/project/setproctitle/) 1.3.3
- [shapely](https://pypi.org/project/shapely/) 2.0.2
- [simplejson](https://pypi.org/project/simplejson/) 3.19.2
- [sortednp](https://pypi.org/project/sortednp/) 0.4.1
- [sounddevice](https://pypi.org/project/sounddevice/) 0.4.6
- [spacy](https://pypi.org/project/spacy/) 3.7.2
- [SQLAlchemy](https://pypi.org/project/SQLAlchemy/) 2.0.23
- [statsmodels](https://pypi.org/project/statsmodels/) 0.14.0
- [tables](https://pypi.org/project/tables/) 3.9.2
- [tinybrain](https://pypi.org/project/tinybrain/) 1.4.0
- [tokenizers](https://pypi.org/project/tokenizers/) 0.15.0
- [tornado](https://pypi.org/project/tornado/) 6.4
- [traits](https://pypi.org/project/traits/) 6.4.3
- [triangle](https://pypi.org/project/triangle/) 20230923
- [vispy](https://pypi.org/project/vispy/) 0.14.1
- [wavpack_numcodecs](https://pypi.org/project/wavpack_numcodecs/) 0.1.5
- [wrapt](https://pypi.org/project/wrapt/) 1.16.0
- [xxhash](https://pypi.org/project/xxhash/) 3.4.1
- [y_py](https://pypi.org/project/y_py/) 0.6.2
- [yappi](https://pypi.org/project/yappi/) 1.5.1
- [yarl](https://pypi.org/project/yarl/) 1.9.3
- [zodbpickle](https://pypi.org/project/zodbpickle/) 3.1
- [zope.interface](https://pypi.org/project/zope.interface/) 6.1
- [zopflipy](https://pypi.org/project/zopflipy/) 1.9

</details>

### Libraries

The wheels include the following statically or dynamically linked libraries:

<details>
  <summary>Details</summary>

- [abseil-cpp](https://github.com/abseil/abseil-cpp) 20230125.3
- [aom](https://aomedia.googlesource.com/aom) 3.7.1
- [arrow](https://github.com/apache/arrow) 1.5.0
- [avm-research](https://gitlab.com/AOMediaCodec/avm) v5.0.0
- [BerkeleyDB](https://github.com/berkeleydb/libdb/releases/download/v5.3.28/db-5.3.28.tar.gz) 5.3.28
- [boost](https://boostorg.jfrog.io/artifactory/main/release/1.82.0/source/boost_1_82_0.zip) 1.82.0
- [brotli](https://github.com/google/brotli) 1.1.0
- [brunsli](https://github.com/google/brunsli) 0.1
- [bzip2](https://sourceware.org/pub/bzip2/bzip2-1.0.8.tar.gz) 1.0.8
- [c-ares](https://c-ares.org/download/c-ares-1.22.1.tar.gz) 1.22.1
- [c-blosc2](https://github.com/Blosc/c-blosc2) 2.11.3
- [c-blosc](https://github.com/Blosc/c-blosc) 1.21.5
- [cairo](https://www.cairographics.org/releases/cairo-1.16.0.tar.xz) 1.16.0+lgpl
- [cfitsio](https://heasarc.gsfc.nasa.gov/FTP/software/fitsio/c/cfitsio-3.49.tar.gz) 3.49
- [charls](https://github.com/team-charls/charls) 2.4.2
- [curl](https://curl.se/download/curl-8.4.0.tar.gz) 8.4.0
- [dav1d](https://github.com/videolan/dav1d) 1.3.0
- [directx-strmbase](https://www.microsoft.com/en-us/download/details.aspx?id=6812) 9.0c
- [expat](https://github.com/libexpat/libexpat/releases/download/R_2_4_9/expat-2.4.9.tar.gz) 2.4.9
- [flac](https://gitlab.xiph.org/xiph/flac.git) 1.4.2
- [flann](https://github.com/flann-lib/flann) 1.9.2
- [fltk](https://www.fltk.org/pub/fltk/1.3.8/fltk-1.3.8-source.tar.gz) 1.3.8
- [fmtlib](https://github.com/fmtlib/fmt) 9.1.0
- [freeglut](https://github.com/FreeGLUTProject/freeglut) 3.4.0
- [freetds](https://www.freetds.org/files/stable/freetds-1.3.18.tar.gz) 1.3.18+lgpl
- [freetype](https://download-mirror.savannah.gnu.org/releases/freetype/freetype-2.13.2.tar.gz) 2.13.2
- [freexl](https://www.gaia-gis.it/gaia-sins/freexl-1.0.6.tar.gz) 1.0.6
- [fribidi](https://github.com/fribidi/fribidi) 1.0.13+lgpl
- [gdal](https://github.com/OSGeo/gdal) 3.7.3
- [geos](https://download.osgeo.org/geos/geos-3.11.2.tar.bz2) 3.11.2+lgpl
- [giflib](https://sourceforge.net/projects/giflib/files/giflib-5.2.1.tar.gz) 5.2.1
- [gle](https://sourceforge.net/projects/gle/files/gle/gle-3.1.0/gle-3.1.0.tar.gz) 3.1.0
- [glew](https://github.com/nigels-com/glew/releases/download/glew-2.2.0/glew-2.2.0.tgz) 2.2.0
- [glfw](https://github.com/glfw/glfw) 3.3.8
- [harfbuzz](https://github.com/harfbuzz/harfbuzz) 8.2.2
- [hdf4](https://github.com/HDFGroup/hdf4) 4.2.16.2
- [hdf5](https://support.hdfgroup.org/ftp/HDF5/releases/hdf5-1.14/hdf5-1.14.3/src/hdf5-1.14.3.tar.gz) 1.14.3
- [icu4c](https://github.com/unicode-org/icu/releases/download/release-74-1/icu4c-74_1-src.zip) 74.1
- [imath](https://github.com/AcademySoftwareFoundation/Imath) 3.1.9
- [jasper](https://github.com/jasper-software/jasper) 4.0.1
- [json-c](https://github.com/json-c/json-c) 0.16
- [jxrlib](https://github.com/cgohlke/jxrlib.git) 1.2
- [krb5](http://web.mit.edu/kerberos/dist/krb5/1.20/krb5-1.20.1.tar.gz) 1.20.1
- [lame](https://sourceforge.net/projects/lame/files/lame/3.100/lame-3.100.tar.gz) 3.100+lgpl
- [lerc](https://github.com/Esri/lerc) 4.0.0
- [libaec](https://gitlab.dkrz.de/k202009/libaec) 1.1.2
- [libarchive](https://github.com/libarchive/libarchive) 3.7.2
- [libavif](https://github.com/AOMediaCodec/libavif) 1.0.3
- [libde265](https://github.com/strukturag/libde265) 1.0.14+lgpl
- [libdeflate](https://github.com/ebiggers/libdeflate) 1.19
- [libevent](https://github.com/libevent/libevent) 2.1.12
- [libgeotiff](https://github.com/OSGeo/libgeotiff/releases/download/1.7.1/libgeotiff-1.7.1.tar.gz) 1.7.1
- [libgit2](https://github.com/libgit2/libgit2) 1.7.1
- [libgta](https://marlam.de/gta/releases/libgta-1.2.1.tar.xz) 1.2.1+lgpl
- [libjpeg-turbo](https://github.com/libjpeg-turbo/libjpeg-turbo) 3.0.1
- [libjxl](https://github.com/libjxl/libjxl) 0.8.2
- [libkml](https://github.com/libkml/libkml) 1.3.0
- [liblzf](http://dist.schmorp.de/liblzf/liblzf-3.6.tar.gz) 3.6
- [libmikmod](https://github.com/sezero/mikmod.git) 3.3.11.1+lgpl
- [libmodplug](https://github.com/Konstanty/libmodplug) master
- [libpng](https://github.com/glennrp/libpng) 1.6.40
- [libraqm](https://github.com/HOST-Oman/libraqm) 0.10.1
- [LibRaw](https://github.com/LibRaw/LibRaw) 0.21.1+lgpl
- [libsndfile](https://github.com/libsndfile/libsndfile) 1.2.0+lgpl
- [libsodium](https://download.libsodium.org/libsodium/releases/libsodium-1.0.18.tar.gz) 1.0.18
- [libspatialite](https://www.gaia-gis.it/gaia-sins/libspatialite-5.0.1.tar.gz) 5.0.1
- [libssh2](https://www.libssh2.org/download/libssh2-1.11.0.tar.gz) 1.11.0
- [libtiff](https://gitlab.com/libtiff/libtiff) 4.6.0
- [libwebp](https://github.com/webmproject/libwebp) 1.3.2
- [libxml2](https://gitlab.gnome.org/GNOME/libxml2) 2.11.5
- [libxslt](https://gitlab.gnome.org/GNOME/libxslt) 1.1.38
- [libyaml](https://github.com/yaml/libyaml) 0.2.5
- [libzmq](https://github.com/zeromq/libzmq) 4.3.5
- [littlecms](https://github.com/mm2/Little-CMS) 2.16
- [llvm](https://github.com/llvm/llvm-project/releases/download/llvmorg-14.0.6/llvm-14.0.6.src.tar.xz) 14.0.6
- [lz4](https://github.com/lz4/lz4) 1.9.4
- [lzfse](https://github.com/lzfse/lzfse/) 1.0
- [lzham](https://github.com/richgel999/lzham_codec) master
- [lzma](https://git.tukaani.org/xz.git) 5.4.5
- [minizip-ng](https://github.com/zlib-ng/minizip-ng) 3.0.10
- [mozjpeg](https://github.com/mozilla/mozjpeg) 4.1.1
- [mpg123](https://cytranet.dl.sourceforge.net/project/mpg123/mpg123/1.31.3/mpg123-1.31.3.tar.bz2) 1.31.3+lgpl
- [msgpack-c](https://github.com/msgpack/msgpack-c) 2.1.4
- [netcdf-c](https://github.com/Unidata/netcdf-c) 4.9.2
- [nghttp2](https://github.com/nghttp2/nghttp2) 1.54.0
- [ogg](https://gitlab.xiph.org/xiph/ogg.git) 1.3.5
- [oneTBB](https://github.com/oneapi-src/oneTBB) 2021.11.0
- [openblas](https://github.com/xianyi/OpenBLAS/releases/download/v0.3.21/OpenBLAS-0.3.21.zip) 0.3.21
- [opencl-icd-loader](https://github.com/KhronosGroup/OpenCL-ICD-Loader) 2023.04.17
- [OpenColorIO](https://github.com/AcademySoftwareFoundation/OpenColorIO) 2.2.1
- [opencv](https://github.com/opencv/opencv) 4.6.0
- [openexr](https://github.com/AcademySoftwareFoundation/openexr) 3.1.11
- [OpenImageIO](https://github.com/OpenImageIO/oiio) v2.4.17.0
- [openjpeg](https://github.com/uclouvain/openjpeg) 2.5.0
- [openldap](https://www.openldap.org/software/download/OpenLDAP/openldap-release/openldap-2.4.59.tgz) 2.4.59
- [openssl](https://github.com/openssl/openssl) 1.1.1w
- [OpenVDB](https://github.com/AcademySoftwareFoundation/openvdb) 10.0.1
- [OpenVR](https://github.com/ValveSoftware/openvr) 1.0.17
- [opus](https://gitlab.xiph.org/xiph/opus.git) 1.4
- [opusfile](https://github.com/xiph/opusfile) 0.12
- [pcre2](https://github.com/PCRE2Project/pcre2.git) 10.42
- [pdcurses](https://github.com/wmcbrine/PDCurses) 3.9
- [pixman](https://www.cairographics.org/releases/pixman-0.42.2.tar.gz) 0.42.2+lgpl
- [pkgconf](https://distfiles.dereferenced.org/pkgconf/pkgconf-1.9.3.tar.xz) 1.9.3
- [portaudio](http://files.portaudio.com/archives/pa_stable_v190700_20210406.tgz) 19.7
- [portmidi](https://sourceforge.net/projects/portmedia/files/portmidi/v2.0.2/portmidi-v2.0.2.zip) 2.0.2
- [postgresql](https://ftp.postgresql.org/pub/source/v15.4/postgresql-15.4.tar.gz) 15.4
- [proj](https://download.osgeo.org/proj/proj-9.3.0.tar.gz) 9.3.0
- [protobuf](https://github.com/protocolbuffers/protobuf/releases/download/v21.12/protobuf-python-4.21.12.zip) 4.21.12
- [ptex](https://github.com/wdas/ptex) 2.4.2
- [pugixml](https://github.com/zeux/pugixml) 1.13
- [qhull](https://github.com/qhull/qhull) 4.0.0
- [quickfix](https://github.com/quickfix/quickfix) 1.15.1
- [rav1e](https://github.com/xiph/rav1e) 0.6.6
- [rdkit](https://github.com/rdkit/rdkit) 22.9.5
- [re2](https://github.com/google/re2) 2023.11.01
- [robin-map](https://github.com/Tessil/robin-map) 1.2.1
- [rtmidi](http://www.music.mcgill.ca/~gary/rtmidi/release/rtmidi-5.0.0.tar.gz) 5.0.0
- [sdl](https://github.com/libsdl-org/SDL) 2.28.5
- [sdl_image](https://github.com/libsdl-org/SDL_image) 2.6.3
- [sdl_mixer](https://github.com/libsdl-org/SDL_mixer) 2.6.3
- [sdl_ttf](https://github.com/libsdl-org/SDL_ttf) 2.20.2
- [sheenbidi](https://github.com/Tehreer/SheenBidi) 2.6
- [snappy](https://github.com/google/snappy) 1.1.10
- [spatialindex](https://github.com/libspatialindex/libspatialindex/releases/download/1.9.3/spatialindex-src-1.9.3.tar.gz) 1.9.3
- [sqlite](https://github.com/sqlite/sqlite) 3.42.0
- [SVT-AV1](https://gitlab.com/AOMediaCodec/SVT-AV1) 1.7.0
- [SVT-HEVC](https://github.com/OpenVisualCloud/SVT-HEVC) 1.5.1
- [ta-lib](https://sourceforge.net/projects/ta-lib/files/ta-lib/0.4.0/ta-lib-0.4.0-msvc.zip) 0.4.0
- [thrift](https://github.com/apache/thrift) 0.18.1
- [tinyexr](https://github.com/syoyo/tinyexr) 1.0.7
- [udunits](https://artifacts.unidata.ucar.edu/repository/downloads-udunits/2.2.28/udunits-2.2.28.zip) 2.2.28
- [uriparser](https://github.com/uriparser/uriparser) 0.9.7
- [uthash](https://github.com/troydhanson/uthash) 2.3.0
- [vorbis](https://gitlab.xiph.org/xiph/vorbis.git) 1.3.7
- [vtk-m](https://gitlab.kitware.com/vtk/vtk-m/-/archive/v1.9.0/vtk-m-v1.9.0.tar.gz) 1.9.0
- [WavPack](https://github.com/dbry/WavPack) master
- [win-iconv](https://github.com/OgreTransporter/win-iconv) master
- [winflexbison](https://github.com/lexxmark/winflexbison) 2.5.25
- [winpty](https://github.com/rprichard/winpty) master
- [xgboost](https://github.com/dmlc/xgboost) 1.7.5
- [yaml-cpp](https://github.com/jbeder/yaml-cpp) 0.7.0
- [zfp](https://github.com/LLNL/zfp) 1.0.0
- [zlib-ng](https://github.com/zlib-ng/zlib-ng) 2.1.5
- [zlib](https://github.com/madler/zlib) 1.3
- [zopfli](https://github.com/google/zopfli) 1.0.3
- [zstd](https://github.com/facebook/zstd) 1.5.5

</details>

### Build system

- [Windows Dev Kit](https://learn.microsoft.com/en-us/windows/arm/dev-kit/) 2023
- [Visual Studio](https://visualstudio.microsoft.com/vs/community/) 2022 Community 17.8
- [Python](https://www.python.org/downloads/release/python-3115/) 3.11.7 (ARM64)
- [LLVM](https://github.com/llvm/llvm-project/releases/tag/llvmorg-16.0.6) 16.0.6-woa64
- [Flang](https://github.com/kaadam/flang/releases/tag/v0.3) 0.3
- [Rust](https://www.rust-lang.org/tools/install) 1.74
- [OpenJDK](https://learn.microsoft.com/en-us/java/openjdk/download) 17.0.8 LTS
- [Strawberry Perl](https://strawberryperl.com/) 5.32.1.1
- [MSYS2](https://www.msys2.org/) 20221028
- [Git](https://gitforwindows.org/) 2.42
- [CMake](https://cmake.org/download/) 3.27.4
- [DirectX SDK](https://www.microsoft.com/en-us/download/details.aspx?id=6812) 9.0c

## Release 2023.9.30

### Highlights

- Many updates and rebuilds.
- Fixes CVE-2023-4863.

### Wheels

Binary wheels for the following packages for Python 3.11 are included in the
[release](https://github.com/cgohlke/win_arm64-wheels/releases/tag/v2023.9.30):

<details>
  <summary>Details</summary>

- [aiohttp](https://pypi.org/project/aiohttp/) 3.8.5
- [apsw](https://pypi.org/project/apsw/) 3.43.1.0
- [argon2_cffi_bindings](https://pypi.org/project/argon2_cffi_bindings/) 21.2.0
- [astropy](https://pypi.org/project/astropy/) 5.3.3
- [asv](https://pypi.org/project/asv/) 0.6.1
- [autobahn](https://pypi.org/project/autobahn/) 23.6.2
- [basemap](https://pypi.org/project/basemap/) 1.3.8
- [bitarray](https://pypi.org/project/bitarray/) 2.8.1
- [bitshuffle](https://pypi.org/project/bitshuffle/) 0.5.1
- [blosc2](https://pypi.org/project/blosc2/) 2.2.8
- [boost_histogram](https://pypi.org/project/boost_histogram/) 1.4.0
- [Brotli](https://pypi.org/project/Brotli/) 1.1.0
- [cairocffi](https://pypi.org/project/cairocffi/) 1.6.1
- [Cartopy](https://pypi.org/project/Cartopy/) 0.22.0
- [centrosome](https://pypi.org/project/centrosome/) 1.2.2
- [cf_units](https://pypi.org/project/cf_units/) 3.2.0
- [cffi](https://pypi.org/project/cffi/) 1.16.0
- [cftime](https://pypi.org/project/cftime/) 1.6.2
- [chaco](https://pypi.org/project/chaco/) 6.0.0
- [contourpy](https://pypi.org/project/contourpy/) 1.1.1
- [coverage](https://pypi.org/project/coverage/) 7.3.1
- [cramjam](https://pypi.org/project/cramjam/) 2.7.0
- [cymem](https://pypi.org/project/cymem/) 2.0.8
- [Cython](https://pypi.org/project/Cython/) 0.29.36
- [cytoolz](https://pypi.org/project/cytoolz/) 0.12.2
- [debugpy](https://pypi.org/project/debugpy/) 1.8.0
- [discretize](https://pypi.org/project/discretize/) 0.9.0
- [dulwich](https://pypi.org/project/dulwich/) 0.21.6
- [edt](https://pypi.org/project/edt/) 2.3.1
- [enable](https://pypi.org/project/enable/) 6.0.0
- [ewah_bool_utils](https://pypi.org/project/ewah_bool_utils/) 1.1.0
- [fabio](https://pypi.org/project/fabio/) 2023.6.0
- [fastparquet](https://pypi.org/project/fastparquet/) 2023.8.0
- [fastremap](https://pypi.org/project/fastremap/) 1.14.0
- [fastrlock](https://pypi.org/project/fastrlock/) 0.8.2
- [Fiona](https://pypi.org/project/Fiona/) 1.9.4.post1
- [fisx](https://pypi.org/project/fisx/) 1.3.1
- [fpzip](https://pypi.org/project/fpzip/) 1.2.2
- [freetype_py](https://pypi.org/project/freetype_py/) 2.4.0
- [GDAL](https://pypi.org/project/GDAL/) 3.7.2
- [gevent](https://pypi.org/project/gevent/) 23.9.1
- [glcontext](https://pypi.org/project/glcontext/) 2.4.0
- [glfw](https://pypi.org/project/glfw/) 2.6.2
- [Glymur](https://pypi.org/project/Glymur/) 0.12.8
- [greenlet](https://pypi.org/project/greenlet/) 2.0.2
- [h5py](https://pypi.org/project/h5py/) 3.9.0
- [hdbscan](https://pypi.org/project/hdbscan/) 0.8.33
- [hmmlearn](https://pypi.org/project/hmmlearn/) 0.3.0
- [imagecodecs](https://pypi.org/project/imagecodecs/) 2023.9.18
- [imgui](https://pypi.org/project/imgui/) 2.0.0
- [indexed_gzip](https://pypi.org/project/indexed_gzip/) 1.8.5
- [jellyfish](https://pypi.org/project/jellyfish/) 1.0.1
- [Kivy](https://pypi.org/project/Kivy/) 2.2.1
- [kiwisolver](https://pypi.org/project/kiwisolver/) 1.4.5
- [lazy_object_proxy](https://pypi.org/project/lazy_object_proxy/) 1.9.0
- [lfdfiles](https://pypi.org/project/lfdfiles/) 2023.9.26
- [line_profiler](https://pypi.org/project/line_profiler/) 4.1.1
- [llvmlite](https://pypi.org/project/llvmlite/) 0.41.0
- [Logbook](https://pypi.org/project/Logbook/) 1.6.0
- [lxml](https://pypi.org/project/lxml/) 4.9.3
- [marisa_trie](https://pypi.org/project/marisa_trie/) 1.0.0
- [MarkupSafe](https://pypi.org/project/MarkupSafe/) 2.1.3
- [matplotlib](https://pypi.org/project/matplotlib/) 3.7.3
- [maturin](https://pypi.org/project/maturin/) 1.2.3
- [mercurial](https://pypi.org/project/mercurial/) 6.5.2
- [mplcairo](https://pypi.org/project/mplcairo/) 0.5
- [msgpack](https://pypi.org/project/msgpack/) 1.0.7
- [murmurhash](https://pypi.org/project/murmurhash/) 1.0.10
- [netCDF4](https://pypi.org/project/netCDF4/) 1.6.4
- [nh3](https://pypi.org/project/nh3/) 0.2.14
- [numba](https://pypi.org/project/numba/) 0.58.0
- [numcodecs](https://pypi.org/project/numcodecs/) 0.11.0
- [numexpr](https://pypi.org/project/numexpr/) 2.8.7
- [numpy](https://pypi.org/project/numpy/) 1.25.2
- [OpenImageIO](https://github.com/OpenImageIO/oiio) 2.4.15.0
- [openTSNE](https://pypi.org/project/openTSNE/) 1.0.0
- [orjson](https://pypi.org/project/orjson/) 3.9.7
- [pandas](https://pypi.org/project/pandas/) 2.1.1
- [Pillow](https://pypi.org/project/Pillow/) 10.0.1
- [pocketsphinx](https://pypi.org/project/pocketsphinx/) 5.0.2
- [preshed](https://pypi.org/project/preshed/) 3.0.9
- [psycopg2](https://pypi.org/project/psycopg2/) 2.9.8
- [pycairo](https://pypi.org/project/pycairo/) 1.25.0
- [pyerfa](https://pypi.org/project/pyerfa/) 2.0.0.3
- [pygame](https://pypi.org/project/pygame/) 2.5.2
- [pygeos](https://pypi.org/project/pygeos/) 0.14.0
- [pygit2](https://pypi.org/project/pygit2/) 1.13.1
- [PyGreSQL](https://pypi.org/project/PyGreSQL/) 5.2.5
- [pyhdf](https://pypi.org/project/pyhdf/) 0.11.3
- [pyjnius](https://pypi.org/project/pyjnius/) 1.5.0
- [pylibCZIrw](https://pypi.org/project/pylibCZIrw/) 3.5.2
- [pylibtiff](https://pypi.org/project/pylibtiff/) 0.6.1
- [pymatgen](https://pypi.org/project/pymatgen/) 2023.9.10
- [pymol](https://github.com/schrodinger/pymol-open-source) 2.6.0a0
- [pymol_launcher](https://pypi.org/project/pymol_launcher/) 2.6
- [pymongo](https://pypi.org/project/pymongo/) 4.5.0
- [pymssql](https://pypi.org/project/pymssql/) 2.2.8
- [pyopencl](https://pypi.org/project/pyopencl/) 2023.1.2
- [PyOpenGL](https://pypi.org/project/PyOpenGL/) 3.1.7
- [PyOpenGL_accelerate](https://pypi.org/project/PyOpenGL_accelerate/) 3.1.7
- [pypmc](https://pypi.org/project/pypmc/) 1.2.2
- [pyproj](https://pypi.org/project/pyproj/) 3.6.1
- [pyreadstat](https://pypi.org/project/pyreadstat/) 1.2.3
- [pytensor](https://pypi.org/project/pytensor/) 2.17.0
- [python_lzo](https://pypi.org/project/python_lzo/) 1.15
- [python_rapidjson](https://pypi.org/project/python_rapidjson/) 1.11
- [python_snappy](https://pypi.org/project/python_snappy/) 0.6.1
- [PyTurboJPEG](https://pypi.org/project/PyTurboJPEG/) 1.7.2
- [PyWavelets](https://pypi.org/project/PyWavelets/) 1.4.1
- [pywinpty](https://pypi.org/project/pywinpty/) 2.0.11
- [PyYAML](https://pypi.org/project/PyYAML/) 6.0.1
- [pyzmq](https://pypi.org/project/pyzmq/) 25.1.1
- [pyzstd](https://pypi.org/project/pyzstd/) 0.15.9
- [qutip](https://pypi.org/project/qutip/) 4.7.3
- [rapidfuzz](https://pypi.org/project/rapidfuzz/) 3.3.0
- [rasterio](https://pypi.org/project/rasterio/) 1.3.8
- [recordclass](https://pypi.org/project/recordclass/) 0.20.1
- [regex](https://pypi.org/project/regex/) 2023.8.8
- [rpds_py](https://pypi.org/project/rpds_py/) 0.10.3
- [Rtree](https://pypi.org/project/Rtree/) 1.0.1
- [scalene](https://pypi.org/project/scalene/) 1.5.31.1
- [scikit_image](https://pypi.org/project/scikit_image/) 0.21.0
- [scikit_learn](https://pypi.org/project/scikit_learn/) 1.3.1
- [SciPy](https://pypi.org/project/SciPy/) 1.11.3
- [sfepy](https://pypi.org/project/sfepy/) 2023.3
- [shapely](https://pypi.org/project/shapely/) 2.0.1
- [spacy](https://pypi.org/project/spacy/) 3.6.1
- [spglib](https://pypi.org/project/spglib/) 2.1.0
- [SQLAlchemy](https://pypi.org/project/SQLAlchemy/) 2.0.21
- [srsly](https://pypi.org/project/srsly/) 2.4.8
- [TA_Lib](https://pypi.org/project/TA_Lib/) 0.4.28
- [tables](https://pypi.org/project/tables/) 3.8.0
- [thinc](https://pypi.org/project/thinc/) 8.2.1
- [tokenizers](https://pypi.org/project/tokenizers/) 0.14.0
- [tornado](https://pypi.org/project/tornado/) 6.3.3
- [traits](https://pypi.org/project/traits/) 6.4.2
- [twisted_iocpsupport](https://pypi.org/project/twisted_iocpsupport/) 1.0.4
- [ujson](https://pypi.org/project/ujson/) 5.8.0
- [vispy](https://pypi.org/project/vispy/) 0.14.0
- [wordcloud](https://pypi.org/project/wordcloud/) 1.9.2
- [xxhash](https://pypi.org/project/xxhash/) 3.3.0
- [y_py](https://pypi.org/project/y_py/) 0.6.0
- [yt](https://pypi.org/project/yt/) 4.2.2

</details>

### Libraries

The wheels include the following statically or dynamically linked libraries:

<details>
  <summary>Details</summary>

- [abseil-cpp](https://github.com/abseil/abseil-cpp) 20230125.3
- [aom](https://aomedia.googlesource.com/aom) 3.7.0
- [arrow](https://github.com/apache/arrow) 1.5.0
- [BerkeleyDB](https://github.com/berkeleydb/libdb/releases/download/v5.3.28/db-5.3.28.tar.gz) 5.3.28
- [boost](https://boostorg.jfrog.io/artifactory/main/release/1.82.0/source/boost_1_82_0.zip) 1.82.0
- [brotli](https://github.com/google/brotli) 1.1.0
- [brunsli](https://github.com/google/brunsli) 0.1
- [bzip2](https://sourceware.org/pub/bzip2/bzip2-1.0.8.tar.gz) 1.0.8
- [c-ares](https://c-ares.org/download/c-ares-1.19.1.tar.gz) 1.19.1
- [c-blosc2](https://github.com/Blosc/c-blosc2) 2.10.4
- [c-blosc](https://github.com/Blosc/c-blosc) 1.21.5
- [cairo](https://www.cairographics.org/releases/cairo-1.16.0.tar.xz) 1.16.0+lgpl
- [cfitsio](https://heasarc.gsfc.nasa.gov/FTP/software/fitsio/c/cfitsio-3.49.tar.gz) 3.49
- [charls](https://github.com/team-charls/charls) 2.4.2
- [curl](https://curl.se/download/curl-8.2.1.tar.gz) 8.2.1
- [dav1d](https://github.com/videolan/dav1d) 1.2.1
- [directx-strmbase](https://www.microsoft.com/en-us/download/details.aspx?id=6812) 9.0c
- [expat](https://github.com/libexpat/libexpat/releases/download/R_2_4_9/expat-2.4.9.tar.gz) 2.4.9
- [flac](https://gitlab.xiph.org/xiph/flac.git) 1.4.2
- [flann](https://github.com/flann-lib/flann) 1.9.2
- [fltk](https://www.fltk.org/pub/fltk/1.3.8/fltk-1.3.8-source.tar.gz) 1.3.8
- [fmtlib](https://github.com/fmtlib/fmt) 9.1.0
- [freeglut](https://github.com/FreeGLUTProject/freeglut) 3.4.0
- [freetds](https://www.freetds.org/files/stable/freetds-1.3.18.tar.gz) 1.3.18+lgpl
- [freetype](https://download-mirror.savannah.gnu.org/releases/freetype/freetype-2.13.2.tar.gz) 2.13.2
- [freexl](https://www.gaia-gis.it/gaia-sins/freexl-1.0.6.tar.gz) 1.0.6
- [fribidi](https://github.com/fribidi/fribidi) 1.0.13+lgpl
- [gdal](https://github.com/OSGeo/gdal) 3.7.2
- [geos](https://download.osgeo.org/geos/geos-3.11.2.tar.bz2) 3.11.2+lgpl
- [giflib](https://sourceforge.net/projects/giflib/files/giflib-5.2.1.tar.gz) 5.2.1
- [gle](https://sourceforge.net/projects/gle/files/gle/gle-3.1.0/gle-3.1.0.tar.gz) 3.1.0
- [glew](https://github.com/nigels-com/glew/releases/download/glew-2.2.0/glew-2.2.0.tgz) 2.2.0
- [glfw](https://github.com/glfw/glfw) 3.3.8
- [harfbuzz](https://github.com/harfbuzz/harfbuzz) 8.1.1
- [hdf4](https://github.com/HDFGroup/hdf4) 4.2.16.2
- [hdf5](https://support.hdfgroup.org/ftp/HDF5/releases/hdf5-1.14/hdf5-1.14.2/src/hdf5-1.14.2.tar.gz) 1.14.2
- [icu4c](https://github.com/unicode-org/icu/releases/download/release-73-2/icu4c-73_2-src.zip) 73.2
- [imath](https://github.com/AcademySoftwareFoundation/Imath) 3.1.9
- [jasper](https://github.com/jasper-software/jasper) 4.0.0
- [json-c](https://github.com/json-c/json-c) 0.16
- [jxrlib](https://github.com/cgohlke/jxrlib.git) 1.2
- [krb5](http://web.mit.edu/kerberos/dist/krb5/1.20/krb5-1.20.1.tar.gz) 1.20.1
- [lame](https://sourceforge.net/projects/lame/files/lame/3.100/lame-3.100.tar.gz) 3.100+lgpl
- [lerc](https://github.com/Esri/lerc) 4.0.0
- [libaec](https://gitlab.dkrz.de/k202009/libaec) 1.0.6
- [libarchive](https://github.com/libarchive/libarchive) 3.7.2
- [libavif](https://github.com/AOMediaCodec/libavif) 1.0.1
- [libde265](https://github.com/strukturag/libde265) 1.0.12+lgpl
- [libdeflate](https://github.com/ebiggers/libdeflate) 1.19
- [libevent](https://github.com/libevent/libevent) 2.1.12
- [libgeotiff](https://github.com/OSGeo/libgeotiff/releases/download/1.7.1/libgeotiff-1.7.1.tar.gz) 1.7.1
- [libgit2](https://github.com/libgit2/libgit2) 1.7.1
- [libgta](https://marlam.de/gta/releases/libgta-1.2.1.tar.xz) 1.2.1+lgpl
- [libjpeg-turbo](https://github.com/libjpeg-turbo/libjpeg-turbo) 3.0.0
- [libjxl](https://github.com/libjxl/libjxl) 0.8.2
- [libkml](https://github.com/libkml/libkml) 1.3.0
- [liblzf](http://dist.schmorp.de/liblzf/liblzf-3.6.tar.gz) 3.6
- [libmikmod](https://github.com/sezero/mikmod.git) 3.3.11.1+lgpl
- [libmodplug](https://github.com/Konstanty/libmodplug) master
- [libpng](https://github.com/glennrp/libpng) 1.6.40
- [libraqm](https://github.com/HOST-Oman/libraqm) 0.10.1
- [LibRaw](https://github.com/LibRaw/LibRaw) 0.21.1+lgpl
- [libsndfile](https://github.com/libsndfile/libsndfile) 1.2.0+lgpl
- [libsodium](https://download.libsodium.org/libsodium/releases/libsodium-1.0.18.tar.gz) 1.0.18
- [libspatialite](https://www.gaia-gis.it/gaia-sins/libspatialite-5.0.1.tar.gz) 5.0.1
- [libssh2](https://www.libssh2.org/download/libssh2-1.11.0.tar.gz) 1.11.0
- [libtiff](https://gitlab.com/libtiff/libtiff) 4.6.0
- [libwebp](https://github.com/webmproject/libwebp) 1.3.2
- [libxml2](https://gitlab.gnome.org/GNOME/libxml2) 2.11.5
- [libxslt](https://gitlab.gnome.org/GNOME/libxslt) 1.1.38
- [libyaml](https://github.com/yaml/libyaml) 0.2.5
- [libzmq](https://github.com/zeromq/libzmq) master+lgpl
- [littlecms](https://github.com/mm2/Little-CMS) 2.15
- [llvm](https://github.com/llvm/llvm-project/releases/download/llvmorg-14.0.6/llvm-14.0.6.src.tar.xz) 14.0.6
- [lz4](https://github.com/lz4/lz4) 1.9.4
- [lzfse](https://github.com/lzfse/lzfse/) 1.0
- [lzham](https://github.com/richgel999/lzham_codec) master
- [lzma](https://git.tukaani.org/xz.git) 5.4.4
- [minizip-ng](https://github.com/zlib-ng/minizip-ng) 3.0.10
- [mozjpeg](https://github.com/mozilla/mozjpeg) 4.1.1
- [mpg123](https://cytranet.dl.sourceforge.net/project/mpg123/mpg123/1.31.3/mpg123-1.31.3.tar.bz2) 1.31.3+lgpl
- [msgpack-c](https://github.com/msgpack/msgpack-c) 2.1.4
- [netcdf-c](https://github.com/Unidata/netcdf-c) 4.9.2
- [nghttp2](https://github.com/nghttp2/nghttp2) 1.54.0
- [ogg](https://gitlab.xiph.org/xiph/ogg.git) 1.3.5
- [oneTBB](https://github.com/oneapi-src/oneTBB) 2021.10.0
- [openblas](https://github.com/xianyi/OpenBLAS/releases/download/v0.3.21/OpenBLAS-0.3.21.zip) 0.3.21
- [opencl-icd-loader](https://github.com/KhronosGroup/OpenCL-ICD-Loader) 2023.04.17
- [OpenColorIO](https://github.com/AcademySoftwareFoundation/OpenColorIO) 2.2.1
- [opencv](https://github.com/opencv/opencv) 4.6.0
- [openexr](https://github.com/AcademySoftwareFoundation/openexr) 3.1.11
- [OpenImageIO](https://github.com/OpenImageIO/oiio) v2.4.15.0
- [openjpeg](https://github.com/uclouvain/openjpeg) 2.5.0
- [openldap](https://www.openldap.org/software/download/OpenLDAP/openldap-release/openldap-2.4.59.tgz) 2.4.59
- [openssl](https://github.com/openssl/openssl) 1.1.1w
- [OpenVDB](https://github.com/AcademySoftwareFoundation/openvdb) 10.0.1
- [OpenVR](https://github.com/ValveSoftware/openvr) 1.0.17
- [opus](https://gitlab.xiph.org/xiph/opus.git) 1.4
- [opusfile](https://github.com/xiph/opusfile) 0.12
- [pcre2](https://github.com/PCRE2Project/pcre2.git) 10.42
- [pdcurses](https://github.com/wmcbrine/PDCurses) 3.9
- [pixman](https://www.cairographics.org/releases/pixman-0.42.2.tar.gz) 0.42.2+lgpl
- [pkgconf](https://distfiles.dereferenced.org/pkgconf/pkgconf-1.9.3.tar.xz) 1.9.3
- [portaudio](http://files.portaudio.com/archives/pa_stable_v190700_20210406.tgz) 19.7
- [portmidi](https://sourceforge.net/projects/portmedia/files/portmidi/v2.0.2/portmidi-v2.0.2.zip) 2.0.2
- [postgresql](https://ftp.postgresql.org/pub/source/v15.3/postgresql-15.3.tar.gz) 15.3
- [proj](https://download.osgeo.org/proj/proj-9.3.0.tar.gz) 9.3.0
- [protobuf](https://github.com/protocolbuffers/protobuf/releases/download/v21.12/protobuf-python-4.21.12.zip) 4.21.12
- [ptex](https://github.com/wdas/ptex) 2.4.2
- [pugixml](https://github.com/zeux/pugixml) 1.13
- [qhull](https://github.com/qhull/qhull) 4.0.0
- [rav1e](https://github.com/xiph/rav1e) 0.6.6
- [rdkit](https://github.com/rdkit/rdkit) 22.9.5
- [re2](https://github.com/google/re2) 2023.09.01
- [robin-map](https://github.com/Tessil/robin-map) 1.2.1
- [rtmidi](http://www.music.mcgill.ca/~gary/rtmidi/release/rtmidi-5.0.0.tar.gz) 5.0.0
- [sdl](https://github.com/libsdl-org/SDL) 2.28.3
- [sdl_image](https://github.com/libsdl-org/SDL_image) 2.6.3
- [sdl_mixer](https://github.com/libsdl-org/SDL_mixer) 2.6.3
- [sdl_ttf](https://github.com/libsdl-org/SDL_ttf) 2.20.2
- [sheenbidi](https://github.com/Tehreer/SheenBidi) 2.6
- [snappy](https://github.com/google/snappy) 1.1.10
- [spatialindex](https://github.com/libspatialindex/libspatialindex/releases/download/1.9.3/spatialindex-src-1.9.3.tar.gz) 1.9.3
- [sqlite](https://github.com/sqlite/sqlite) 3.42.0
- [SVT-AV1](https://gitlab.com/AOMediaCodec/SVT-AV1) 1.7.0
- [SVT-HEVC](https://github.com/OpenVisualCloud/SVT-HEVC) 1.5.1
- [ta-lib](https://sourceforge.net/projects/ta-lib/files/ta-lib/0.4.0/ta-lib-0.4.0-msvc.zip) 0.4.0
- [thrift](https://github.com/apache/thrift) 0.18.1
- [tinyexr](https://github.com/syoyo/tinyexr) 1.0.7
- [udunits](https://artifacts.unidata.ucar.edu/repository/downloads-udunits/2.2.28/udunits-2.2.28.zip) 2.2.28
- [uriparser](https://github.com/uriparser/uriparser) 0.9.7
- [uthash](https://github.com/troydhanson/uthash) 2.3.0
- [vorbis](https://gitlab.xiph.org/xiph/vorbis.git) 1.3.7
- [vtk-m](https://gitlab.kitware.com/vtk/vtk-m/-/archive/v1.9.0/vtk-m-v1.9.0.tar.gz) 1.9.0
- [WavPack](https://github.com/dbry/WavPack) 5.6.0
- [win-iconv](https://github.com/OgreTransporter/win-iconv) master
- [winflexbison](https://github.com/lexxmark/winflexbison) 2.5.25
- [winpty](https://github.com/rprichard/winpty) master
- [xgboost](https://github.com/dmlc/xgboost) 1.7.5
- [yaml-cpp](https://github.com/jbeder/yaml-cpp) 0.7.0
- [zfp](https://github.com/LLNL/zfp) 1.0.0
- [zlib-ng](https://github.com/zlib-ng/zlib-ng) 2.1.3
- [zlib](https://github.com/madler/zlib) 1.3
- [zopfli](https://github.com/google/zopfli) 1.0.3
- [zstd](https://github.com/facebook/zstd) 1.5.5

</details>

### Build system

<details>
  <summary>Details</summary>

- [Windows Dev Kit](https://learn.microsoft.com/en-us/windows/arm/dev-kit/) 2023
- [Visual Studio](https://visualstudio.microsoft.com/vs/community/) 2022 Community 17.7
- [Python](https://www.python.org/downloads/release/python-3115/) 3.11.5 (ARM64)
- [LLVM](https://github.com/llvm/llvm-project/releases/tag/llvmorg-16.0.6) 16.0.6-woa64
- [Flang](https://github.com/kaadam/flang/releases/tag/v0.3) 0.3
- [Rust](https://www.rust-lang.org/tools/install) 1.72
- [OpenJDK](https://learn.microsoft.com/en-us/java/openjdk/download) 17.0.8 LTS
- [Strawberry Perl](https://strawberryperl.com/) 5.32.1.1
- [MSYS2](https://www.msys2.org/) 20221028
- [Git](https://gitforwindows.org/) 2.42
- [CMake](https://cmake.org/download/) 3.27.4
- [DirectX SDK](https://www.microsoft.com/en-us/download/details.aspx?id=6812) 9.0c

</details>

## Release 2023.5.5

### Highlights

- Numba 0.57 and llvmlite 0.40
- OpenImageIO 2.4

### Wheels

Binary wheels for the following packages are included in the
[release](https://github.com/cgohlke/win_arm64-wheels/releases/tag/v2023.5.5):

<details>
  <summary>Details</summary>

- [aicspylibczi](https://pypi.org/project/aicspylibczi/) 3.1.2
- [atom](https://pypi.org/project/atom/) 0.10.0
- [basemap](https://pypi.org/project/basemap/) 1.3.7
- [blosc2](https://pypi.org/project/blosc2/) 2.2.0
- [cairocffi](https://pypi.org/project/cairocffi/) 1.5.1
- [Cartopy](https://pypi.org/project/Cartopy/) 0.21.1
- [cf_units](https://pypi.org/project/cf_units/) 3.2.0
- [chebyfit](https://pypi.org/project/chebyfit/) 2023.4.22
- [coverage](https://pypi.org/project/coverage/) 7.2.5
- [Cython](https://pypi.org/project/Cython/) 0.29.34
- [debugpy](https://pypi.org/project/debugpy/) 1.6.7
- [dulwich](https://pypi.org/project/dulwich/) 0.21.5
- [enaml](https://pypi.org/project/enaml/) 0.16.1
- [fabio](https://pypi.org/project/fabio/) 2023.4.1
- [Fiona](https://pypi.org/project/Fiona/) 1.9.3
- [fisx](https://pypi.org/project/fisx/) 1.3.0
- [fpzip](https://pypi.org/project/fpzip/) 1.2.1
- [freetype_py](https://pypi.org/project/freetype_py/) 2.4.0
- [GDAL](https://pypi.org/project/GDAL/) 3.6.4
- [Glymur](https://pypi.org/project/Glymur/) 0.12.5
- [jellyfish](https://pypi.org/project/jellyfish/) 0.11.2
- [lfdfiles](https://pypi.org/project/lfdfiles/) 2023.4.20
- [llvmlite](https://pypi.org/project/llvmlite/) 0.40.0
- [lmdb](https://pypi.org/project/lmdb/) 1.4.1
- [maturin](https://pypi.org/project/maturin/) 0.14.17
- [mercurial](https://pypi.org/project/mercurial/) 6.4.3
- [netCDF4](https://pypi.org/project/netCDF4/) 1.6.3
- [numba](https://pypi.org/project/numba/) 0.57.0
- [numpy](https://pypi.org/project/numpy/) 1.24.3
- [OpenImageIO](https://github.com/OpenImageIO/oiio) 2.4.11.0
- [orjson](https://pypi.org/project/orjson/) 3.8.11
- [pandas](https://pypi.org/project/pandas/) 2.0.1
- [PartSegCore_compiled_backend](https://pypi.org/project/PartSegCore_compiled_backend/) 0.15.1
- [psf](https://pypi.org/project/psf/) 2023.4.26
- [psutil](https://pypi.org/project/psutil/) 5.9.5
- [psycopg2](https://pypi.org/project/psycopg2/) 2.9.6
- [pygame](https://pypi.org/project/pygame/) 2.4.0
- [pygeos](https://pypi.org/project/pygeos/) 0.14.0
- [pygit2](https://pypi.org/project/pygit2/) 1.12.0
- [PyICU](https://pypi.org/project/PyICU/) 2.11
- [pylibCZIrw](https://pypi.org/project/pylibCZIrw/) 3.4.0
- [pymol](https://github.com/schrodinger/pymol-open-source) 2.6.0a0
- [pyodbc](https://pypi.org/project/pyodbc/) 4.0.39
- [pyproj](https://pypi.org/project/pyproj/) 3.5.0
- [pytensor](https://pypi.org/project/pytensor/) 2.11.0
- [PyTurboJPEG](https://pypi.org/project/PyTurboJPEG/) 1.7.1
- [rapidfuzz](https://pypi.org/project/rapidfuzz/) 2.15.1
- [rasterio](https://pypi.org/project/rasterio/) 1.3.6
- [recordclass](https://pypi.org/project/recordclass/) 0.18.4
- [regex](https://pypi.org/project/regex/) 2023.5.5
- [reportlab](https://pypi.org/project/reportlab/) 3.6.13
- [Rtree](https://pypi.org/project/Rtree/) 1.0.1
- [Shapely](https://pypi.org/project/Shapely/) 1.8.5.post1
- [shapely](https://pypi.org/project/shapely/) 2.0.1
- [simplejson](https://pypi.org/project/simplejson/) 3.19.1
- [spacy](https://pypi.org/project/spacy/) 3.5.2
- [SQLAlchemy](https://pypi.org/project/SQLAlchemy/) 1.4.48
- [statsmodels](https://pypi.org/project/statsmodels/) 0.14.0
- [TA_Lib](https://pypi.org/project/TA_Lib/) 0.4.26
- [thinc](https://pypi.org/project/thinc/) 8.1.10
- [tokenizers](https://pypi.org/project/tokenizers/) 0.13.3
- [tornado](https://pypi.org/project/tornado/) 6.3.1
- [wordcloud](https://pypi.org/project/wordcloud/) 1.9.1.1
- [yarl](https://pypi.org/project/yarl/) 1.9.2
- [zstd](https://pypi.org/project/zstd/) 1.5.5.1

</details>

### Libraries

The wheels include the following statically or dynamically linked libraries:

<details>
  <summary>Details</summary>

- [aom](https://aomedia.googlesource.com/aom) 3.6.0
- [arrow](https://github.com/apache/arrow) 1.5.0
- [BerkeleyDB](https://github.com/berkeleydb/libdb/releases/download/v5.3.28/db-5.3.28.tar.gz) 5.3.28
- [boost](https://boostorg.jfrog.io/artifactory/main/release/1.81.0/source/boost_1_81_0.zip) 1.81.0
- [brotli](https://github.com/google/brotli) 1.0.9
- [brunsli](https://github.com/google/brunsli) 0.1
- [bzip2](https://sourceware.org/pub/bzip2/bzip2-1.0.8.tar.gz) 1.0.8
- [c-ares](https://c-ares.org/download/c-ares-1.18.1.tar.gz) 1.18.1
- [c-blosc2](https://github.com/Blosc/c-blosc2) 2.8.0
- [c-blosc](https://github.com/Blosc/c-blosc) 1.21.3
- [cairo](https://www.cairographics.org/releases/cairo-1.16.0.tar.xz) 1.16.0+lgpl
- [cfitsio](https://heasarc.gsfc.nasa.gov/FTP/software/fitsio/c/cfitsio-3.49.tar.gz) 3.49
- [charls](https://github.com/team-charls/charls) 2.4.1
- [curl](https://curl.se/download/curl-7.88.1.tar.gz) 7.88.1
- [dav1d](https://github.com/videolan/dav1d) 1.2.0
- [directx-strmbase](https://www.microsoft.com/en-us/download/details.aspx?id=6812) 9.0c
- [expat](https://github.com/libexpat/libexpat/releases/download/R_2_4_9/expat-2.4.9.tar.gz) 2.4.9
- [flac](https://gitlab.xiph.org/xiph/flac.git) 1.4.2
- [flann](https://github.com/flann-lib/flann) 1.9.2
- [fltk](https://www.fltk.org/pub/fltk/1.3.8/fltk-1.3.8-source.tar.gz) 1.3.8
- [fmtlib](https://github.com/fmtlib/fmt) 9.1.0
- [freeglut](https://github.com/FreeGLUTProject/freeglut) 3.4.0
- [freetds](https://www.freetds.org/files/stable/freetds-1.3.17.tar.gz) 1.3.17+lgpl
- [freetype](https://download.savannah.gnu.org/releases/freetype/freetype-2.13.0.tar.gz) 2.13.0
- [freexl](https://www.gaia-gis.it/gaia-sins/freexl-1.0.6.tar.gz) 1.0.6
- [fribidi](https://github.com/fribidi/fribidi) 1.0.12+lgpl
- [gdal](https://github.com/OSGeo/gdal) 3.6.4
- [geos](https://download.osgeo.org/geos/geos-3.11.2.tar.bz2) 3.11.2+lgpl
- [giflib](https://sourceforge.net/projects/giflib/files/giflib-5.2.1.tar.gz) 5.2.1
- [gle](https://sourceforge.net/projects/gle/files/gle/gle-3.1.0/gle-3.1.0.tar.gz) 3.1.0
- [glew](https://github.com/nigels-com/glew/releases/download/glew-2.2.0/glew-2.2.0.tgz) 2.2.0
- [glfw](https://github.com/glfw/glfw) 3.3.8
- [harfbuzz](https://github.com/harfbuzz/harfbuzz) 7.2.0
- [hdf4](https://github.com/HDFGroup/hdf4) 4.2.16
- [hdf5](https://support.hdfgroup.org/ftp/HDF5/releases/hdf5-1.10/hdf5-1.10.10/src/hdf5-1.10.10.tar.gz) 1.10.10
- [icu4c](https://github.com/unicode-org/icu/releases/download/release-73-1/icu4c-73_1-src.zip) 73.1
- [imath](https://github.com/AcademySoftwareFoundation/Imath) 3.1.7
- [jasper](https://github.com/jasper-software/jasper) 4.0.0
- [json-c](https://github.com/json-c/json-c) 0.16
- [jxrlib](https://github.com/cgohlke/jxrlib.git) 1.2
- [krb5](http://web.mit.edu/kerberos/dist/krb5/1.20/krb5-1.20.1.tar.gz) 1.20.1
- [lame](https://sourceforge.net/projects/lame/files/lame/3.100/lame-3.100.tar.gz) 3.100+lgpl
- [lerc](https://github.com/Esri/lerc) 4.0.0
- [libaec](https://gitlab.dkrz.de/k202009/libaec) 1.0.6
- [libavif](https://github.com/AOMediaCodec/libavif) 0.11.1
- [libde265](https://github.com/strukturag/libde265) 1.0.11+lgpl
- [libdeflate](https://github.com/ebiggers/libdeflate) 1.18
- [libevent](https://github.com/libevent/libevent) 2.1.12
- [libgeotiff](https://github.com/OSGeo/libgeotiff/releases/download/1.7.1/libgeotiff-1.7.1.tar.gz) 1.7.1
- [libgit2](https://github.com/libgit2/libgit2) 1.6.4
- [libgta](https://marlam.de/gta/releases/libgta-1.2.1.tar.xz) 1.2.1+lgpl
- [libjpeg-turbo](https://github.com/libjpeg-turbo/libjpeg-turbo) 2.1.91
- [libjxl](https://github.com/libjxl/libjxl) 0.8.1
- [libkml](https://github.com/libkml/libkml) 1.3.0
- [liblzf](http://dist.schmorp.de/liblzf/liblzf-3.6.tar.gz) 3.6
- [libmikmod](https://github.com/sezero/mikmod.git) 3.3.11.1+lgpl
- [libmodplug](https://github.com/Konstanty/libmodplug) master
- [libpng](https://github.com/glennrp/libpng) 1.6.39
- [libraqm](https://github.com/HOST-Oman/libraqm) 0.10.1
- [LibRaw](https://github.com/LibRaw/LibRaw) 0.21.1+lgpl
- [libsndfile](https://github.com/libsndfile/libsndfile) 1.2.0+lgpl
- [libsodium](https://download.libsodium.org/libsodium/releases/libsodium-1.0.18.tar.gz) 1.0.18
- [libspatialite](https://www.gaia-gis.it/gaia-sins/libspatialite-5.0.1.tar.gz) 5.0.1
- [libssh2](https://www.libssh2.org/download/libssh2-1.10.0.tar.gz) 1.10.0
- [libtiff](https://gitlab.com/libtiff/libtiff) 4.5.0
- [libwebp](https://github.com/webmproject/libwebp) 1.3.0
- [libxml2](https://gitlab.gnome.org/GNOME/libxml2) 2.10.4
- [libxslt](https://gitlab.gnome.org/GNOME/libxslt) 1.1.37
- [libyaml](https://github.com/yaml/libyaml) 0.2.5
- [libzmq](https://github.com/zeromq/libzmq) master+lgpl
- [littlecms](https://github.com/mm2/Little-CMS) 2.14
- [llvm](https://github.com/llvm/llvm-project/releases/download/llvmorg-14.0.6/llvm-14.0.6.src.tar.xz) 14.0.6
- [lz4](https://github.com/lz4/lz4) 1.9.4
- [lzfse](https://github.com/lzfse/lzfse/) 1.0
- [lzham](https://github.com/richgel999/lzham_codec) master
- [lzma](https://git.tukaani.org/xz.git) 5.4.3
- [minizip-ng](https://github.com/zlib-ng/minizip-ng) 3.0.10
- [mozjpeg](https://github.com/mozilla/mozjpeg) 4.1.1
- [mpg123](https://cytranet.dl.sourceforge.net/project/mpg123/mpg123/1.31.3/mpg123-1.31.3.tar.bz2) 1.31.3+lgpl
- [msgpack-c](https://github.com/msgpack/msgpack-c) 2.1.4
- [netcdf-c](https://github.com/Unidata/netcdf-c) 4.9.2
- [ogg](https://gitlab.xiph.org/xiph/ogg.git) 1.3.5
- [oneTBB](https://github.com/oneapi-src/oneTBB) 2021.9.0
- [openblas](https://github.com/xianyi/OpenBLAS/releases/download/v0.3.21/OpenBLAS-0.3.21.zip) 0.3.21
- [opencl-icd-loader](https://github.com/KhronosGroup/OpenCL-ICD-Loader) 2023.04.17
- [OpenColorIO](https://github.com/AcademySoftwareFoundation/OpenColorIO) 2.2.1
- [opencv](https://github.com/opencv/opencv) 4.6.0
- [openexr](https://github.com/AcademySoftwareFoundation/openexr) 3.1.7
- [OpenImageIO](https://github.com/OpenImageIO/oiio) v2.4.11.0
- [openjpeg](https://github.com/uclouvain/openjpeg) 2.5.0
- [openldap](https://www.openldap.org/software/download/OpenLDAP/openldap-release/openldap-2.4.59.tgz) 2.4.59
- [openssl](https://github.com/openssl/openssl) 1.1.1t
- [OpenVDB](https://github.com/AcademySoftwareFoundation/openvdb) 10.0.1
- [OpenVR](https://github.com/ValveSoftware/openvr) 1.0.17
- [opus](https://gitlab.xiph.org/xiph/opus.git) 1.4
- [opusfile](https://github.com/xiph/opusfile) 0.12
- [pcre2](https://github.com/PCRE2Project/pcre2.git) 10.42
- [pdcurses](https://github.com/wmcbrine/PDCurses) 3.9
- [pixman](https://www.cairographics.org/releases/pixman-0.42.2.tar.gz) 0.42.2+lgpl
- [pkgconf](https://distfiles.dereferenced.org/pkgconf/pkgconf-1.9.3.tar.xz) 1.9.3
- [portaudio](http://files.portaudio.com/archives/pa_stable_v190700_20210406.tgz) 19.7
- [portmidi](https://sourceforge.net/projects/portmedia/files/portmidi/v2.0.2/portmidi-v2.0.2.zip) 2.0.2
- [postgresql](https://ftp.postgresql.org/pub/source/v15.2/postgresql-15.2.tar.gz) 15.2
- [proj](https://download.osgeo.org/proj/proj-9.1.1.tar.gz) 9.1.1
- [protobuf](https://github.com/protocolbuffers/protobuf/releases/download/v21.12/protobuf-python-4.21.12.zip) 4.21.12
- [ptex](https://github.com/wdas/ptex) 2.4.2
- [pugixml](https://github.com/zeux/pugixml) 1.13
- [qhull](https://github.com/qhull/qhull) 4.0.0
- [rav1e](https://github.com/xiph/rav1e) 0.6.4
- [rdkit](https://github.com/rdkit/rdkit) 22.9.5
- [re2](https://github.com/google/re2) 2023.03.01
- [robin-map](https://github.com/Tessil/robin-map) 1.2.1
- [rtmidi](http://www.music.mcgill.ca/~gary/rtmidi/release/rtmidi-5.0.0.tar.gz) 5.0.0
- [sdl](https://github.com/libsdl-org/SDL) 2.26.5
- [sdl_image](https://github.com/libsdl-org/SDL_image) 2.6.3
- [sdl_mixer](https://github.com/libsdl-org/SDL_mixer) 2.6.3
- [sdl_ttf](https://github.com/libsdl-org/SDL_ttf) 2.20.2
- [sheenbidi](https://github.com/Tehreer/SheenBidi) 2.6
- [snappy](https://github.com/google/snappy) 1.1.10
- [spatialindex](https://github.com/libspatialindex/libspatialindex/releases/download/1.9.3/spatialindex-src-1.9.3.tar.gz) 1.9.3
- [sqlite](https://github.com/sqlite/sqlite) 3.41.2
- [SVT-AV1](https://gitlab.com/AOMediaCodec/SVT-AV1) 1.4.1
- [SVT-HEVC](https://github.com/OpenVisualCloud/SVT-HEVC) 1.5.1
- [ta-lib](https://sourceforge.net/projects/ta-lib/files/ta-lib/0.4.0/ta-lib-0.4.0-msvc.zip) 0.4.0
- [thrift](https://github.com/apache/thrift) 0.18.1
- [tinyexr](https://github.com/syoyo/tinyexr) 1.0.2
- [udunits](https://artifacts.unidata.ucar.edu/repository/downloads-udunits/2.2.28/udunits-2.2.28.zip) 2.2.28
- [uriparser](https://github.com/uriparser/uriparser) 0.9.7
- [uthash](https://github.com/troydhanson/uthash) 2.3.0
- [vorbis](https://gitlab.xiph.org/xiph/vorbis.git) 1.3.7
- [vtk-m](https://gitlab.kitware.com/vtk/vtk-m/-/archive/v1.9.0/vtk-m-v1.9.0.tar.gz) 1.9.0
- [WavPack](https://github.com/dbry/WavPack) 5.6.0
- [win-iconv](https://github.com/OgreTransporter/win-iconv) master
- [winflexbison](https://github.com/lexxmark/winflexbison) 2.5.25
- [winpty](https://github.com/rprichard/winpty) master
- [xgboost](https://github.com/dmlc/xgboost) 1.7.5
- [yaml-cpp](https://github.com/jbeder/yaml-cpp) 0.7.0
- [zfp](https://github.com/LLNL/zfp) 1.0.0
- [zlib-ng](https://github.com/zlib-ng/zlib-ng) 2.0.7
- [zlib](https://github.com/madler/zlib) 1.2.13
- [zopfli](https://github.com/google/zopfli) 1.0.3
- [zstd](https://github.com/facebook/zstd) 1.5.5

</details>

### Build system

<details>
  <summary>Details</summary>

- [Windows Dev Kit](https://learn.microsoft.com/en-us/windows/arm/dev-kit/) 2023
- [Visual Studio](https://visualstudio.microsoft.com/vs/community/) 2022 Community 17.5
- [Python](https://www.python.org/downloads/release/python-3113/) 3.11.3 (ARM64)
- [LLVM](https://github.com/llvm/llvm-project/releases/tag/llvmorg-15.0.3) 15.0.3-woa64
- [Flang](https://github.com/kaadam/flang/releases/tag/v0.3) 0.3
- [Rust](https://www.rust-lang.org/tools/install) 1.68
- [OpenJDK](https://learn.microsoft.com/en-us/java/openjdk/download) 17.0.7 LTS
- [Strawberry Perl](https://strawberryperl.com/) 5.32.1.1
- [MSYS2](https://www.msys2.org/) 20221028
- [Git](https://gitforwindows.org/) 2.39.2
- [CMake](https://cmake.org/download/) 3.24.3
- [DirectX SDK](https://www.microsoft.com/en-us/download/details.aspx?id=6812) 9.0c

</details>

## Release 2023.4.1

### Highlights

- Numpy 1.24 and scipy 1.10
- Fixed Jupyter kernel connection issues

### Wheels

Binary wheels for the following packages are included in the
[release](https://github.com/cgohlke/win_arm64-wheels/releases/tag/v2023.4.1):

<details>
  <summary>Details</summary>

- [aggdraw](https://pypi.org/project/aggdraw/) 1.3.16
- [aicspylibczi](https://pypi.org/project/aicspylibczi/) 3.1.0
- [aiohttp](https://pypi.org/project/aiohttp/) 3.8.4
- [apsw](https://pypi.org/project/apsw/) 3.41.2.0
- [astropy](https://pypi.org/project/astropy/) 5.2.2
- [atom](https://pypi.org/project/atom/) 0.9.1
- [autobahn](https://pypi.org/project/autobahn/) 23.1.2
- [basemap](https://pypi.org/project/basemap/) 1.3.6
- [biopython](https://pypi.org/project/biopython/) 1.81
- [bitarray](https://pypi.org/project/bitarray/) 2.7.3
- [blosc2](https://pypi.org/project/blosc2/) 2.1.1
- [Bottleneck](https://pypi.org/project/Bottleneck/) 1.3.7
- [bsdiff4](https://pypi.org/project/bsdiff4/) 1.2.3
- [BTrees](https://pypi.org/project/BTrees/) 5.0
- [cairocffi](https://pypi.org/project/cairocffi/) 1.5.0
- [Cartopy](https://pypi.org/project/Cartopy/) 0.21.1
- [celiagg](https://pypi.org/project/celiagg/) 2.1.3
- [chaco](https://pypi.org/project/chaco/) 5.1.1
- [contourpy](https://pypi.org/project/contourpy/) 1.0.7
- [coverage](https://pypi.org/project/coverage/) 7.2.2
- [Cython](https://pypi.org/project/Cython/) 0.29.33
- [cytoolz](https://pypi.org/project/cytoolz/) 0.12.1
- [debugpy](https://pypi.org/project/debugpy/) 1.6.6
- [dipy](https://pypi.org/project/dipy/) 1.6.0
- [discretize](https://pypi.org/project/discretize/) 0.8.3
- [dulwich](https://pypi.org/project/dulwich/) 0.21.3
- [enaml](https://pypi.org/project/enaml/) 0.16.0
- [fastparquet](https://pypi.org/project/fastparquet/) 2023.2.0
- [Fiona](https://pypi.org/project/Fiona/) 1.9.2
- [fisx](https://pypi.org/project/fisx/) 1.2.1
- [GDAL](https://pypi.org/project/GDAL/) 3.6.3
- [glfw](https://pypi.org/project/glfw/) 2.5.9
- [Glymur](https://pypi.org/project/Glymur/) 0.12.2
- [greenlet](https://pypi.org/project/greenlet/) 2.0.2
- [h5py](https://pypi.org/project/h5py/) 3.8.0
- [imagecodecs](https://pypi.org/project/imagecodecs/) 2023.3.16
- [indexed_gzip](https://pypi.org/project/indexed_gzip/) 1.7.1
- [intbitset](https://pypi.org/project/intbitset/) 3.0.2
- [jellyfish](https://pypi.org/project/jellyfish/) 0.11.1
- [lazy_object_proxy](https://pypi.org/project/lazy_object_proxy/) 1.9.0
- [line_profiler](https://pypi.org/project/line_profiler/) 4.0.3
- [lz4](https://pypi.org/project/lz4/) 4.3.2
- [marisa_trie](https://pypi.org/project/marisa_trie/) 0.8.0
- [MarkupSafe](https://pypi.org/project/MarkupSafe/) 2.1.2
- [matplotlib](https://pypi.org/project/matplotlib/) 3.7.1
- [maturin](https://pypi.org/project/maturin/) 0.14.16
- [mercurial](https://pypi.org/project/mercurial/) 6.4
- [moderngl](https://pypi.org/project/moderngl/) 5.8.2
- [msgpack](https://pypi.org/project/msgpack/) 1.0.5
- [multidict](https://pypi.org/project/multidict/) 6.0.4
- [netCDF4](https://pypi.org/project/netCDF4/) 1.6.3
- [numexpr](https://pypi.org/project/numexpr/) 2.8.4
- [numpy](https://pypi.org/project/numpy/) 1.24.2
- [numpy_quaternion](https://pypi.org/project/numpy_quaternion/) 2022.4.3
- [orjson](https://pypi.org/project/orjson/) 3.8.9
- [pandas](https://pypi.org/project/pandas/) 1.5.3
- [PartSegCore_compiled_backend](https://pypi.org/project/PartSegCore_compiled_backend/) 0.15.0
- [persistent](https://pypi.org/project/persistent/) 5.0
- [Pillow](https://pypi.org/project/Pillow/) 9.5.0
- [protobuf](https://pypi.org/project/protobuf/) 4.21.12
- [psycopg2](https://pypi.org/project/psycopg2/) 2.9.5
- [PyAudio](https://pypi.org/project/PyAudio/) 0.2.13
- [pycairo](https://pypi.org/project/pycairo/) 1.23.0
- [pydantic](https://pypi.org/project/pydantic/) 1.10.7
- [pyemd](https://pypi.org/project/pyemd/) 1.0.0
- [pyerfa](https://pypi.org/project/pyerfa/) 2.0.0.3
- [pygame](https://pypi.org/project/pygame/) 2.3.0
- [pygeos](https://pypi.org/project/pygeos/) 0.14.0
- [pylibCZIrw](https://pypi.org/project/pylibCZIrw/) 3.3.1
- [pylibjpeg_libjpeg](https://pypi.org/project/pylibjpeg_libjpeg/) 1.3.4
- [pylibjpeg_openjpeg](https://pypi.org/project/pylibjpeg_openjpeg/) 1.3.2
- [pylibtiff](https://pypi.org/project/pylibtiff/) 0.5.1
- [pylzham](https://pypi.org/project/pylzham/) 0.1.3
- [pymatgen](https://pypi.org/project/pymatgen/) 2023.3.23
- [PyMCubes](https://pypi.org/project/PyMCubes/) 0.1.4
- [pymol](https://github.com/schrodinger/pymol-open-source) 2.6.0a0
- [pyopencl](https://pypi.org/project/pyopencl/) 2022.3.1
- [pyproj](https://pypi.org/project/pyproj/) 3.5.0
- [pyreadstat](https://pypi.org/project/pyreadstat/) 1.2.1
- [PyStemmer](https://pypi.org/project/PyStemmer/) 2.2.0.1
- [pytensor](https://pypi.org/project/pytensor/) 2.10.1
- [python_rapidjson](https://pypi.org/project/python_rapidjson/) 1.10
- [pytomlpp](https://pypi.org/project/pytomlpp/) 1.0.13
- [pywin32](https://pypi.org/project/pywin32/) 306
- [pywinpty](https://pypi.org/project/pywinpty/) 2.0.10
- [pyzmq](https://pypi.org/project/pyzmq/) 25.0.2
- [rapidfuzz](https://pypi.org/project/rapidfuzz/) 2.14.0
- [rasterio](https://pypi.org/project/rasterio/) 1.3.6
- [recordclass](https://pypi.org/project/recordclass/) 0.18.3
- [regex](https://pypi.org/project/regex/) 2023.3.23
- [Rtree](https://pypi.org/project/Rtree/) 1.0.1
- [scikit_image](https://pypi.org/project/scikit_image/) 0.20.0
- [scikit_learn](https://pypi.org/project/scikit_learn/) 1.2.2
- [SciPy](https://pypi.org/project/SciPy/) 1.10.1
- [sfepy](https://pypi.org/project/sfepy/) 2023.1
- [Shapely](https://pypi.org/project/Shapely/) 1.8.5.post1
- [shapely](https://pypi.org/project/shapely/) 2.0.1
- [simplejson](https://pypi.org/project/simplejson/) 3.18.4
- [SimpleParse](https://pypi.org/project/SimpleParse/) 2.2.4
- [sounddevice](https://pypi.org/project/sounddevice/) 0.4.6
- [soundfile](https://pypi.org/project/soundfile/) 0.12.1
- [spacy](https://pypi.org/project/spacy/) 3.5.1
- [SQLAlchemy](https://pypi.org/project/SQLAlchemy/) 2.0.8
- [srsly](https://pypi.org/project/srsly/) 2.4.6
- [tables](https://pypi.org/project/tables/) 3.8.0
- [thinc](https://pypi.org/project/thinc/) 8.1.9
- [tornado](https://pypi.org/project/tornado/) 6.2
- [ujson](https://pypi.org/project/ujson/) 5.7.0
- [vispy](https://pypi.org/project/vispy/) 0.12.2
- [wrapt](https://pypi.org/project/wrapt/) 1.15.0
- [xgboost](https://pypi.org/project/xgboost/) 1.7.5
- [xxhash](https://pypi.org/project/xxhash/) 3.2.0
- [y_py](https://pypi.org/project/y_py/) 0.6.0
- [yt](https://pypi.org/project/yt/) 4.1.4
- [zope.interface](https://pypi.org/project/zope.interface/) 6.0
- [zstd](https://pypi.org/project/zstd/) 1.5.4.1

</details>

### Libraries

The wheels include the following statically or dynamically linked libraries:

<details>
  <summary>Details</summary>

- [aom](https://aomedia.googlesource.com/aom) 3.6.0
- [BerkeleyDB](https://github.com/berkeleydb/libdb/releases/download/v5.3.28/db-5.3.28.tar.gz) 5.3.28
- [boost](https://boostorg.jfrog.io/artifactory/main/release/1.81.0/source/boost_1_81_0.zip) 1.81.0
- [brotli](https://github.com/google/brotli) 1.0.9
- [brunsli](https://github.com/google/brunsli) 0.1
- [bzip2](https://sourceware.org/pub/bzip2/bzip2-1.0.8.tar.gz) 1.0.8
- [c-ares](https://c-ares.org/download/c-ares-1.18.1.tar.gz) 1.18.1
- [c-blosc2](https://github.com/Blosc/c-blosc2) 2.8.0
- [c-blosc](https://github.com/Blosc/c-blosc) 1.21.3
- [cairo](https://www.cairographics.org/releases/cairo-1.16.0.tar.xz) 1.16.0+lgpl
- [cfitsio](https://heasarc.gsfc.nasa.gov/FTP/software/fitsio/c/cfitsio-3.49.tar.gz) 3.49
- [charls](https://github.com/team-charls/charls) 2.4.1
- [curl](https://curl.se/download/curl-7.88.1.tar.gz) 7.88.1
- [dav1d](https://github.com/videolan/dav1d) 1.1.0
- [directx-strmbase](https://www.microsoft.com/en-us/download/details.aspx?id=6812) 9.0c
- [expat](https://github.com/libexpat/libexpat/releases/download/R_2_4_9/expat-2.4.9.tar.gz) 2.4.9
- [flac](https://gitlab.xiph.org/xiph/flac.git) 1.4.2
- [flann](https://github.com/flann-lib/flann) 1.9.2
- [fltk](https://www.fltk.org/pub/fltk/1.3.8/fltk-1.3.8-source.tar.gz) 1.3.8
- [freeglut](https://github.com/FreeGLUTProject/freeglut) 3.4.0
- [freetds](https://www.freetds.org/files/stable/freetds-1.3.17.tar.gz) 1.3.17+lgpl
- [freetype](https://download.savannah.gnu.org/releases/freetype/freetype-2.13.0.tar.gz) 2.13.0
- [freexl](https://www.gaia-gis.it/gaia-sins/freexl-1.0.6.tar.gz) 1.0.6
- [fribidi](https://github.com/fribidi/fribidi) 1.0.12+lgpl
- [gdal](https://github.com/OSGeo/gdal) 3.6.3
- [geos](https://download.osgeo.org/geos/geos-3.11.2.tar.bz2) 3.11.2+lgpl
- [giflib](https://sourceforge.net/projects/giflib/files/giflib-5.2.1.tar.gz) 5.2.1
- [gle](https://sourceforge.net/projects/gle/files/gle/gle-3.1.0/gle-3.1.0.tar.gz) 3.1.0
- [glew](https://github.com/nigels-com/glew/releases/download/glew-2.2.0/glew-2.2.0.tgz) 2.2.0
- [glfw](https://github.com/glfw/glfw) 3.3.8
- [harfbuzz](https://github.com/harfbuzz/harfbuzz) 7.1.0
- [hdf4](https://github.com/HDFGroup/hdf4) 4.2.16
- [hdf5](https://support.hdfgroup.org/ftp/HDF5/releases/hdf5-1.10/hdf5-1.10.9/src/hdf5-1.10.9.tar.gz) 1.10.9
- [icu4c](https://github.com/unicode-org/icu/releases/download/release-72-1/icu4c-72_1-src.zip) 72.1
- [imath](https://github.com/AcademySoftwareFoundation/Imath) 3.1.7
- [jasper](https://github.com/jasper-software/jasper) 4.0.0
- [json-c](https://github.com/json-c/json-c) 0.16
- [jxrlib](https://salsa.debian.org/debian-phototools-team/jxrlib) 1.2
- [krb5](http://web.mit.edu/kerberos/dist/krb5/1.20/krb5-1.20.1.tar.gz) 1.20.1
- [lame](https://sourceforge.net/projects/lame/files/lame/3.100/lame-3.100.tar.gz) 3.100+lgpl
- [lerc](https://github.com/Esri/lerc) 4.0.0
- [libaec](https://gitlab.dkrz.de/k202009/libaec) 1.0.6
- [libavif](https://github.com/AOMediaCodec/libavif) 0.11.1
- [libde265](https://github.com/strukturag/libde265) 1.0.11+lgpl
- [libdeflate](https://github.com/ebiggers/libdeflate) 1.18
- [libevent](https://github.com/libevent/libevent) 2.1.12
- [libgeotiff](https://github.com/OSGeo/libgeotiff/releases/download/1.7.1/libgeotiff-1.7.1.tar.gz) 1.7.1
- [libgit2](https://github.com/libgit2/libgit2) 1.6.3
- [libjpeg-turbo](https://github.com/libjpeg-turbo/libjpeg-turbo) 2.1.91
- [libjxl](https://github.com/libjxl/libjxl) 0.8.1
- [libkml](https://github.com/libkml/libkml) 1.3.0
- [liblzf](http://dist.schmorp.de/liblzf/liblzf-3.6.tar.gz) 3.6
- [libmikmod](https://github.com/sezero/mikmod.git) 3.3.11.1+lgpl
- [libmodplug](https://github.com/Konstanty/libmodplug) master
- [libpng](https://github.com/glennrp/libpng) 1.6.39
- [libraqm](https://github.com/HOST-Oman/libraqm) 0.9.0
- [libsndfile](https://github.com/libsndfile/libsndfile) 1.2.0+lgpl
- [libsodium](https://download.libsodium.org/libsodium/releases/libsodium-1.0.18.tar.gz) 1.0.18
- [libspatialite](https://www.gaia-gis.it/gaia-sins/libspatialite-5.0.1.tar.gz) 5.0.1
- [libssh2](https://www.libssh2.org/download/libssh2-1.10.0.tar.gz) 1.10.0
- [libtiff](https://gitlab.com/libtiff/libtiff) 4.5.0
- [libwebp](https://github.com/webmproject/libwebp) 1.3.0
- [libxml2](https://gitlab.gnome.org/GNOME/libxml2) 2.10.3
- [libxslt](https://gitlab.gnome.org/GNOME/libxslt) 1.1.37
- [libyaml](https://github.com/yaml/libyaml) 0.2.5
- [libzmq](https://github.com/zeromq/libzmq) master+lgpl
- [littlecms](https://github.com/mm2/Little-CMS) 2.14
- [lz4](https://github.com/lz4/lz4) 1.9.4
- [lzfse](https://github.com/lzfse/lzfse/) 1.0
- [lzham](https://github.com/richgel999/lzham_codec) master
- [minizip-ng](https://github.com/zlib-ng/minizip-ng) 3.0.7
- [mozjpeg](https://github.com/mozilla/mozjpeg) 4.1.1
- [mpg123](https://cytranet.dl.sourceforge.net/project/mpg123/mpg123/1.31.3/mpg123-1.31.3.tar.bz2) 1.31.3+lgpl
- [msgpack-c](https://github.com/msgpack/msgpack-c) 2.1.4
- [netcdf-c](https://github.com/Unidata/netcdf-c) 4.9.2
- [ogg](https://gitlab.xiph.org/xiph/ogg.git) 1.3.5
- [oneTBB](https://github.com/oneapi-src/oneTBB) 2021.8.0
- [openblas](https://github.com/xianyi/OpenBLAS/releases/download/v0.3.21/OpenBLAS-0.3.21.zip) 0.3.21
- [opencl-icd-loader](https://github.com/KhronosGroup/OpenCL-ICD-Loader) 2023.02.06
- [opencv](https://github.com/opencv/opencv) 4.6.0
- [openexr](https://github.com/AcademySoftwareFoundation/openexr) 3.1.7
- [openjpeg](https://github.com/uclouvain/openjpeg) 2.5.0
- [openldap](https://www.openldap.org/software/download/OpenLDAP/openldap-release/openldap-2.4.59.tgz) 2.4.59
- [openssl](https://github.com/openssl/openssl) 1.1.1t
- [OpenVDB](https://github.com/AcademySoftwareFoundation/openvdb) 10.0.1
- [OpenVR](https://github.com/ValveSoftware/openvr) 1.0.17
- [opus](https://gitlab.xiph.org/xiph/opus.git) 1.3.1
- [opusfile](https://github.com/xiph/opusfile) 0.12
- [pcre2](https://github.com/PCRE2Project/pcre2.git) 10.42
- [pdcurses](https://github.com/wmcbrine/PDCurses) 3.9
- [pixman](https://www.cairographics.org/releases/pixman-0.42.2.tar.gz) 0.42.2+lgpl
- [portaudio](http://files.portaudio.com/archives/pa_stable_v190700_20210406.tgz) 19.7
- [portmidi](https://sourceforge.net/projects/portmedia/files/portmidi/v2.0.2/portmidi-v2.0.2.zip) 2.0.2
- [postgresql](https://ftp.postgresql.org/pub/source/v15.2/postgresql-15.2.tar.gz) 15.2
- [proj](https://download.osgeo.org/proj/proj-9.1.1.tar.gz) 9.1.1
- [protobuf](https://github.com/protocolbuffers/protobuf/releases/download/v21.12/protobuf-python-4.21.12.zip) 4.21.12
- [ptex](https://github.com/wdas/ptex) 2.4.2
- [pugixml](https://github.com/zeux/pugixml) 1.13
- [qhull](https://github.com/qhull/qhull) 4.0.0
- [rav1e](https://github.com/xiph/rav1e) 0.6.3
- [re2-2023-03](https://github.com/google/re2) 2023.03.01
- [rtmidi](http://www.music.mcgill.ca/~gary/rtmidi/release/rtmidi-5.0.0.tar.gz) 5.0.0
- [sdl](https://github.com/libsdl-org/SDL) 2.26.4
- [sdl_image](https://github.com/libsdl-org/SDL_image) 2.6.3
- [sdl_mixer](https://github.com/libsdl-org/SDL_mixer) 2.6.3
- [sdl_ttf](https://github.com/libsdl-org/SDL_ttf) 2.20.2
- [sheenbidi](https://github.com/Tehreer/SheenBidi) 2.6
- [snappy](https://github.com/google/snappy) 1.1.10
- [spatialindex](https://github.com/libspatialindex/libspatialindex/releases/download/1.9.3/spatialindex-src-1.9.3.tar.gz) 1.9.3
- [sqlite](https://github.com/sqlite/sqlite) 3.41.2
- [SVT-AV1](https://gitlab.com/AOMediaCodec/SVT-AV1) 1.4.1
- [SVT-HEVC](https://github.com/OpenVisualCloud/SVT-HEVC) 1.5.1
- [ta-lib](https://sourceforge.net/projects/ta-lib/files/ta-lib/0.4.0/ta-lib-0.4.0-msvc.zip) 0.4.0
- [thrift](https://github.com/apache/thrift) 0.18.1
- [udunits](https://artifacts.unidata.ucar.edu/repository/downloads-udunits/2.2.28/udunits-2.2.28.zip) 2.2.28
- [uriparser](https://github.com/uriparser/uriparser) 0.9.7
- [uthash](https://github.com/troydhanson/uthash) 2.3.0
- [vorbis](https://gitlab.xiph.org/xiph/vorbis.git) 1.3.7
- [vtk-m](https://gitlab.kitware.com/vtk/vtk-m/-/archive/v1.9.0/vtk-m-v1.9.0.tar.gz) 1.9.0
- [win-iconv](https://github.com/OgreTransporter/win-iconv) master
- [winflexbison](https://github.com/lexxmark/winflexbison) 2.5.25
- [winpty](https://github.com/rprichard/winpty) master
- [xgboost](https://github.com/dmlc/xgboost) 1.7.5
- [xz](https://git.tukaani.org/xz.git) 5.4.1
- [yaml-cpp](https://github.com/jbeder/yaml-cpp) 0.7.0
- [zfp](https://github.com/LLNL/zfp) 1.0.0
- [zlib-ng](https://github.com/zlib-ng/zlib-ng) 2.0.7
- [zlib](https://github.com/madler/zlib) 1.2.13
- [zopfli](https://github.com/google/zopfli) 1.0.3
- [zstd](https://github.com/facebook/zstd) 1.5.4

</details>

### Build system

<details>
  <summary>Details</summary>

- [Windows Dev Kit](https://learn.microsoft.com/en-us/windows/arm/dev-kit/) 2023
- [Visual Studio](https://visualstudio.microsoft.com/vs/community/) 2022 Community 17.5
- [Python](https://www.python.org/downloads/release/python-3112/) 3.11.3 (ARM64)
- [LLVM](https://github.com/llvm/llvm-project/releases/tag/llvmorg-15.0.3) 15.0.3-woa64
- [Flang](https://github.com/kaadam/flang/releases/tag/v0.3) 0.3
- [Rust](https://www.rust-lang.org/tools/install) 1.68
- [OpenJDK](https://learn.microsoft.com/en-us/java/openjdk/download) 17.0.6 LTS
- [Strawberry Perl](https://strawberryperl.com/) 5.32.1.1
- [MSYS2](https://www.msys2.org/) 20221028
- [Git](https://gitforwindows.org/) 2.39.2
- [CMake](https://cmake.org/download/) 3.24.3
- [DirectX SDK](https://www.microsoft.com/en-us/download/details.aspx?id=6812) 9.0c

</details>

## Release 2022.12.22

### Highlights

- Kivy
- spaCy

### Wheels

Binary wheels for the following packages are included in the
[release](https://github.com/cgohlke/win_arm64-wheels/releases/tag/v2022.12.22):

<details>
  <summary>Details</summary>

- [apsw](https://pypi.org/project/apsw/) 3.40.0.0
- [astropy](https://pypi.org/project/astropy/) 5.2
- [autobahn](https://pypi.org/project/autobahn/) 22.12.1
- [bitarray](https://pypi.org/project/bitarray/) 2.6.1
- [bitshuffle](https://pypi.org/project/bitshuffle/) 0.5.1
- [blosc2](https://pypi.org/project/blosc2/) 2.0.0
- [blosc](https://pypi.org/project/blosc/) 1.11.1
- [Cartopy](https://pypi.org/project/Cartopy/) 0.21.1
- [ceODBC](https://pypi.org/project/ceODBC/) 3.1
- [coverage](https://pypi.org/project/coverage/) 7.0.0
- [cx_Logging](https://pypi.org/project/cx_Logging/) 3.1.0
- [cymem](https://pypi.org/project/cymem/) 2.0.7
- [debugpy](https://pypi.org/project/debugpy/) 1.6.4
- [dukpy](https://pypi.org/project/dukpy/) 0.3.0
- [ephem](https://pypi.org/project/ephem/) 4.1.4
- [fabio](https://pypi.org/project/fabio/) 2022.12.1
- [fastparquet](https://pypi.org/project/fastparquet/) 2022.12.0
- [Fiona](https://pypi.org/project/Fiona/) 1.8.22
- [freetype_py](https://pypi.org/project/freetype_py/) 2.3.0
- [GDAL](https://pypi.org/project/GDAL/) 3.6.1
- [gevent](https://pypi.org/project/gevent/) 22.10.2
- [Glymur](https://pypi.org/project/Glymur/) 0.12.1
- [imagecodecs](https://pypi.org/project/imagecodecs/) 2022.12.22
- [Kivy](https://pypi.org/project/Kivy/) 2.1.0
- [lazy_object_proxy](https://pypi.org/project/lazy_object_proxy/) 1.8.0
- [line_profiler](https://pypi.org/project/line_profiler/) 4.0.2
- [lmdb](https://pypi.org/project/lmdb/) 1.4.0
- [lxml](https://pypi.org/project/lxml/) 4.9.2
- [maturin](https://pypi.org/project/maturin/) 0.14.6
- [moderngl](https://pypi.org/project/moderngl/) 5.7.4
- [msvc_runtime](https://pypi.org/project/msvc_runtime/) 14.34.31931
- [multidict](https://pypi.org/project/multidict/) 6.0.3
- [murmurhash](https://pypi.org/project/murmurhash/) 1.0.9
- [numcodecs](https://pypi.org/project/numcodecs/) 0.11.0
- [orjson](https://pypi.org/project/orjson/) 3.8.3
- [preshed](https://pypi.org/project/preshed/) 3.0.8
- [pycairo](https://pypi.org/project/pycairo/) 1.23.0
- [pycares](https://pypi.org/project/pycares/) 4.3.0
- [pycurl](https://pypi.org/project/pycurl/) 7.45.2
- [pyFltk](https://pypi.org/project/pyFltk/) 1.3.8
- [pygeos](https://pypi.org/project/pygeos/) 0.14.0
- [pylibCZIrw](https://pypi.org/project/pylibCZIrw/) 3.2.1
- [pylibjpeg_openjpeg](https://pypi.org/project/pylibjpeg_openjpeg/) 1.3.0
- [pyliblzfse](https://pypi.org/project/pyliblzfse/) 0.4.1
- [pymol](https://github.com/schrodinger/pymol-open-source) 2.6.0a0
- [pyproj](https://pypi.org/project/pyproj/) 3.4.1
- [pyroexr](https://pypi.org/project/pyroexr/) 0.2.0
- [PyStemmer](https://pypi.org/project/PyStemmer/) 2.2.0
- [PyX](https://pypi.org/project/PyX/) 0.16
- [PyYAML](https://pypi.org/project/PyYAML/) 6.0
- [qutip](https://pypi.org/project/qutip/) 4.7.1
- [rasterio](https://pypi.org/project/rasterio/) 1.3.4
- [recordclass](https://pypi.org/project/recordclass/) 0.18.0.1
- [scikit_learn](https://pypi.org/project/scikit_learn/) 1.2.0
- [spacy](https://pypi.org/project/spacy/) 3.4.4
- [SQLAlchemy](https://pypi.org/project/SQLAlchemy/) 1.4.45
- [srsly](https://pypi.org/project/srsly/) 2.4.5
- [thinc](https://pypi.org/project/thinc/) 8.1.6
- [tokenizers](https://pypi.org/project/tokenizers/) 0.13.2
- [tornado](https://pypi.org/project/tornado/) 6.2
- [ujson](https://pypi.org/project/ujson/) 5.6.0
- [yappi](https://pypi.org/project/yappi/) 1.4.0
- [yarl](https://pypi.org/project/yarl/) 1.8.2
- [yt](https://pypi.org/project/yt/) 4.1.3

</details>

### Libraries

The wheels include the following statically or dynamically linked libraries:

<details>
  <summary>Details</summary>

- [BerkeleyDB](https://github.com/berkeleydb/libdb/releases/download/v5.3.28/db-5.3.28.tar.gz) 5.3.28
- [boost](https://boostorg.jfrog.io/artifactory/main/release/1.81.0/source/boost_1_81_0.zip) 1.81.0
- [brotli](https://github.com/google/brotli) 1.0.9
- [brunsli](https://github.com/google/brunsli) 0.1
- [bzip2](https://sourceware.org/pub/bzip2/bzip2-1.0.8.tar.gz) 1.0.8
- [c-ares](https://c-ares.org/download/c-ares-1.18.1.tar.gz) 1.18.1
- [c-blosc2](https://github.com/Blosc/c-blosc2) 2.6.1
- [c-blosc](https://github.com/Blosc/c-blosc) 1.21.3
- [cairo](https://www.cairographics.org/releases/cairo-1.16.0.tar.xz) 1.16.0+lgpl
- [cfitsio](https://heasarc.gsfc.nasa.gov/FTP/software/fitsio/c/cfitsio-3.49.tar.gz) 3.49
- [charls](https://github.com/team-charls/charls) 2.3.4
- [curl](https://curl.se/download/curl-7.86.0.tar.gz) 7.86.0
- [directx-strmbase](https://www.microsoft.com/en-us/download/details.aspx?id=6812) 9.0c
- [expat](https://github.com/libexpat/libexpat/releases/download/R_2_4_9/expat-2.4.9.tar.gz) 2.4.9
- [flac](https://gitlab.xiph.org/xiph/flac.git) 1.4.2
- [flann](https://github.com/flann-lib/flann) 1.9.2
- [fltk](https://www.fltk.org/pub/fltk/1.3.8/fltk-1.3.8-source.tar.gz) 1.3.8
- [freeglut](https://github.com/FreeGLUTProject/freeglut) 3.4.0
- [freetds](https://www.freetds.org/files/stable/freetds-1.3.14.tar.gz) 1.3.14+lgpl
- [freetype](https://download.savannah.gnu.org/releases/freetype/freetype-2.12.1.tar.gz) 2.12.1
- [freexl](https://www.gaia-gis.it/gaia-sins/freexl-1.0.6.tar.gz) 1.0.6
- [gdal](https://github.com/OSGeo/gdal) 3.6.1
- [geos](https://download.osgeo.org/geos/geos-3.11.1.tar.bz2) 3.11.1+lgpl
- [giflib](https://sourceforge.net/projects/giflib/files/giflib-5.2.1.tar.gz) 5.2.1
- [gle](https://sourceforge.net/projects/gle/files/gle/gle-3.1.0/gle-3.1.0.tar.gz) 3.1.0
- [glew](https://github.com/nigels-com/glew/releases/download/glew-2.2.0/glew-2.2.0.tgz) 2.2.0
- [glfw](https://github.com/glfw/glfw) 3.3.8
- [harfbuzz](https://github.com/harfbuzz/harfbuzz) 5.3.1
- [hdf4](https://github.com/HDFGroup/hdf4) 4.2.15
- [hdf5](https://support.hdfgroup.org/ftp/HDF5/releases/hdf5-1.10/hdf5-1.10.9/src/hdf5-1.10.9.tar.gz) 1.10.9
- [icu4c](https://github.com/unicode-org/icu/releases/download/release-72-1/icu4c-72_1-src.zip) 72.1
- [imath](https://github.com/AcademySoftwareFoundation/Imath) 3.1.5
- [jasper](https://github.com/jasper-software/jasper) 4.0.0
- [json-c](https://github.com/json-c/json-c) 0.16
- [jxrlib](http://deb.debian.org/debian/pool/main/j/jxrlib/jxrlib_1.1.orig.tar.gz) 1.1
- [krb5](http://web.mit.edu/kerberos/dist/krb5/1.20/krb5-1.20.1.tar.gz) 1.20.1
- [lerc](https://github.com/Esri/lerc) 4.0.0
- [libaec](https://gitlab.dkrz.de/k202009/libaec) 1.0.6
- [libde265](https://github.com/strukturag/libde265) 1.0.9+lgpl
- [libdeflate](https://github.com/ebiggers/libdeflate) 1.15
- [libgeotiff](https://github.com/OSGeo/libgeotiff/releases/download/1.7.1/libgeotiff-1.7.1.tar.gz) 1.7.1
- [libgit2](https://github.com/libgit2/libgit2) 1.5.0
- [libjpeg-turbo](https://github.com/libjpeg-turbo/libjpeg-turbo) 2.1.4
- [libjxl](https://github.com/libjxl/libjxl) 0.7.0
- [libkml](https://github.com/libkml/libkml) 1.3.0
- [liblzf](http://dist.schmorp.de/liblzf/liblzf-3.6.tar.gz) 3.6
- [libmikmod](https://github.com/sezero/mikmod.git) 3.3.11.1+lgpl
- [libmodplug](https://github.com/Konstanty/libmodplug) master
- [libpng](https://github.com/glennrp/libpng) 1.6.39
- [libsodium](https://download.libsodium.org/libsodium/releases/libsodium-1.0.18.tar.gz) 1.0.18
- [libspatialite](https://www.gaia-gis.it/gaia-sins/libspatialite-5.0.1.tar.gz) 5.0.1
- [libssh2](https://www.libssh2.org/download/libssh2-1.10.0.tar.gz) 1.10.0
- [libtiff](https://gitlab.com/libtiff/libtiff) 4.5.0
- [libwebp](https://github.com/webmproject/libwebp) 1.2.4
- [libxml2](https://gitlab.gnome.org/GNOME/libxml2) 2.10.3
- [libxslt](https://gitlab.gnome.org/GNOME/libxslt) 1.1.37
- [libyaml](https://github.com/yaml/libyaml) 0.2.5
- [littlecms](https://github.com/mm2/Little-CMS) 2.14
- [lz4](https://github.com/lz4/lz4) 1.9.4
- [lzfse](https://github.com/lzfse/lzfse/) 1.0
- [lzham](https://github.com/richgel999/lzham_codec) master
- [minizip-ng](https://github.com/zlib-ng/minizip-ng) 3.0.7
- [mozjpeg](https://github.com/mozilla/mozjpeg) 4.1.1
- [mpg123](https://cytranet.dl.sourceforge.net/project/mpg123/mpg123/1.31.1/mpg123-1.31.1.tar.bz2) 1.31.1+lgpl
- [msgpack-c](https://github.com/msgpack/msgpack-c) 2.1.4
- [netcdf-c](https://downloads.unidata.ucar.edu/netcdf-c/4.8.1/netcdf-c-4.8.1.tar.gz) 4.8.1
- [ogg](https://gitlab.xiph.org/xiph/ogg.git) 1.3.5
- [openblas](https://github.com/xianyi/OpenBLAS/releases/download/v0.3.21/OpenBLAS-0.3.21.zip) 0.3.21
- [opencl-icd-loader](https://github.com/KhronosGroup/OpenCL-ICD-Loader) 2022.09.30
- [opencv](https://github.com/opencv/opencv) 4.6.0
- [openexr](https://github.com/AcademySoftwareFoundation/openexr) 3.1.5
- [openjpeg](https://github.com/uclouvain/openjpeg) 2.5.0
- [openldap](https://www.openldap.org/software/download/OpenLDAP/openldap-release/openldap-2.4.59.tgz) 2.4.59
- [openssl](https://github.com/openssl/openssl) 1.1.1s
- [opus](https://gitlab.xiph.org/xiph/opus.git) 1.3.1
- [opusfile](https://github.com/xiph/opusfile) 0.12
- [pcre2](https://github.com/PCRE2Project/pcre2.git) 10.42
- [pdcurses](https://github.com/wmcbrine/PDCurses) 3.9
- [pixman](https://www.cairographics.org/releases/pixman-0.42.2.tar.gz) 0.42.2+lgpl
- [pkgconf](https://distfiles.dereferenced.org/pkgconf/pkgconf-1.9.3.tar.xz) 1.9.3
- [portaudio](http://files.portaudio.com/archives/pa_stable_v190700_20210406.tgz) 19.7
- [portmidi](https://sourceforge.net/projects/portmedia/files/portmidi/v2.0.2/portmidi-v2.0.2.zip) 2.0.2
- [postgresql](https://ftp.postgresql.org/pub/source/v15.1/postgresql-15.1.tar.gz) 15.1
- [proj](https://download.osgeo.org/proj/proj-9.1.1.tar.gz) 9.1.1
- [protobuf](https://github.com/protocolbuffers/protobuf/releases/download/v21.10/protobuf-python-4.21.10.zip) 4.21.10
- [qhull](https://github.com/qhull/qhull) 4.0.0
- [rtmidi](http://www.music.mcgill.ca/~gary/rtmidi/release/rtmidi-5.0.0.tar.gz) 5.0.0
- [sdl](https://github.com/libsdl-org/SDL) 2.26.1
- [sdl_image](https://github.com/libsdl-org/SDL_image) 2.6.2
- [sdl_mixer](https://github.com/libsdl-org/SDL_mixer) 2.6.2
- [sdl_ttf](https://github.com/libsdl-org/SDL_ttf) 2.20.1
- [snappy](https://github.com/google/snappy) 1.1.9
- [spatialindex](https://github.com/libspatialindex/libspatialindex/releases/download/1.9.3/spatialindex-src-1.9.3.tar.gz) 1.9.3
- [sqlite](https://github.com/sqlite/sqlite) 3.40.0
- [ta-lib](https://sourceforge.net/projects/ta-lib/files/ta-lib/0.4.0/ta-lib-0.4.0-msvc.zip) 0.4.0
- [udunits](https://artifacts.unidata.ucar.edu/repository/downloads-udunits/2.2.28/udunits-2.2.28.zip) 2.2.28
- [uriparser](https://github.com/uriparser/uriparser) 0.9.7
- [vorbis](https://gitlab.xiph.org/xiph/vorbis.git) 1.3.7
- [win-iconv](https://github.com/OgreTransporter/win-iconv) master
- [winpty](https://github.com/rprichard/winpty) master
- [xz](https://git.tukaani.org/xz.git) 5.4.0
- [zfp](https://github.com/LLNL/zfp) 1.0.0
- [zlib-ng](https://github.com/zlib-ng/zlib-ng) 2.0.6
- [zlib](https://github.com/madler/zlib) 1.2.13
- [zopfli](https://github.com/google/zopfli) 1.0.3
- [zstd](https://github.com/facebook/zstd) 1.5.2

</details>

### Build system

<details>
  <summary>Details</summary>

- [Windows Dev Kit](https://learn.microsoft.com/en-us/windows/arm/dev-kit/) 2023
- [Visual Studio](https://visualstudio.microsoft.com/vs/community/) 2022 Community 17.4
- [Python](https://www.python.org/downloads/release/python-3110/) 3.11.1 (ARM64)
- [LLVM](https://github.com/llvm/llvm-project/releases/tag/llvmorg-15.0.3) 15.0.3-woa64
- [Flang](https://github.com/kaadam/flang/releases/tag/v0.3) 0.3
- [Rust](https://www.rust-lang.org/tools/install) 1.65.0
- [OpenJDK](https://learn.microsoft.com/en-us/java/openjdk/download) 17.0.5 LTS
- [Strawberry Perl](https://strawberryperl.com/) 5.32.1.1
- [MSYS2](https://www.msys2.org/) 20221028
- [Git](https://gitforwindows.org/) 2.38.1
- [CMake](https://cmake.org/download/) 3.24.3
- [DirectX SDK](https://www.microsoft.com/en-us/download/details.aspx?id=6812) 9.0c

</details>

## Release 2022.11.22

### Highlights

- Numpy linked to OpenBLAS
- AVIF
- GDAL 3.6
- Pygame

### Wheels

Binary wheels for the following packages are included in the
[release](https://github.com/cgohlke/win_arm64-wheels/releases/tag/v2022.11.22):

<details>
  <summary>Details</summary>

- [biopython](https://pypi.org/project/biopython/) 1.80
- [BTrees](https://pypi.org/project/BTrees/) 4.11.3
- [fastparquet](https://pypi.org/project/fastparquet/) 2022.11.0
- [Fiona](https://pypi.org/project/Fiona/) 1.8.22
- [GDAL](https://pypi.org/project/GDAL/) 3.6.0.1
- [imagecodecs](https://pypi.org/project/imagecodecs/) 2022.9.26
- [imgui](https://pypi.org/project/imgui/) 2.0.0
- [line_profiler](https://pypi.org/project/line_profiler/) 4.0.1
- [maturin](https://pypi.org/project/maturin/) 0.14.1
- [mercurial](https://pypi.org/project/mercurial/) 6.3.1
- [netCDF4](https://pypi.org/project/netCDF4/) 1.6.2
- [numpy](https://pypi.org/project/numpy/) 1.23.5
- [orjson](https://pypi.org/project/orjson/) 3.8.2
- [pandas](https://pypi.org/project/pandas/) 1.5.2
- [persistent](https://pypi.org/project/persistent/) 4.9.3
- [pillow_avif_plugin](https://pypi.org/project/pillow_avif_plugin/) 1.3.1
- [psycopg2](https://pypi.org/project/psycopg2/) 2.9.5
- [psygnal](https://pypi.org/project/psygnal/) 0.6.1
- [pycairo](https://pypi.org/project/pycairo/) 1.22.0
- [PyCifRW](https://pypi.org/project/PyCifRW/) 4.4.5
- [pygame](https://pypi.org/project/pygame/) 2.1.3
- [PyGreSQL](https://pypi.org/project/PyGreSQL/) 5.2.4
- [pymongo](https://pypi.org/project/pymongo/) 4.3.3
- [pymssql](https://pypi.org/project/pymssql/) 2.2.7
- [pyodbc](https://pypi.org/project/pyodbc/) 4.0.35
- [pyopencl](https://pypi.org/project/pyopencl/) 2022.3
- [pyzmq](https://pypi.org/project/pyzmq/) 24.0.1
- [rasterio](https://pypi.org/project/rasterio/) 1.3.4
- [scikit_image](https://pypi.org/project/scikit_image/) 0.19.3
- [scikit_learn](https://pypi.org/project/scikit_learn/) 1.1.3
- [scipy](https://pypi.org/project/scipy/) 1.9.3
- [simplejson](https://pypi.org/project/simplejson/) 3.18.0
- [vispy](https://pypi.org/project/vispy/) 0.12.1
- [yt](https://pypi.org/project/yt/) 4.1.2
- [zodbpickle](https://pypi.org/project/zodbpickle/) 2.6
- [zope.interface](https://pypi.org/project/zope.interface/) 5.5.2

</details>

### Libraries

The wheels include the following statically or dynamically linked libraries:

<details>
  <summary>Details</summary>

- [BerkeleyDB](https://github.com/berkeleydb/libdb/releases/download/v5.3.28/db-5.3.28.tar.gz) 5.3.28
- [boost](https://boostorg.jfrog.io/artifactory/main/release/1.80.0/source/boost_1_80_0.zip) 1.80.0
- [brotli](https://github.com/google/brotli) 1.0.9
- [brunsli](https://github.com/google/brunsli) 0.1
- [bzip2](https://sourceware.org/pub/bzip2/bzip2-1.0.8.tar.gz) 1.0.8
- [c-ares](https://c-ares.org/download/c-ares-1.18.1.tar.gz) 1.18.1
- [c-blosc2](https://github.com/Blosc/c-blosc2) 2.4.3
- [c-blosc](https://github.com/Blosc/c-blosc) 1.21.1
- [cairo](https://www.cairographics.org/releases/cairo-1.16.0.tar.xz) 1.16.0+lgpl
- [cfitsio](http://heasarc.gsfc.nasa.gov/FTP/software/fitsio/c/cfitsio-3.49.tar.gz) 3.49
- [charls](https://github.com/team-charls/charls) 2.3.4
- [curl](https://curl.se/download/curl-7.86.0.tar.gz) 7.86.0
- [expat](https://github.com/libexpat/libexpat/releases/download/R_2_4_9/expat-2.4.9.tar.gz) 2.4.9
- [flac](https://gitlab.xiph.org/xiph/flac.git) 1.4.2
- [flann](https://github.com/flann-lib/flann) 1.9.2
- [freeglut](https://github.com/FreeGLUTProject/freeglut) 3.4.0
- [freetds](https://www.freetds.org/files/stable/freetds-1.3.14.tar.gz) 1.3.14+lgpl
- [freetype](https://download.savannah.gnu.org/releases/freetype/freetype-2.12.1.tar.gz) 2.12.1
- [freexl](https://www.gaia-gis.it/gaia-sins/freexl-1.0.6.tar.gz) 1.0.6
- [gdal](https://github.com/OSGeo/gdal) 3.6.0.1
- [geos](https://download.osgeo.org/geos/geos-3.11.1.tar.bz2) 3.11.1+lgpl
- [giflib](https://sourceforge.net/projects/giflib/files/giflib-5.2.1.tar.gz) 5.2.1
- [gle](https://sourceforge.net/projects/gle/files/gle/gle-3.1.0/gle-3.1.0.tar.gz) 3.1.0
- [glew](https://github.com/nigels-com/glew/releases/download/glew-2.2.0/glew-2.2.0.tgz) 2.2.0
- [glfw](https://github.com/glfw/glfw) 3.3.8
- [harfbuzz](https://github.com/harfbuzz/harfbuzz) 5.3.1
- [hdf4](https://github.com/HDFGroup/hdf4) 4.2.15
- [hdf5](https://support.hdfgroup.org/ftp/HDF5/releases/hdf5-1.10/hdf5-1.10.9/src/hdf5-1.10.9.tar.gz) 1.10.9
- [icu4c](https://github.com/unicode-org/icu/releases/download/release-72-1/icu4c-72_1-src.zip) 72.1
- [imath](https://github.com/AcademySoftwareFoundation/Imath) 3.1.5
- [jasper](https://github.com/jasper-software/jasper) 4.0.0
- [json-c](https://github.com/json-c/json-c) 0.16
- [jxrlib](http://deb.debian.org/debian/pool/main/j/jxrlib/jxrlib_1.1.orig.tar.gz) 1.1
- [krb5](http://web.mit.edu/kerberos/dist/krb5/1.20/krb5-1.20.1.tar.gz) 1.20.1
- [lerc](https://github.com/Esri/lerc) 4.0.0
- [libaec](https://gitlab.dkrz.de/k202009/libaec) 1.0.6
- [libde265](https://github.com/strukturag/libde265) 1.0.9+lgpl
- [libdeflate](https://github.com/ebiggers/libdeflate) 1.14
- [libgeotiff](https://github.com/OSGeo/libgeotiff/releases/download/1.7.1/libgeotiff-1.7.1.tar.gz) 1.7.1
- [libgit2](https://github.com/libgit2/libgit2) 1.5.0
- [libjpeg-turbo](https://github.com/libjpeg-turbo/libjpeg-turbo) 2.1.4
- [libjxl](https://github.com/libjxl/libjxl) 0.7.0
- [libkml](https://github.com/libkml/libkml) 1.3.0
- [liblzf](http://dist.schmorp.de/liblzf/liblzf-3.6.tar.gz) 3.6
- [libmikmod](https://github.com/sezero/mikmod.git) 3.3.11.1+lgpl
- [libmodplug](https://github.com/Konstanty/libmodplug) master
- [libpng](https://github.com/glennrp/libpng) 1.6.39
- [libsodium](https://download.libsodium.org/libsodium/releases/libsodium-1.0.18.tar.gz) 1.0.18
- [libspatialite](https://www.gaia-gis.it/gaia-sins/libspatialite-5.0.1.tar.gz) 5.0.1
- [libssh2](https://www.libssh2.org/download/libssh2-1.10.0.tar.gz) 1.10.0
- [libtiff](https://gitlab.com/libtiff/libtiff) 4.4.0
- [libwebp](https://github.com/webmproject/libwebp) 1.2.4
- [libxml2](https://gitlab.gnome.org/GNOME/libxml2) 2.10.3
- [libxslt](https://gitlab.gnome.org/GNOME/libxslt) 1.1.37
- [littlecms](https://github.com/mm2/Little-CMS) 2.14
- [lz4](https://github.com/lz4/lz4) 1.9.4
- [minizip-ng](https://github.com/zlib-ng/minizip-ng) 3.0.7
- [mozjpeg](https://github.com/mozilla/mozjpeg) 4.1.1
- [mpg123](https://cytranet.dl.sourceforge.net/project/mpg123/mpg123/1.31.1/mpg123-1.31.1.tar.bz2) 1.31.1+lgpl
- [msgpack-c](https://github.com/msgpack/msgpack-c) 2.1.4
- [netcdf-c](https://downloads.unidata.ucar.edu/netcdf-c/4.8.1/netcdf-c-4.8.1.tar.gz) 4.8.1
- [ogg](https://gitlab.xiph.org/xiph/ogg.git) 1.3.5
- [openblas](https://github.com/xianyi/OpenBLAS/releases/download/v0.3.21/OpenBLAS-0.3.21.zip) 0.3.21
- [opencl-icd-loader](https://github.com/KhronosGroup/OpenCL-ICD-Loader) 2022.09.30
- [opencv](https://github.com/opencv/opencv) 4.6.0
- [openexr](https://github.com/AcademySoftwareFoundation/openexr) 3.1.5
- [openjpeg](https://github.com/uclouvain/openjpeg) 2.5.0
- [openldap](https://www.openldap.org/software/download/OpenLDAP/openldap-release/openldap-2.4.59.tgz) 2.4.59
- [openssl](https://github.com/openssl/openssl) 1.1.1s
- [opus](https://gitlab.xiph.org/xiph/opus.git) 1.3.1
- [opusfile](https://github.com/xiph/opusfile) 0.12
- [pdcurses](https://github.com/wmcbrine/PDCurses) 3.9
- [pixman](https://www.cairographics.org/releases/pixman-0.42.2.tar.gz) 0.42.2+lgpl
- [portaudio](http://files.portaudio.com/archives/pa_stable_v190700_20210406.tgz) 19.7
- [portmidi](https://sourceforge.net/projects/portmedia/files/portmidi/v2.0.2/portmidi-v2.0.2.zip) 2.0.2
- [postgresql](https://ftp.postgresql.org/pub/source/v15.1/postgresql-15.1.tar.gz) 15.1
- [proj](https://download.osgeo.org/proj/proj-9.1.0.tar.gz) 9.1.0
- [protobuf](https://github.com/protocolbuffers/protobuf/releases/download/v21.9/protobuf-python-4.21.9.zip) 4.21.9
- [rtmidi](http://www.music.mcgill.ca/~gary/rtmidi/release/rtmidi-5.0.0.tar.gz) 5.0.0
- [sdl](https://github.com/libsdl-org/SDL) 2.26.0
- [sdl_image](https://github.com/libsdl-org/SDL_image) 2.6.2
- [sdl_mixer](https://github.com/libsdl-org/SDL_mixer) 2.6.2
- [sdl_ttf](https://github.com/libsdl-org/SDL_ttf) 2.20.1
- [snappy](https://github.com/google/snappy) 1.1.8
- [spatialindex](https://github.com/libspatialindex/libspatialindex/releases/download/1.9.3/spatialindex-src-1.9.3.tar.gz) 1.9.3
- [sqlite](https://github.com/sqlite/sqlite) 3.39.4
- [ta-lib](https://sourceforge.net/projects/ta-lib/files/ta-lib/0.4.0/ta-lib-0.4.0-msvc.zip) 0.4.0
- [udunits](https://artifacts.unidata.ucar.edu/repository/downloads-udunits/2.2.28/udunits-2.2.28.zip) 2.2.28
- [uriparser](https://github.com/uriparser/uriparser) 0.9.7
- [vorbis](https://gitlab.xiph.org/xiph/vorbis.git) 1.3.7
- [win-iconv](https://github.com/OgreTransporter/win-iconv) master
- [winpty](https://github.com/rprichard/winpty) master
- [xz](https://sourceforge.net/projects/lzmautils/files/xz-5.2.8.tar.gz) 5.2.8
- [zfp](https://github.com/LLNL/zfp) 1.0.0
- [zlib-ng](https://github.com/zlib-ng/zlib-ng) 2.0.6
- [zlib](https://github.com/madler/zlib) 1.2.13
- [zopfli](https://github.com/google/zopfli) 1.0.3
- [zstd](https://github.com/facebook/zstd) 1.5.2

</details>

### Build system

<details>
  <summary>Details</summary>

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

</details>

## Release 2022.11.12

### Highlights

- Includes 200 wheels.
- Scipy stack: numpy, scipy, matplotlib, Pandas, h5py, scikit-image, scikit-learn, etc.
- GIS stack: GDAL, netCDF4, pyproj, Shapely, rasterio, basemap, Fiona, etc.
- Image IO and compression: Pillow, imagecodecs, aicspylibczi, Glymur, zfpy, blosc2, cramjam, etc.
- Pymol-open-source.

### Known issues

- The binaries underwent only limited testing.
- Numpy is not linked to OpenBLAS.
- OpenBLAS was built with an alpha version of flang.
- Scipy's Fortran bindings are unstable.
- Jupyter notebooks cannot connect to kernel.
- No GUI, CUDA, numba, napari packages.
- Few libraries do not compile, e.g., AVIF and VTK-m.
- Few compiler crashes during builds.

### Wheels

Binary wheels for the following packages are included in the
[release](https://github.com/cgohlke/win_arm64-wheels/releases/tag/v2022.11.12):

<details>
  <summary>Details</summary>

- [aggdraw](https://pypi.org/project/aggdraw/) 1.3.15
- [ahds](https://pypi.org/project/ahds/) 0.2.4
- [aicspylibczi](https://pypi.org/project/aicspylibczi/) 3.0.5
- [aiohttp](https://pypi.org/project/aiohttp/) 3.8.3
- [akima](https://pypi.org/project/akima/) 2022.9.12
- [apsw](https://pypi.org/project/apsw/) 3.39.4.0
- [argon2_cffi_bindings](https://pypi.org/project/argon2_cffi_bindings/) 21.2.0
- [astropy](https://pypi.org/project/astropy/) 5.1.1
- [atom](https://pypi.org/project/atom/) 0.8.2
- [autobahn](https://pypi.org/project/autobahn/) 22.7.1
- [basemap](https://pypi.org/project/basemap/) 1.3.6
- [bcrypt](https://pypi.org/project/bcrypt/) 4.0.1
- [bfloat16](https://pypi.org/project/bfloat16/) 1.1
- [bintrees](https://pypi.org/project/bintrees/) 2.2.0
- [biopython](https://pypi.org/project/biopython/) 1.79
- [bitarray](https://pypi.org/project/bitarray/) 2.6.0
- [bitshuffle](https://pypi.org/project/bitshuffle/) 0.4.2
- [blis](https://pypi.org/project/blis/) 0.9.1
- [blosc2](https://pypi.org/project/blosc2/) 0.5.2
- [blosc](https://pypi.org/project/blosc/) 1.10.6
- [Bottleneck](https://pypi.org/project/Bottleneck/) 1.3.5
- [Brotli](https://pypi.org/project/Brotli/) 1.0.9
- [bsddb3](https://pypi.org/project/bsddb3/) 6.2.9
- [bsdiff4](https://pypi.org/project/bsdiff4/) 1.2.2
- [BTrees](https://pypi.org/project/BTrees/) 4.11.1
- [cairocffi](https://pypi.org/project/cairocffi/) 1.4.0
- [caterva](https://pypi.org/project/caterva/) 0.7.3
- [centrosome](https://pypi.org/project/centrosome/) 1.2.1
- [cf_units](https://pypi.org/project/cf_units/) 3.1.1
- [cffi](https://pypi.org/project/cffi/) 1.15.1
- [cftime](https://pypi.org/project/cftime/) 1.6.2
- [chaco](https://pypi.org/project/chaco/) 5.1.0
- [chebyfit](https://pypi.org/project/chebyfit/) 2022.9.29
- [Cheetah3](https://pypi.org/project/Cheetah3/) 3.2.6.post1
- [contourpy](https://pypi.org/project/contourpy/) 1.0.6
- [coverage](https://pypi.org/project/coverage/) 6.5.0
- [cramjam](https://pypi.org/project/cramjam/) 2.6.2
- [curses](https://github.com/python/cpython/issues/47138) 2.2.1
- [Cython](https://pypi.org/project/Cython/) 0.29.32
- [discretize](https://pypi.org/project/discretize/) 0.8.2
- [dulwich](https://pypi.org/project/dulwich/) 0.20.50
- [elasticdeform](https://pypi.org/project/elasticdeform/) 0.5.0
- [enable](https://pypi.org/project/enable/) 5.3.1
- [enaml](https://pypi.org/project/enaml/) 0.15.2
- [ephem](https://pypi.org/project/ephem/) 4.1.3
- [fabio](https://pypi.org/project/fabio/) 0.14.0
- [fast_histogram](https://pypi.org/project/fast_histogram/) 0.11
- [fastparquet](https://pypi.org/project/fastparquet/) 0.8.3
- [fastrlock](https://pypi.org/project/fastrlock/) 0.8.1
- [fdint](https://pypi.org/project/fdint/) 2.0.2
- [Fiona](https://pypi.org/project/Fiona/) 1.8.22
- [fpzip](https://pypi.org/project/fpzip/) 1.2.0
- [freetype_py](https://pypi.org/project/freetype_py/) 2.3.0
- [frozenlist](https://pypi.org/project/frozenlist/) 1.3.3
- [GDAL](https://pypi.org/project/GDAL/) 3.5.3
- [gevent](https://pypi.org/project/gevent/) 22.10.2
- [glcontext](https://pypi.org/project/glcontext/) 2.3.7
- [glfw](https://pypi.org/project/glfw/) 2.5.5
- [glumpy](https://pypi.org/project/glumpy/) 1.2.0
- [Glymur](https://pypi.org/project/Glymur/) 0.12.0
- [greenlet](https://pypi.org/project/greenlet/) 2.0.1
- [h5py](https://pypi.org/project/h5py/) 3.7.0
- [imagecodecs](https://pypi.org/project/imagecodecs/) 2022.9.26
- [imread](https://pypi.org/project/imread/) 0.7.4
- [indexed_gzip](https://pypi.org/project/indexed_gzip/) 1.7.0
- [intbitset](https://pypi.org/project/intbitset/) 3.0.1
- [JCC](https://pypi.org/project/JCC/) 3.13
- [jellyfish](https://pypi.org/project/jellyfish/) 0.9.0
- [JPype1](https://pypi.org/project/JPype1/) 1.4.1
- [jsonobject](https://pypi.org/project/jsonobject/) 2.1.0
- [kiwisolver](https://pypi.org/project/kiwisolver/) 1.4.4
- [lfdfiles](https://pypi.org/project/lfdfiles/) 2022.9.29
- [line_profiler](https://pypi.org/project/line_profiler/) 4.0.0
- [lmdb](https://pypi.org/project/lmdb/) 1.3.0
- [lxml](https://pypi.org/project/lxml/) 4.9.1
- [lz4](https://pypi.org/project/lz4/) 4.0.2
- [mahotas](https://pypi.org/project/mahotas/) 1.4.13
- [marisa_trie](https://pypi.org/project/marisa_trie/) 0.7.8
- [MarkupSafe](https://pypi.org/project/MarkupSafe/) 2.1.1
- [matplotlib](https://pypi.org/project/matplotlib/) 3.6.2
- [maturin](https://pypi.org/project/maturin/) 0.13.7
- [mercurial](https://pypi.org/project/mercurial/) 6.2.3
- [MeshPy](https://pypi.org/project/MeshPy/) 2022.1.3
- [moderngl](https://pypi.org/project/moderngl/) 5.7.2
- [mplcairo](https://pypi.org/project/mplcairo/) 0.5
- [msgpack](https://pypi.org/project/msgpack/) 1.0.4
- [multidict](https://pypi.org/project/multidict/) 6.0.2
- [naturalneighbor](https://pypi.org/project/naturalneighbor/) 0.2.1
- [ndimage](https://github.com/scipy/scipy/tree/main/scipy/ndimage) 1.3.1
- [ndindex](https://pypi.org/project/ndindex/) 1.6
- [netCDF4](https://pypi.org/project/netCDF4/) 1.6.1
- [netifaces](https://pypi.org/project/netifaces/) 0.11.0
- [noise](https://pypi.org/project/noise/) 1.2.3
- [numcodecs](https://pypi.org/project/numcodecs/) 0.10.2
- [numexpr](https://pypi.org/project/numexpr/) 2.8.4
- [numpy](https://pypi.org/project/numpy/) 1.23.4
- [numpy_quaternion](https://pypi.org/project/numpy_quaternion/) 2022.4.2
- [numpy_stl](https://pypi.org/project/numpy_stl/) 2.17.1
- [opencv_python](https://pypi.org/project/opencv_python/) 4.6.0
- [OpenEXR](https://pypi.org/project/OpenEXR/) 1.3.9
- [orjson](https://pypi.org/project/orjson/) 3.8.1
- [pandas](https://pypi.org/project/pandas/) 1.5.1
- [persistent](https://pypi.org/project/persistent/) 4.9.2
- [Pillow](https://pypi.org/project/Pillow/) 9.3.0
- [protobuf](https://pypi.org/project/protobuf/) 4.21.9
- [psf](https://pypi.org/project/psf/) 2022.9.26
- [psutil](https://pypi.org/project/psutil/) 5.9.4
- [psycopg2](https://pypi.org/project/psycopg2/) 2.9.5
- [psygnal](https://pypi.org/project/psygnal/) 0.6.0.post0
- [pyamg](https://pypi.org/project/pyamg/) 4.2.3
- [pyasn](https://pypi.org/project/pyasn/) 1.6.1
- [PyAudio](https://pypi.org/project/PyAudio/) 0.2.12
- [pycairo](https://pypi.org/project/pycairo/) 1.21.0
- [pycares](https://pypi.org/project/pycares/) 4.2.2
- [PyCifRW](https://pypi.org/project/PyCifRW/) 4.4.3
- [Pycluster](https://pypi.org/project/Pycluster/) 1.59
- [pycosat](https://pypi.org/project/pycosat/) 0.6.4
- [pycurl](https://pypi.org/project/pycurl/) 7.45.1
- [pydantic](https://pypi.org/project/pydantic/) 1.10.2
- [pyeda](https://pypi.org/project/pyeda/) 0.28.0
- [pyerfa](https://pypi.org/project/pyerfa/) 2.0.0.1
- [pygeos](https://pypi.org/project/pygeos/) 0.13.0
- [pygit2](https://pypi.org/project/pygit2/) 1.11.1
- [PyGreSQL](https://pypi.org/project/PyGreSQL/) 5.2.4
- [pyhdf](https://pypi.org/project/pyhdf/) 0.10.5
- [PyICU](https://pypi.org/project/PyICU/) 2.10.2
- [pyjnius](https://pypi.org/project/pyjnius/) 1.4.2
- [pylibjpeg_libjpeg](https://pypi.org/project/pylibjpeg_libjpeg/) 1.3.2
- [pylibjpeg_openjpeg](https://pypi.org/project/pylibjpeg_openjpeg/) 1.2.1
- [pylibjpeg_rle](https://pypi.org/project/pylibjpeg_rle/) 1.3.0
- [pymatgen](https://pypi.org/project/pymatgen/) 2022.11.7
- [PyMCubes](https://pypi.org/project/PyMCubes/) 0.1.2
- [pymol](https://github.com/schrodinger/pymol-open-source) 2.6.0a0
- [pymongo](https://pypi.org/project/pymongo/) 4.3.2
- [pymssql](https://pypi.org/project/pymssql/) 2.2.5
- [PyNaCl](https://pypi.org/project/PyNaCl/) 1.5.0
- [pyodbc](https://pypi.org/project/pyodbc/) 4.0.34
- [pyopencl](https://pypi.org/project/pyopencl/) 2022.2.4
- [PyOpenGL](https://pypi.org/project/PyOpenGL/) 3.1.6
- [PyOpenGL_accelerate](https://pypi.org/project/PyOpenGL_accelerate/) 3.1.6
- [pyproj](https://pypi.org/project/pyproj/) 3.4.0
- [pyreadstat](https://pypi.org/project/pyreadstat/) 1.2.0
- [pyrsistent](https://pypi.org/project/pyrsistent/) 0.19.2
- [pyRXP](https://pypi.org/project/pyRXP/) 3.0.1
- [pystackreg](https://pypi.org/project/pystackreg/) 0.2.7
- [python_javabridge](https://pypi.org/project/python_javabridge/) 4.0.3
- [python_ldap](https://pypi.org/project/python_ldap/) 3.4.3
- [python_lzf](https://pypi.org/project/python_lzf/) 0.2.4
- [python_rapidjson](https://pypi.org/project/python_rapidjson/) 1.9
- [python_snappy](https://pypi.org/project/python_snappy/) 0.6.1
- [PyTurboJPEG](https://pypi.org/project/PyTurboJPEG/) 1.7.0
- [PyWavelets](https://pypi.org/project/PyWavelets/) 1.4.1
- [pywin32](https://pypi.org/project/pywin32/) 305
- [pywinpty](https://pypi.org/project/pywinpty/) 2.0.9
- [PyYAML](https://pypi.org/project/PyYAML/) 6.0
- [pyzmq](https://pypi.org/project/pyzmq/) 24.0.1
- [rasterio](https://pypi.org/project/rasterio/) 1.3.3
- [recordclass](https://pypi.org/project/recordclass/) 0.18.0.1
- [regex](https://pypi.org/project/regex/) 2022.10.31
- [reportlab](https://pypi.org/project/reportlab/) 3.6.12
- [rtmidi_python](https://pypi.org/project/rtmidi_python/) 0.2.2
- [Rtree](https://pypi.org/project/Rtree/) 1.0.1
- [ruamel.yaml.clib](https://pypi.org/project/ruamel.yaml.clib/) 0.2.7
- [scikit_image](https://pypi.org/project/scikit_image/) 0.19.3
- [scikit_learn](https://pypi.org/project/scikit_learn/) 1.1.3
- [scikits.vectorplot](https://pypi.org/project/scikits.vectorplot/) 0.1.1
- [SciPy](https://pypi.org/project/SciPy/) 1.9.3
- [setproctitle](https://pypi.org/project/setproctitle/) 1.3.2
- [sfepy](https://pypi.org/project/sfepy/) 2022.3
- [Shapely](https://pypi.org/project/Shapely/) 1.8.5.post1
- [simplejson](https://pypi.org/project/simplejson/) 3.17.6
- [SimpleParse](https://pypi.org/project/SimpleParse/) 2.2.3
- [spectrum](https://pypi.org/project/spectrum/) 0.8.1
- [spglib](https://pypi.org/project/spglib/) 2.0.2
- [SQLAlchemy](https://pypi.org/project/SQLAlchemy/) 1.4.44
- [statsmodels](https://pypi.org/project/statsmodels/) 0.13.5
- [TA_Lib](https://pypi.org/project/TA_Lib/) 0.4.25
- [tables](https://pypi.org/project/tables/) 3.7.0
- [thrift](https://pypi.org/project/thrift/) 0.16.0
- [tornado](https://pypi.org/project/tornado/) 6.2
- [traits](https://pypi.org/project/traits/) 6.4.1
- [transformations](https://pypi.org/project/transformations/) 2022.9.26
- [triangle](https://pypi.org/project/triangle/) 20220202
- [udunits2](https://github.com/Unidata/UDUNITS-2) 2.2.28
- [VideoCapture](https://videocapture.sourceforge.net/) 0.9.5
- [vidsrc](https://pypi.org/project/vidsrc/) 2022.9.28
- [vispy](https://pypi.org/project/vispy/) 0.12.0
- [win_arm64_runtime_dlls](https://github.com/cgohlke/win_arm64-wheels) 2022.11.12
- [wordcloud](https://pypi.org/project/wordcloud/) 1.8.2.2
- [wrapt](https://pypi.org/project/wrapt/) 1.14.1
- [xxhash](https://pypi.org/project/xxhash/) 3.1.0
- [yarl](https://pypi.org/project/yarl/) 1.8.1
- [yt](https://pypi.org/project/yt/) 4.1.1
- [zfpy](https://pypi.org/project/zfpy/) 1.0.0
- [zodbpickle](https://pypi.org/project/zodbpickle/) 2.5
- [zope.interface](https://pypi.org/project/zope.interface/) 5.5.1
- [zopflipy](https://pypi.org/project/zopflipy/) 1.8
- [zstd](https://pypi.org/project/zstd/) 1.5.2.6

</details>

### Libraries

The wheels include the following statically or dynamically linked libraries:

<details>
  <summary>Details</summary>

- [berkeleydb](https://github.com/berkeleydb/libdb/releases/download/v5.3.28/db-5.3.28.tar.gz) 5.3.28
- [boost](https://boostorg.jfrog.io/artifactory/main/release/1.80.0/source/boost_1_80_0.zip) 1.80.0
- [brotli](https://github.com/google/brotli) 1.0.9
- [brunsli](https://github.com/google/brunsli) 0.1
- [bzip2](https://sourceware.org/pub/bzip2/bzip2-1.0.8.tar.gz) 1.0.8
- [c-ares](https://c-ares.org/download/c-ares-1.18.1.tar.gz) 1.18.1
- [c-blosc2](https://github.com/Blosc/c-blosc2) 2.4.3
- [c-blosc](https://github.com/Blosc/c-blosc) 1.21.1
- [cairo](https://www.cairographics.org/releases/cairo-1.16.0.tar.xz) 1.16.0
- [cfitsio](http://heasarc.gsfc.nasa.gov/FTP/software/fitsio/c/cfitsio-3.49.tar.gz) 3.49
- [charls](https://github.com/team-charls/charls) 2.3.4
- [curl](https://curl.se/download/curl-7.86.0.tar.gz) 7.86.0
- [expat](https://github.com/libexpat/libexpat/releases/download/R_2_4_9/expat-2.4.9.tar.gz) 2.4.9
- [freeglut](https://github.com/FreeGLUTProject/freeglut) 3.4.0
- [freetds](https://www.freetds.org/files/stable/freetds-1.3.13.tar.gz) 1.3.13
- [freetype](https://download.savannah.gnu.org/releases/freetype/freetype-2.12.1.tar.gz) 2.12.1
- [freexl](https://www.gaia-gis.it/gaia-sins/freexl-1.0.6.tar.gz) 1.0.6
- [GDAL](https://github.com/OSGeo/gdal) 3.5.3
- [geos](https://download.osgeo.org/geos/geos-3.11.0.tar.bz2) 3.11.0
- [giflib](https://sourceforge.net/projects/giflib/files/giflib-5.2.1.tar.gz) 5.2.1
- [gle](https://sourceforge.net/projects/gle/files/gle/gle-3.1.0/gle-3.1.0.tar.gz) 3.1.0
- [glew](https://github.com/nigels-com/glew/releases/download/glew-2.2.0/glew-2.2.0.tgz) 2.2.0
- [glfw](https://github.com/glfw/glfw) 3.3.8
- [harfbuzz](https://github.com/harfbuzz/harfbuzz) 5.3.1
- [hdf4](https://github.com/HDFGroup/hdf4) 4.2.15
- [hdf5](https://support.hdfgroup.org/ftp/HDF5/releases/hdf5-1.10/hdf5-1.10.9/src/hdf5-1.10.9.tar.gz) 1.10.9
- [icu](https://github.com/unicode-org/icu/releases/download/release-72-1/icu4c-72_1-src.zip) 72.1
- [imath](https://github.com/AcademySoftwareFoundation/Imath) 3.1.5
- [jasper](https://github.com/jasper-software/jasper) 4.0.0
- [json-c](https://github.com/json-c/json-c) 0.16
- [jxrlib](http://deb.debian.org/debian/pool/main/j/jxrlib/jxrlib_1.1.orig.tar.gz) 1.1
- [lcms2](https://github.com/mm2/Little-CMS) 2.14
- [lerc](https://github.com/Esri/lerc) 4.0.0
- [libaec](https://gitlab.dkrz.de/k202009/libaec) 1.0.6
- [libdeflate](https://github.com/ebiggers/libdeflate) 1.14
- [libgeotiff](https://github.com/OSGeo/libgeotiff/releases/download/1.7.1/libgeotiff-1.7.1.tar.gz) 1.7.1
- [libgit2](https://github.com/libgit2/libgit2) 1.5.0
- [libjpeg-turbo](https://github.com/libjpeg-turbo/libjpeg-turbo) 2.1.4
- [libjxl](https://github.com/libjxl/libjxl) 0.7.0
- [libkml](https://github.com/libkml/libkml) 1.3.0
- [liblzf](http://dist.schmorp.de/liblzf/liblzf-3.6.tar.gz) 3.6
- [libpng](https://github.com/glennrp/libpng) 1.6.38
- [libsodium](https://download.libsodium.org/libsodium/releases/libsodium-1.0.18.tar.gz) 1.0.18
- [libspatialite](https://www.gaia-gis.it/gaia-sins/libspatialite-5.0.1.tar.gz) 5.0.1
- [libssh2](https://www.libssh2.org/download/libssh2-1.10.0.tar.gz) 1.10.0
- [libtiff](https://gitlab.com/libtiff/libtiff) 4.4.0
- [libwebp](https://github.com/webmproject/libwebp) 1.2.4
- [libxml2](https://gitlab.gnome.org/GNOME/libxml2) 2.10.3
- [libxslt](https://gitlab.gnome.org/GNOME/libxslt) 1.1.37
- [lz4](https://github.com/lz4/lz4) 1.9.4
- [minizip-ng](https://github.com/zlib-ng/minizip-ng) 3.0.7
- [mozjpeg](https://github.com/mozilla/mozjpeg) 4.1.1
- [msgpack-c](https://github.com/msgpack/msgpack-c) 2.1.4
- [netcdf-c](https://downloads.unidata.ucar.edu/netcdf-c/4.8.1/netcdf-c-4.8.1.tar.gz) 4.8.1
- [openblas](https://github.com/xianyi/OpenBLAS/releases/download/v0.3.21/OpenBLAS-0.3.21.zip) 0.3.21
- [opencl-icd-loader](https://github.com/KhronosGroup/OpenCL-ICD-Loader) 2022.09.30
- [opencv](https://github.com/opencv/opencv) 4.6.0
- [openexr](https://github.com/AcademySoftwareFoundation/openexr) 3.1.5
- [openjpeg](https://github.com/uclouvain/openjpeg) 2.5.0
- [openldap](https://www.openldap.org/software/download/OpenLDAP/openldap-release/openldap-2.4.59.tgz) 2.4.59
- [openssl](https://github.com/openssl/openssl) 1.1.1s
- [pdcurses](https://github.com/wmcbrine/PDCurses) 3.9
- [pixman](https://www.cairographics.org/releases/pixman-0.42.2.tar.gz) 0.42.2
- [portaudio](http://files.portaudio.com/archives/pa_stable_v190700_20210406.tgz) 19.7
- [portmidi](https://sourceforge.net/projects/portmedia/files/portmidi/v2.0.2/portmidi-v2.0.2.zip) 2.0.2
- [postgresql](https://ftp.postgresql.org/pub/source/v15.0/postgresql-15.0.tar.gz) 15.0
- [proj](https://download.osgeo.org/proj/proj-9.1.0.tar.gz) 9.1.0
- [protobuf](https://github.com/protocolbuffers/protobuf/releases/download/v21.9/protobuf-python-4.21.9.zip) 4.21.9
- [rtmidi](http://www.music.mcgill.ca/~gary/rtmidi/release/rtmidi-5.0.0.tar.gz) 5.0.0
- [snappy](https://github.com/google/snappy) 1.1.8
- [spatialindex](https://github.com/libspatialindex/libspatialindex/releases/download/1.9.3/spatialindex-src-1.9.3.tar.gz) 1.9.3
- [sqlite](https://github.com/sqlite/sqlite) 3.39.4
- [ta-lib](https://sourceforge.net/projects/ta-lib/files/ta-lib/0.4.0/ta-lib-0.4.0-msvc.zip) 0.4.0
- [udunits](https://artifacts.unidata.ucar.edu/repository/downloads-udunits/2.2.28/udunits-2.2.28.zip) 2.2.28
- [uriparser](https://github.com/uriparser/uriparser) 0.9.7
- [win-iconv](https://github.com/OgreTransporter/win-iconv) master
- [winpty](https://github.com/rprichard/winpty) master
- [xz-lzma](https://github.com/xz-mirror/xz) 5.2.7
- [zfp](https://github.com/LLNL/zfp) 1.0.0
- [zlib-ng](https://github.com/zlib-ng/zlib-ng) 2.0.6
- [zlib](https://github.com/madler/zlib) 1.2.13
- [zopfli](https://github.com/google/zopfli) 1.0.3
- [zstd](https://github.com/facebook/zstd) 1.5.2

</details>

### Build system

<details>
  <summary>Details</summary>

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

</details>