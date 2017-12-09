# SeqMiner (Beta) #
A Fast Monero CPU Miner

Download here: https://github.com/SeqMiner/SeqMiner/releases/download/Beta5/SeqMiner.Beta5.zip

## Usage ##
SeqMiner [pool url] [port] [address] [optional: password]

Alternatively you can edit run.bat to add your pool and address.

## FAQ ##
### How fast is SeqMiner?  ###
On an i7-4770k SeqMiner achieves 335 hashes/second.  About 10% faster than xmr-stak.

### What is the fee? ###
SeqMiner has a fee of 3%.

### How do I tweak SeqMiner? ###
At the moment SeqMiner self-calibrates for 100% CPU usage.  In the future more tweaks will be exposed.

### Is there a Linux version? ###
Its on the way.  However for the near future only a windows version is available.

### What CPUs are Supported? ###
Westmere and above are supported.  You must have AES-NI and SSE4 support.  The software will check on startup if your machine is supported.
