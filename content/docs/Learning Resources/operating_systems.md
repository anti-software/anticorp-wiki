---
title: "Operating systems"
# bookFlatSection: false
# bookToc: true
# bookHidden: false
# bookCollapseSection: false
# bookComments: false
# bookSearchExclude: false
---

# Operating systems

## Theoretical concepts
- **Hack The Kernel**: ops-class.org includes everything you need to learn about operating systems online [[Link]](https://ops-class.org)
- **Understanding Virtual Memory**: Virtual Memory lecture for Introduction to Computer Architecture at Uppsala University [[YouTube]](https://youtube.com/playlist?list=PLiwt1iVUib9s2Uo5BeYmwkDFUh70fJPxX&si=u6SnOVXuUehXBTME)
- **osdev Wiki**: This website provides information about the creation of operating systems and serves as a community for those people interested in OS development [[Link]](https://wiki.osdev.org/Main_Page)
- **Writing an OS in Rust**: [[Link]](https://os.phil-opp.com)
- **DECS**: Design and Engineering of Computer Systems taught at IIT Bombay [[Link]](https://www.cse.iitb.ac.in/~mythili/decs/)
- **OSTEP**: Operating Systems: Three Easy Pieces [[Link]](https://pages.cs.wisc.edu/~remzi/OSTEP/)
- **Operating System Concepts** (10th edition): [[Link]](https://www.wiley.com/en-us/Operating+System+Concepts,+10th+Edition-p-9781119320913)
- [CS-6210-Advanced-Operating-Systems-Notes](https://github.com/mohamedameen93/CS-6210-Advanced-Operating-Systems-Notes): Notes for GaTech's Advanced Operating Systems course (CS6210)
- [os_kernel_lab](https://github.com/chyyuu/os_kernel_lab): OS kernel labs based on Rust/C Lang & RISC-V 64/X86-32

---

## Linux

### Learning resources
- **linux-insides**: A book-in-progress about the linux kernel and its insides [[Book]](https://0xax.gitbook.io/linux-insides/) [[GitHub]](https://github.com/0xAX/linux-insides)
- **The Executable and Linkable Format** (ELF) by Intezer Labs
    - [Part 1](https://www.intezer.com/blog/research/executable-linkable-format-101-part1-sections-segments/) Section and Segments
    - [Part 2](https://www.intezer.com/blog/malware-analysis/executable-linkable-format-101-part-2-symbols/) Symbols
    - [Part 3](https://www.intezer.com/blog/malware-analysis/executable-and-linkable-format-101-part-3-relocations/) Relocations
    - [Part 4](https://www.intezer.com/blog/malware-analysis/executable-linkable-format-101-part-4-dynamic-linking/) Dynamic Linking
- **Understanding the memory layout of Linux executables**: [[GitHub Gist]](https://gist.github.com/CMCDragonkai/10ab53654b2aa6ce55c11cfc5b2432a4)
- [awesome-elf](https://github.com/tmpout/awesome-elf)

### Tools
- **quBSD**: A FreeBSD jails and bhyve wrapper; which emulates a Qubes-like containerization schema [[GitHub]](https://github.com/BawdyAnarchist/quBSD)
- **explainshell**: match command-line arguments to their help text [[Link]](https://explainshell.com)
- [WSL-Hello-sudo](https://github.com/nullpo-head/WSL-Hello-sudo): Let's sudo by face recognition of Windows Hello on Windows Subsystem for Linux (WSL). It runs on both WSL 1 and WSL 2. This is a PAM module for Linux on WSL
- [Awesome-Linux-Software](https://github.com/luong-komorebi/Awesome-Linux-Software): A list of awesome Linux softwares
- [easywall](https://github.com/jpylypiw/easywall): Web interface for easy use of the IPTables firewall on Linux systems written in python3
- [photoCClinux](https://github.com/Gictorbit/photoshopCClinux): Photoshop CC v19 installer for GNU/Linux
- [awesome-shell](https://github.com/alebcay/awesome-shell): A curated list of awesome command-line frameworks, toolkits, guides and gizmos.
- [awesome-tui](https://github.com/rothgar/awesome-tuis): List of projects that provide terminal user interfaces
- [grub2-themes](https://github.com/vinceliuice/grub2-themes): Modern Design theme for Grub2
- [pure-bash-bible](https://github.com/dylanaraps/pure-bash-bible): A collection of pure bash alternatives to external processes
- Dotfiles management
  - [chezmoi](https://github.com/twpayne/chezmoi): Manage your dotfiles across multiple diverse machines, securely
  - [awesome-dotfiles](https://github.com/webpro/awesome-dotfiles): A curated list of dotfiles resources
- Linux hardening
  - [kernel-hardening-checker](https://github.com/a13xp0p0v/kernel-hardening-checker): A tool for checking the security hardening options of the Linux kernel
  - [JShielder](https://github.com/Jsitech/JShielder): Hardening Script for Linux Servers/ Secure LAMP-LEMP Deployer/ CIS Benchmark

## Android

### Android security
- A 3-day video course on how to analyze Android Malware: [[Day 1]](https://youtu.be/CwCOGf4Uunk?si=Fm8IOU1vJuRrtjDL) [[Day 2]](https://youtu.be/yZe8tGzm8nA?si=Zb1SDQW8oru0INGG) [[Day 3]](https://youtu.be/JdBu9yEu8g4?si=8NuK1Q4uw2TWmxs4)


---

## Windows

### Windows security
- **Windows hardening**
    - [[beerisgood/Windows11_Hardening]](https://github.com/beerisgood/Windows11_Hardening)
    - [windows_hardening](https://github.com/0x6d69636b/windows_hardening): HardeningKitty and Windows Hardening settings and configurations

### Learning Resource
- **Windows Drivers RE Methodology**: [[Link]](https://voidsec.com/windows-drivers-reverse-engineering-methodology/)

---

## MacOS
### Learning Resource
- **MacOS Internals**: [[Gist]](https://gist.github.com/kconner/cff08fe3e0bb857ea33b47d965b3e19f)

### Tools
- [macos-defaults](https://github.com/yannbertrand/macos-defaults): Incomplete list of macOS `defaults` commands with demos
- [EFIgy](https://github.com/duo-labs/EFIgy): A small client application that uses the Duo Labs EFIgy API to inform you about the state of your Mac EFI firmware

### MacOS security
- **MacOS hardening**:
  - [macOS-Security-and-Privacy-Guide](https://github.com/drduh/macOS-Security-and-Privacy-Guide): Guide to securing and improving privacy on macOS
  - [macOS_hardening](https://github.com/beerisgood/macOS_Hardening): a collection about macOS