# read4me-api

### Read4me PDF to voice converter API

##### 1. Requirements:
 
* [espeak](https://github.com/rhdunn/espeak)
* [PoDoFo](https://github.com/mekentosj/podofo)
    
##### 2. Using:

##### 2.1. espeak:

* Compile espeak:
    
    `cd app/libs/espeak/src && make`
        

##### 2.2. PoDoFo:

* Compile PoDoFo:
    
    `cd app/libs/` 
    
    `mkdir podofo-build && cd $_`
    
    `cmake -G "Unix Makefiles" -DCMAKE_INSTALL_PREFIX="$HOME/podofo" ../podofo`
    
    `make && make install`
    
##### 3. Compile:

    `cd app && make`

##### 4. Contributors:

See project contributors [here](https://github.com/read4me/read4me-api/graphs/contributors).
