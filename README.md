# Systemy Rekomendacyjne 

Projekt II

Autor: Rafał Piskorski

## Opis
Celem projektu było utworzenie modelu zdolnego do dokonywania rekomendacji z jak najwyższą dokładnością. System trenowany był na historycznych danych hotelowych a rekomendacje przez niego tworzone przypisują daną ofertę hotelową konkretnemu użytkownikowi tak, aby prawdopodobieństwo jej wykupienia było jak najwyższe.

## Szczegóły

Głównym narzędziem, którym posłużono się w trakcie wykonywania projektu był pytorch v.1.8.0. Za jego pomocą zrealizowano sieć neuronową złożoną z czterech warstw w tym dwóch warstw ukrytych. Sieć dokonuje także operacji normalizacji oraz obliczenia podobieństwa cosinusowego wektorów opisujących użytkownika i ofertę hotelową.

Otrzymany, finalny wynik ostatecznej ewaluacji wynosi  0.056598 .

Projekt został utworzony w pythonie v 3.8.0.
Podstawowymi pakietami, które umożliwiły dokonanie operacji na zbiorze danych są pandas oraz numpy.

## Pakiety + wersje

	+_libgcc_mutex-0.1 
    +ca-certificates-2021.1.19 
    +certifi-2020.12.5 
    +libedit-3.1.20191231 
    +libffi-3.2.1 
    +libgcc-ng-9.1.0 
    +libstdcxx-ng-9.1.0 
    +ncurses-6.2 
    +openssl-1.1.1j 
    +pip-21.0.1 
    +python-3.8.0 
    +readline-7.0 
    +setuptools-52.0.0 
    +sqlite-3.33.0 
    +tk-8.6.10 
    +wheel-0.36.2
    +xz-5.2.5 
    +zlib-1.2.11 

	+async_generator-1.10
    +attrs-20.3.0
    +backcall-0.2.0
    +blas-1.0 
    +bleach-3.3.0
    +dbus-1.13.18 
    +decorator-4.4.2
    +defusedxml-0.7.1
    +entrypoints-0.3 
    +expat-2.2.10 
    +fontconfig-2.13.1 
    +freetype-2.10.4 
    +glib-2.63.1 
    +gst-plugins-base-1.14.0 
    +gstreamer-1.14.0 
    +icu-58.2 
    +importlib-metadata-2.0.0
    +importlib_metadata-2.0.0
    +intel-openmp-2020.2 
    +ipykernel-5.3.4 
    +ipython-7.21.0 
    +ipython_genutils-0.2.0
    +ipywidgets-7.6.3
    +jedi-0.17.0 
    +jinja2-2.11.3
    +joblib-1.0.1
    +jpeg-9b 
    +jsonschema-3.2.0
    +jupyter-1.0.0 
    +jupyter_client-6.1.7
    +jupyter_console-6.2.0
    +jupyter_core-4.7.1 
    +jupyterlab_pygments-0.1.2
    +jupyterlab_widgets-1.0.0
    +libgfortran-ng-7.3.0 
    +libpng-1.6.37 
    +libsodium-1.0.18 
    +libuuid-1.0.3 
    +libxcb-1.14 
    +libxml2-2.9.10 
    +markupsafe-1.1.1 
    +mistune-0.8.4 
    +mkl-2020.2 
    +mkl-service-2.3.0 
    +mkl_fft-1.3.0 
    +mkl_random-1.1.1 
    +nbclient-0.5.3
    +nbconvert-6.0.7 
    +nbformat-5.1.2
    +nest-asyncio-1.5.1
    +notebook-6.0.3 
    +numpy-1.19.2 
    +numpy-base-1.19.2 
    +packaging-20.9
    +pandas-1.2.3 
    +pandoc-2.11 
    +pandocfilters-1.4.3 
    +parso-0.8.1
    +pcre-8.44 
    +pexpect-4.8.0
    +pickleshare-0.7.5
    +prometheus_client-0.9.0
    +prompt-toolkit-3.0.8
    +prompt_toolkit-3.0.8
    +ptyprocess-0.7.0
    +pygments-2.8.1
    +pyparsing-2.4.7
    +pyqt-5.9.2 
    +pyrsistent-0.17.3 
    +python-dateutil-2.8.1
    +pytz-2021.1
    +pyzmq-20.0.0 
    +qt-5.9.7 
    +qtconsole-5.0.2
    +qtpy-1.9.0
    +scikit-learn-0.24.1 
    +scipy-1.6.1 
    +send2trash-1.5.0
    +sip-4.19.13 
    +six-1.15.0 
    +terminado-0.9.2 
    +testpath-0.4.4
    +threadpoolctl-2.1.0
    +tornado-6.1 
    +traitlets-5.0.5
    +wcwidth-0.2.5
    +webencodings-0.5.1 
    +widgetsnbextension-3.5.1 
    +zeromq-4.3.3 
    +zipp-3.4.0

	+bzip2-1.0.8 
    +cudatoolkit-10.2.89 
    +ffmpeg-4.3 (pytorch/linux-64)
    +gmp-6.2.1 
    +gnutls-3.6.5 
    +lame-3.100 
    +lcms2-2.11 
    +libiconv-1.15 
    +libtiff-4.1.0 
    +libuv-1.40.0 
    +lz4-c-1.9.3 
    +nettle-3.4.1 
    +ninja-1.10.2 
    +olefile-0.46
    +openh264-2.1.0 
    +pillow-8.1.2 
    +pytorch-1.8.0 (pytorch/linux-64)
    +torchaudio-0.8.0 (pytorch/linux-64)
    +torchvision-0.9.0 (pytorch/linux-64)
    +typing_extensions-3.7.4.3
    +zstd-1.4.5 

	+cycler-0.10.0 
    +kiwisolver-1.3.1 
    +matplotlib-3.3.4 
    +matplotlib-base-3.3.4 

	+seaborn-0.11.1

	+patsy-0.5.1 
    +statsmodels-0.12.2 






