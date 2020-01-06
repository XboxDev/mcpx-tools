# mcpx-tools

### disassemble-mcpx.sh

A script to annotate and disassemble the MCPX ROM using [objdump](https://en.wikipedia.org/wiki/Objdump).

```
disassemble-mcpx.sh <path to MCPX ROM>
```

### mcpx-attack

Tool to display the following exploits:

* [RC4 attack](http://xboxdevwiki.net/Exploits#RC4_attack_.28MCPX_1.0_only.29)
* [TEA attack](http://xboxdevwiki.net/Exploits#TEA_attack_.28MCPX_1.1_only.29)

This tool has to be compiled first:

```
git clone https://github.com/XboxDev/mcpx-tools.git
cd mcpx-tools
mkdir build
cmake ..
make
```

To see the usage information, run the tool without additional arguments.
