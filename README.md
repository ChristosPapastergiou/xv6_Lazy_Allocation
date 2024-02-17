# Lazy Allocation on xv6 OS

The goal of this project is to implement a technique that defers the allocation of resources until they are actually needed. 
This can be particularly useful for optimizing performance and resource usage.
This technique is the Lazy allocation

# Package needed

In order to be able to use the xv6 Unix OS you need to have the qemu. QEMU is a virtualization and emulation tool that allows you to run operating systems and software on a host system that is different from the one for which the software was originally designed.

    sudo apt install git build-essential gdb-multiarch qemu-system-misc gcc-riscv64-linux-gnu binutils-riscv64-linux-gnu

# Compilation & Run

    compile : make
    compile & entering simulation environment : make qemu
    compile & grading : make grade
