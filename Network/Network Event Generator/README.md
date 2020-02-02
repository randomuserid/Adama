
### Network Event Generator

A Chain Reactor (https://github.com/redcanaryco/chain-reactor) manifest for generating network syscalls in order to test network threat hunting searches and rules. The SpaceCake project has a set of network searches for C2, persistence, commonly used ports among other things here: https://github.com/randomuserid/Adama/tree/master/Network
The DNS, FTP and IRC events use generally available public services but in order to fully test these searches, you will need to replace the 127.0.0.1 address in the rest with the public IP address of an instance you have listening on each of these ports, because many of these searches test for a local to remote context.)

### Setup

Chain Reactor requires `python3`.

Install dependencies:

Debian:
```
sudo apt install musl-tools
```

RPM:
```
sudo yum install musl-tools
```

*Note: If your repository system doesn't contain musl-tools, you can build it from source:*

```
git clone git://git.musl-libc.org/musl
cd musl && ./configure && sudo make install
```

Build Chain Reactor:
```
make
```

### Usage

Run the command below to make the ELF binary:

`python3 compose_reaction network-atoms.json network-reaction.json <output_name_for_executable>`
