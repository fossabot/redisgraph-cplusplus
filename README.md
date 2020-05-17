Beta Version.
## Dependencies:
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fdeviprasad97%2Fredisgraph-cplusplus.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fdeviprasad97%2Fredisgraph-cplusplus?ref=badge_shield)

*   Hiredis
*   C++ 11
##### Hiredis:
```console
    git clone https://github.com/redis/hiredis
    mkdir build && cd build
    cmake ..
    make -j4
    sudo make install
```
This will install Hiredis to */usr/local/include/hiredis/*

### In Development
#### __TODO__ (CURRENT):
 *        FULL PARSING SUPPORT (Done)
 *        ResultScalarType Implementaion (Done)
 *        Functional Query implementation (Partial Done)
 *        Statistics Implementation  
 *        RedisGraph Caches (Single Graph) added
 *        Result Set implemented accoroing to RedisGraph client specification
 *        Comapact query instruction support added
  
#### TODO (PENDING):  
 *        MULTI THREAD IMPLEMENTATION  
 *        PUB-SUB (Transcation Watch)  
 *        CONTEXTED API  
 *        PROCEDURE test  
 


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fdeviprasad97%2Fredisgraph-cplusplus.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fdeviprasad97%2Fredisgraph-cplusplus?ref=badge_large)