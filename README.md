# EmbedOS
EmbedOS - Embedded security testing operating system based on Ubuntu 18.04 preloaded with firmware security testing tools. The virtual machine can be downloaded and imported as an OVF file into VirtualBox or VMWare.

# Download Link
The most recent version is 2020.2 from October 2020 and can be downloaded via the following links: 

[Google Drive](https://tinyurl.com/EmbedOS-2020)

[Direct](https://drive.google.com/file/d/1t53Q1LaKxd7WeXiw21syhbGbvZFkLzWh/view?usp=sharing)

```
shasum -a 256 EmbedOS_2020.2-disk1.vmdk
f95f8c72e6dc1a57369a37ed4699c50a6ce7c0f7d86b23715a031151e09c4635  EmbedOS_2020.2-disk1.vmdk
shasum -a 512 EmbedOS_2020.2-disk1.vmdk
6db0142ddcd63e8096f3a97ca5d964862ea1d80aa71f07095fe5da0ced075d1446998fc13f9062cb22145589129a2ee2849f3f55e7c4b2bbcd0725afba8e3b55  EmbedOS_2020.2-disk1.vmdk
```

Alternative download site available soon

## Credentials
Username: `embedos`
Password: `embeddedappsec`

# Tools (~/tools)
- [Firmware Analysis Toolkit](https://github.com/attify/firmware-analysis-toolkit)
- [Firmware Analysis Comparison Toolkit (FACT) ](https://github.com/fkie-cad/FACT_core): Not fully installed. More disk space required. 
- [fwanalyzer](https://github.com/cruise-automation/fwanalyzer)
- [ByteSweep](https://gitlab.com/bytesweep/bytesweep)
- [Firmwalker](https://github.com/craigz28/firmwalker)
- [Checksec.sh](https://github.com/slimm609/checksec.sh)
- [Binwalk](http://binwalk.org/)
- [QEMU](https://www.qemu.org/)
- [Firmadyne](https://github.com/firmadyne/firmadyne)
- [Firmware Modification Kit](https://code.google.com/archive/p/firmware-mod-kit/)
- OpenOCD
- Flashrom
- minicom
- ubi_reader
- uboot write
- elfutils
- pax-utils
- prelink
- lddtree

plus more...

Some of the above tools will install additional dependencies not listed here such as [radare2](https://github.com/radareorg/radare2), [cwe-checker](https://github.com/fkie-cad/cwe_checker), and others. 

# Vulnerable Firmware (~/firmware)
- Mirai affected firmware (DVR based)
- [Damn Vulnerable Router Project](https://github.com/praetorian-code/DVRF)
- [IoTGoat](https://github.com/OWASP/IoTGoat)

# Methodology (~/Desktop/Firmware-Security-Testing-Methodology.pdf)
- Firmware Security Testing Methodology - See the following repository for further details hhttps://scriptingxss.gitbook.io/firmware-security-testing-methodology/

# Feedback
If you would like to contribute or provide feedback to improve this virtual machine, submit a pull request or get in touch over Twitter [@scriptingxss](https://twitter.com/scriptingxss).
