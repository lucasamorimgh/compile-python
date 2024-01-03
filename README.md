# compile-python
This is a repo for compilling and installing python from scratch

Following:
https://www.youtube.com/watch?v=gzh329Yzv8E&ab_channel=PragmaticAILabs

Commands:
python

exit()

sudo apt-get update

sudo apt-get install build-essential gdb lcov libbz2-dev libffi-dev libgdbm-dev liblzma-dev libncurses5-dev libreadline6-dev libsqlite3-dev libssl-dev lzma lzma-dev tk-dev uuid-dev zlib1g-dev

sudo apt-get update

wget https://www.python.org/ftp/python/3.12.1/Python-3.12.1.tgz

tar zxvf Python-3.12.1.tgz

ls

rm Python-3.12.1.tgz

cd Python-3.12.1/

./configure --enable-optimizations

make -j 2

-- error here
make altinstall

sudo make altinstall

python

exit()

cd ..

usr/local/bin/python3.12

exit()