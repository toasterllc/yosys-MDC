## MDC Build Instructions

    make config-clang
    make -j$(nproc)
    make install PREFIX=$PWD/install
