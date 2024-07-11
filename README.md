# Network security project

**DISCLAIMER**: this project is for study purpose. I do not own the exploit PoC (
it is has been created by  [this blogpost](https://pwning.tech/nftables/#5-proof-of-concept)). 
I studied the vulnerability and exploit from the references provided in the [docs](./docs/refs.bib).

The project analyzes the dirty pagetable tecnique used to exploit the Linux Kernel. 

Based on [this blogpost](https://pwning.tech/nftables/#5-proof-of-concept) and related sources
I analyzed a nf_tables double free vulnerability that can be exploited using the dirty 
pagetables tecnique and modprobe_path overwriting to get root access from a machine.
