# B3_Coin

b3coin

#How to Build
1. clean the src by "make clean"
2. Build leveldb "cd <dir>/src/levedb  TARGET_OS=NATIVE_WINDOWS make libleveldb.a libmemenv.a"
3. Build secp256k1 "cd <to secp256k1> ./autogen.sh ./configure --enable-module-recovery make"
4. Now qmake B3coin-qt.pro make
