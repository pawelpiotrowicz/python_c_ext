
python3-dbg setup.py build 
sudo python3-dbg setup.py install








x86_64-linux-gnu-gcc -pthread -g -Og -Wall -g -Og -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2 -fPIC -I/usr/include/python3.6dm -c test.c -o build/temp.linux-x86_64-3.6-pydebug/test.o
x86_64-linux-gnu-gcc -pthread -shared -Wl,-O1 -Wl,-Bsymbolic-functions -Wl,-Bsymbolic-functions -Wl,-z,relro -Wl,-Bsymbolic-functions -Wl,-z,relro -g -Og -fstack-protector-strong -Wformat -Werror=format-security -Wdate-time -D_FORTIFY_SOURCE=2 build/temp.linux-x86_64-3.6-pydebug/test.o -o build/lib.linux-x86_64-3.6-pydebug/myModule.cpython-36dm-x86_64-linux-gnu.so
running install_lib
copying build/lib.linux-x86_64-3.6-pydebug/myModule.cpython-36dm-x86_64-linux-gnu.so -> /usr/local/lib/python3.6/dist-packages
running install_egg_info
Removing /usr/local/lib/python3.6/dist-packages/myModule-1.0.egg-info
Writing /usr/local/lib/python3.6/dist-packages/myModule-1.0.egg-info


