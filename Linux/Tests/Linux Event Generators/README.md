
### Linux Event Generators

A Chain Reactor (https://github.com/redcanaryco/chain-reactor) manifest for generating Linux activity in order to test Auditbeat threat hunting searches and rules. The SpaceCake project has over 100 hunting searches for Linux here: https://github.com/randomuserid/Adama/tree/master/Linux

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

Run the command below to make the ELF binary. NOTE: make and run this in /tmp because certain hunting rules look for execution in the Linux /tmp directory. This manifest runs both a hidden and a visible process from /tmp.

`python3 compose_reaction atoms.json reaction.json <output_name_for_executable>`
