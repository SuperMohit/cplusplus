# Rate Limiting using Redis and hiredis client

1. Create a shared library by running $make install after cloning https://github.com/redis/hiredis 
2. LD_LIBRARY_PATH=/usr/local/lib
3. ldconfig
4. g++ rate_redis.cpp -lhiredis -o rate.o


