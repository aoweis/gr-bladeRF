# gr-bladeRF

This is a fork of GNU Radio source and sink blocks for bladeRF devices. The only difference is the reduction in the default number and size of the Tx buffers in the sink to reduce latency.

## bladeRF wiki

* [bladeRF wiki](https://github.com/Nuand/bladeRF/wiki)

## Installation

Build from source

    git clone https://github.com/Nuand/gr-bladeRF.git
    cd gr-bladeRF
    mkdir build
    cd build
    cmake ..
    make -j4
    sudo make install

## GNURadio-Companion Examples
Run FM-receiver example:

    cd 
    gnuradio-companion gr-bladeRF/apps/fm_receiver.grc

## Run on Raspberry
   
   [How to install gr-bladeRF on Raspberry Pi 4
](raspberry/)



