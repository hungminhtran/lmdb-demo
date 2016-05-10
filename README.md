# lmdb-demo \n demo code for lmdb library
Must create folder name in mdb_env_open()
In this case mdb_env_open(env, "./testdb", 0, 0664); a folder name testdb must be created in current directory of code file
build command:
gcc -o lmdb-demo.out lmdb-demo.c -llmdb -ldb
lmdb: link to lmdb lib
db: link to db lib if necessary
