---
layout: default
title: Installation
nav_order: 3
---

# Installation

Just the Docs has some specific configuration parameters that can be defined in your Jekyll site's _config.yml file.
{: .fs-6 .fw-300 }

---

### Pre requisites
A frida server running anywhere.

### Setup and run

```bash
git clone https://github.com/iGio90/Dwarf

pip3 install -r requirements.txt

python3 dwarf.py
```

### Optionally

You can install keystone-engine to enable assembler:

```$xslt
Windows
x86: https://github.com/keystone-engine/keystone/releases/download/0.9.1/keystone-0.9.1-python-win32.msi
x64: https://github.com/keystone-engine/keystone/releases/download/0.9.1/keystone-0.9.1-python-win64.msi

OSX / Unix
pip3 install keystone-engine
```


