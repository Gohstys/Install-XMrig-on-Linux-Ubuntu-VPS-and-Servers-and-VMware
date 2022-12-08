# Install-XMrig-on-Linux-Ubuntu-VPS-and-Servers-and-VMware
Install XMrig on Linux Ubuntu VPS and Servers and VMware

Usage

To start use: xmrig/build/./xmrig -o stratum+tcp://prohashing.com:3359 -u sabiasque -p a=randomx,n=I_TA_VPS,o=VPS -k --coin monero -a rx/0

or

sudo ./xmrig -o POOL:3333 -u WALLED -k


MINERxCUDA INFO

Compiling the CUDA plugin is optional and only required if you want to use NVIDIA GPUs.

Follow the instructions at https://developer.nvidia.com/cuda-downloads to install CUDA.


Advanced Construction

We use build_deps.shscript to build recent versions of libuv , openssl and hwloc as static libraries.

Use the ldd xmrig command to verify the binary dependencies.
