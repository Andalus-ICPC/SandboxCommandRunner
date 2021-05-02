sudo apt-get install libseccomp-dev
sudo apt install cmake
mkdir build && cd build && cmake .. && make && sudo make install

sudo python3 bindings/python/setup.py install

# SandboxCommandRunner
