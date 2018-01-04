# bullet-physics-vita
bullet physics engine ver. 3-2.87 for Vita

To build and install:

mkdir vita
cd vita
cmake -DCMAKE_TOOLCHAIN_FILE=$VITASDK/share/vita.toolchain.cmake ../
make
make install
