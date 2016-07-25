Chapter 2. Virtualization > Introduction and Learning Objectives > Virtualization

Virtualization : According to Wikipedia,
"In computing, virtualization refers to the act of creating a virtual (rather than actual) version of something, including virtual computer hardware platforms, operating systems, storage devices, and computer resources." 

Example of hypervisors are:

* KVM (Kernel-based Virtual Machine)
KVM is an Open Source software. It supports various Guest OSes, like Linux, Windows, Solaris, etc. 
KVM does not perform any emulation itself, but it exposes the /dev/kvm interface, by which an external userspace host can do emulation. QEMU is one such host.

A High-Level Overview of the KVM/QEMU Virtualization Environment
![ A High-Level Overview of the KVM/QEMU Virtualization Environment](https://github.com/abhishekanand/lfs151/blob/master/chapter2/images/Kernel-based_Virtual_Machine.PNG)

* Xen
* VMWare
* VirtualBox
* Hyper-V.
