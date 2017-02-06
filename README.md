## VoidHack toolset
Here are represented useful tools for CTF competitions. You can add new tools if you are convinced they can help in games.

### Reverse Engineering/Exploitation
- [radare2](https://github.com/radare/radare2): (also known as r2) is a complete framework for reverse-engineering and analyzing binaries; composed of a set of small utilities that can be used together or independently from the command line.

- [qemu](https://github.com/qemu/qemu) ([official site](http://www.qemu-project.org/)): QEMU is a generic and open source machine emulator and virtualizer. ... QEMU supports virtualization when executing under the Xen hypervisor or using the KVM kernel module in Linux. When using KVM, QEMU can virtualize x86, server and embedded PowerPC, 64-bit POWER, S390, 32-bit and 64-bit ARM, and MIPS guests.

- [gdb](https://www.sourceware.org/gdb/): GNU Debugger, which is also called gdb, is the most popular debugger for UNIX systems to debug C and C++ programs.

- [strace](http://man7.org/linux/man-pages/man1/strace.1.html) ([github link](https://github.com/strace/strace)): is a diagnostic, debugging and instructional userspace utility for Linux. It is used to monitor interactions between processes and the Linux kernel, which include system calls, signal deliveries, and changes of process state.

- [angr](http://angr.io/): angr is a python framework for analyzing binaries. It focuses on both static and dynamic symbolic ("concolic") analysis, making it applicable to a variety of tasks.

- [voltron](https://github.com/snare/voltron): Voltron is an extensible debugger UI toolkit written in Python. It aims to improve the user experience of various debuggers (LLDB, GDB, VDB and WinDbg) by enabling the attachment of utility views that can retrieve and display data from the debugger host. By running these views in other TTYs, you can build a customised debugger user interface to suit your needs.

- [nasm](http://www.nasm.us/): The Netwide Assembler (NASM) is an assembler and disassembler for the Intel x86 architecture. It can be used to write 16-bit, 32-bit (IA-32) and 64-bit (x86-64) programs. NASM is considered to be one of the most popular assemblers for Linux.


### Forensics
- [volatility](https://github.com/volatilityfoundation/volatility): The Volatility Framework is a completely open collection of tools, implemented in Python under the GNU General Public License, for the extraction of digital artifacts from volatile memory (RAM) samples.

- [dd](https://en.wikipedia.org/wiki/Dd_(Unix_software): dd is a command-line utility for Unix and Unix-like operating systems whose primary purpose is to convert and copy files.

- [cuckoo](https://github.com/cuckoosandbox/cuckoo): cuckoo is a malware analysis system. It means that you can throw any suspicious file at it and in a matter of seconds Cuckoo will provide you back some detailed results outlining what such file did when executed inside an isolated environment

- [binwalk](https://github.com/devttys0/binwalk): Binwalk is a tool for searching a given binary image for embedded files and executable code. Specifically, it is designed for identifying files and code embedded inside of firmware images.

- [dff](https://github.com/arxsys/dff): dff is computer forensics open-source software. It is used by professionals and non-experts to collect, preserve and reveal digital evidence without compromising systems and data

- [Sleuth Kit](https://www.sleuthkit.org/): is a collection of command line tools and a C library that allows you to analyze disk images and recover files from them. It is used behind the scenes in Autopsy and many other open source and commercial forensics tools.

- [gpart](https://github.com/baruch/gpart): gpart is a software utility which scans a storage device, examining the data in order to detect partitions which may exist but are absent from the disk's partition tables

- [fdisk](https://www.gnu.org/software/fdisk/): fdisk is a dialog-driven program for creation and manipulation of partition tables. It understands GPT, MBR, Sun, SGI and BSD partition tables.

- [TrID](http://mark0.net/soft-trid-e.html): TrID is an utility designed to identify file types from their binary signatures. While there are similar utilities with hard coded logic, TrID has no fixed rules. Instead, it's extensible and can be trained to recognize new formats in a fast and automatic way.


### Cryptography
- [sagemath](https://github.com/sagemath/sage): sagemath is mathematical software with features covering many aspects of mathematics, including algebra, combinatorics, numerical mathematics, number theory, and calculus.

- [john-the-ripper](https://github.com/magnumripper/JohnTheRipper/): John the Ripper is a fast password cracker. It is one of the most popular password testing and breaking programs as it combines a number of password crackers into one package, autodetects password hash types, and includes a customizable cracker.

- [pycrypto](https://pypi.python.org/pypi/pycrypto): This is a collection of both secure hash functions (such as SHA256 and RIPEMD160), and various encryption algorithms (AES, DES, RSA, ElGamal, etc.). The package is structured to make adding new modules easy.

- [openssl](https://www.openssl.org/): OpenSSL is a general purpose cryptography library that provides an open source implementation of the Secure Sockets Layer (SSL) and Transport Layer Security (TLS) protocols.

- [FeatherDuster](https://github.com/nccgroup/featherduster): is a tool used for breaking crypto which tries to make the process of identifying and exploiting weak cryptosystems as easy as possible.


### Network
- [nmap](https://nmap.org/): nmap is a free and open source (license) utility for network discovery and security auditing. Many systems and network administrators also find it useful for tasks such as network inventory, managing service upgrade schedules, and monitoring host or service uptime.

- [wireshark](https://www.wireshark.org/): Wireshark is a free and open source packet analyzer. It is used for network troubleshooting, analysis, software and communications protocol development.

- [tcpdump](http://www.tcpdump.org/): tcpdump is a powerful command-line packet analyzer; and libpcap, a portable C/C++ library for network traffic capture.

- [sslstrip](https://github.com/moxie0/sslstrip/): sslstrip is a MITM tool that implements Moxie Marlinspike’s SSL stripping attacks


### System
- [pwntools](https://github.com/Gallopsled/pwntools/): pwntools is a CTF framework and exploit development library. Written in Python, it is designed for rapid prototyping and development, and intended to make exploit writing as simple as possible

- [metasploit](https://github.com/rapid7/metasploit-framework): The Metasploit Framework (MSF) is far more than just a collection of exploits. It’s an infrastructure that you can build upon and utilize for your custom needs. This allows you to concentrate on your unique environment, and not have to reinvent the wheel. I consider the MSF to be one of the single most useful auditing tools freely available to security professionals today.
