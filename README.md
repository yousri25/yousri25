# Yousri

```python
from pwn import *

context.update(arch="amd64", os="linux")

p = remote("tunisia", 1337)

p.sendlineafter(b"name: ", b"Yousri")
p.sendlineafter(b"focus: ", b"binary exploitation, digital forensics")
p.sendlineafter(b"tools: ", b"Ghidra, pwntools, Autopsy, Python, Linux")

p.interactive()
```

## checksec
```
Student:        Yes
Focus:          Pwn (reverse engineering, exploit dev)
Also:           Digital forensics
Daily driver:   Linux
Status:         Learning, playing CTFs, building things
```

## Projects
- **[ghidra_auto](https://github.com/yousri25/ghidra_auto)**: imports, analyzes, and opens binaries in Ghidra with one command
- **[security-consultant-agent](https://github.com/yousri25/security-consultant-agent)**: CVE lookup and email breach checks

## Write-ups
Pwn challenge write-ups coming soon in `pwn-writeups`.

## Contact
[LinkedIn](https://linkedin.com/in/your-profile) · [Email](mailto:yousribenhariz59@gmail.com)
