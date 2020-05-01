# install-clang-9
instructions for installing clang9

run these commands by order:

curl -SL http://releases.llvm.org/9.0.0/clang%2bllvm-9.0.0-x86_64-linux-gnu-ubuntu-18.04.tar.xz | tar -xJC

mv clang+llvm-9.0.0-x86_64-linux-gnu-ubuntu-18.04 clang_9.0.0

sudo mv clang_9.0.0 /usr/local

export PATH=/usr/local/clang_9.0.0/bin:$PATH

export LD_LIBRARY_PATH=/usr/local/clang_9.0.0/lib:$LD_LIBRARY_PATH

