# bullet-physics-vita
bullet physics engine ver. 3-2.87 for Vita

To build and install:

1. Install newest VitaSDK using https://github.com/vitasdk/vdpm  

2. Build bullet lib  
   mkdir vita  
   cd vita  
   cmake -DCMAKE_TOOLCHAIN_FILE=$VITASDK/share/vita.toolchain.cmake ../  
   make  
   make install  
   
