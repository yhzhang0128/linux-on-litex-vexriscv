Output of `sim.py`

```

        __   _ __      _  __
       / /  (_) /____ | |/_/
      / /__/ / __/ -_)>  <
     /____/_/\__/\__/_/|_|
   Build your hardware, easily!

 (c) Copyright 2012-2024 Enjoy-Digital
 (c) Copyright 2007-2015 M-Labs

 BIOS built on Jun 11 2024 20:57:17
 BIOS CRC passed (a98e2a3a)

 LiteX git sha1: 4e044f54c

--=============== SoC ==================--
CPU:    VexRiscv SMP-LINUX @ 100MHz
BUS:    wishbone 32-bit @ 4GiB
CSR:    32-bit data
ROM:    64.0KiB
SRAM:   8.0KiB
SDRAM:    64.0MiB 32-bit @ 100MT/s (CL-2 CWL-2)
MAIN-RAM: 64.0MiB

--========== Initialization ============--
Initializing SDRAM @0x40000000...
Switching SDRAM to software control.
Switching SDRAM to hardware control.

--============== Boot ==================--
Booting from serial...
Press Q or ESC to abort boot completely.
sL5DdSMmkekro
Timeout
Executing booted program at 0x40f00000

--============= Liftoff! ===============--

OpenSBI v0.8-1-gecf7701
   ____                    _____ ____ _____
  / __ \                  / ____|  _ \_   _|
 | |  | |_ __   ___ _ __ | (___ | |_) || |
 | |  | | '_ \ / _ \ '_ \ \___ \|  _ < | |
 | |__| | |_) |  __/ | | |____) | |_) || |_
  \____/| .__/ \___|_| |_|_____/|____/_____|
        | |
        |_|

Platform Name       : LiteX / VexRiscv-SMP
Platform Features   : timer,mfdeleg
Platform HART Count : 8
Boot HART ID        : 0
Boot HART ISA       : rv32imasu
BOOT HART Features  : pmp,time
BOOT HART PMP Count : 16
Firmware Base       : 0x40f00000
Firmware Size       : 124 KB
Runtime SBI Version : 0.2

MIDELEG : 0x00000222
MEDELEG : 0x0000b109
[    0.000000] Linux version 5.14.0 (florent@panda) (riscv32-buildroot-linux-gnu-gcc.br_real (Buildroot 2021.08-381-g279167ee8d) 10.3.0, GNU ld (GNU Binutils) 2.36.1) #1 SMP Tue Sep 21 12:57:31 CEST 2021
[    0.000000] Machine model: sim
[    0.000000] earlycon: liteuart0 at I/O port 0x0 (options '')
[    0.000000] Malformed early option 'console'
[    0.000000] earlycon: liteuart0 at MMIO 0xf0001000 (options '')
[    0.000000] printk: bootconsole [liteuart0] enabled
[    0.000000] Zone ranges:
[    0.000000]   Normal   [mem 0x0000000040000000-0x0000000043ffffff]
[    0.000000] Movable zone start for each node
[    0.000000] Early memory node ranges
[    0.000000]   node   0: [mem 0x0000000040000000-0x0000000043ffffff]
[    0.000000] Initmem setup node 0 [mem 0x0000000040000000-0x0000000043ffffff]
[    0.000000] SBI specification v0.2 detected
[    0.000000] SBI implementation ID=0x1 Version=0x8
[    0.000000] SBI TIME extension detected
[    0.000000] SBI IPI extension detected
[    0.000000] SBI RFENCE extension detected
[    0.000000] SBI v0.2 HSM extension detected
[    0.000000] riscv: ISA extensions aimp
[    0.000000] riscv: ELF capabilities aim
[    0.000000] percpu: Embedded 8 pages/cpu s11340 r0 d21428 u32768
[    0.000000] Built 1 zonelists, mobility grouping on.  Total pages: 16256
[    0.000000] Kernel command line: console=liteuart earlycon=liteuart,0xf0001000 rootwait root=/dev/ram0
[    0.000000] Dentry cache hash table entries: 8192 (order: 3, 32768 bytes, linear)
[    0.000000] Inode-cache hash table entries: 4096 (order: 2, 16384 bytes, linear)
[    0.000000] Sorting __ex_table...
[    0.000000] mem auto-init: stack:off, heap alloc:off, heap free:off
[    0.000000] Memory: 48644K/65536K available (5685K kernel code, 572K rwdata, 883K rodata, 209K init, 221K bss, 16892K reserved, 0K cma-reserved)
[    0.000000] SLUB: HWalign=64, Order=0-3, MinObjects=0, CPUs=1, Nodes=1
[    0.000000] rcu: Hierarchical RCU implementation.
[    0.000000] rcu:   RCU restricting CPUs from NR_CPUS=8 to nr_cpu_ids=1.
[    0.000000] rcu: RCU calculated value of scheduler-enlistment delay is 25 jiffies.
[    0.000000] rcu: Adjusting geometry for rcu_fanout_leaf=16, nr_cpu_ids=1
[    0.000000] NR_IRQS: 64, nr_irqs: 64, preallocated irqs: 0
[    0.000000] riscv-intc: 32 local interrupts mapped
[    0.000000] plic: interrupt-controller@f0c00000: mapped 32 interrupts with 1 handlers for 2 contexts.
[    0.000000] random: get_random_bytes called from start_kernel+0x4ac/0x63c with crng_init=0
[    0.000000] riscv_timer_init_dt: Registering clocksource cpuid [0] hartid [0]
[    0.000000] clocksource: riscv_clocksource: mask: 0xffffffffffffffff max_cycles: 0x171024e7e0, max_idle_ns: 440795205315 ns
[    0.000017] sched_clock: 64 bits at 100MHz, resolution 10ns, wraps every 4398046511100ns
[    0.002157] Console: colour dummy device 80x25
[    0.003092] Calibrating delay loop (skipped), value calculated using timer frequency.. 200.00 BogoMIPS (lpj=400000)
[    0.004628] pid_max: default: 32768 minimum: 301
[    0.008071] Mount-cache hash table entries: 1024 (order: 0, 4096 bytes, linear)
[    0.009105] Mountpoint-cache hash table entries: 1024 (order: 0, 4096 bytes, linear)
[    0.029661] ASID allocator using 9 bits (512 entries)
[    0.032256] rcu: Hierarchical SRCU implementation.
[    0.037719] smp: Bringing up secondary CPUs ...
[    0.038281] smp: Brought up 1 node, 1 CPU
[    0.043687] devtmpfs: initialized
[    0.067646] clocksource: jiffies: mask: 0xffffffff max_cycles: 0xffffffff, max_idle_ns: 7645041785100000 ns
[    0.069253] futex hash table entries: 256 (order: 2, 16384 bytes, linear)
[    0.076698] NET: Registered PF_NETLINK/PF_ROUTE protocol family
[    0.220379] pps_core: LinuxPPS API ver. 1 registered
[    0.221174] pps_core: Software ver. 5.3.6 - Copyright 2005-2007 Rodolfo Giometti <giometti@linux.it>
[    0.222330] PTP clock support registered
[    0.225771] FPGA manager framework
[    0.238859] clocksource: Switched to clocksource riscv_clocksource
[    0.389583] NET: Registered PF_INET protocol family
[    0.391723] IP idents hash table entries: 2048 (order: 2, 16384 bytes, linear)
[    0.399253] tcp_listen_portaddr_hash hash table entries: 512 (order: 0, 6144 bytes, linear)
[    0.400579] TCP established hash table entries: 1024 (order: 0, 4096 bytes, linear)
[    0.401805] TCP bind hash table entries: 1024 (order: 1, 8192 bytes, linear)
[    0.403015] TCP: Hash tables configured (established 1024 bind 1024)
[    0.404444] UDP hash table entries: 256 (order: 1, 8192 bytes, linear)
[    0.405534] UDP-Lite hash table entries: 256 (order: 1, 8192 bytes, linear)
[    0.423436] Unpacking initramfs...
[    0.459181] workingset: timestamp_bits=30 max_order=14 bucket_order=0
[    0.666129] io scheduler mq-deadline registered
[    0.666993] io scheduler kyber registered
[    0.911654] LiteX SoC Controller driver initialized
[    4.162725] Freeing initrd memory: 8192K
[    4.661489] f0001000.serial: ttyLXU0 at MMIO 0x0 (irq = 0, base_baud = 0) is a liteuart
[    4.663023] printk: console [liteuart0] enabled
[    4.663023] printk: console [liteuart0] enabled
[    4.663685] printk: bootconsole [liteuart0] disabled
[    4.663685] printk: bootconsole [liteuart0] disabled
[    4.684547] i2c_dev: i2c /dev entries driver
[    4.721476] NET: Registered PF_INET6 protocol family
[    4.735249] Segment Routing with IPv6
[    4.736064] In-situ OAM (IOAM) with IPv6
[    4.737604] sit: IPv6, IPv4 and MPLS over IPv4 tunneling driver
[    4.750842] NET: Registered PF_PACKET protocol family
[    4.762433] Freeing unused kernel image (initmem) memory: 204K
[    4.763648] Kernel memory protection not selected by kernel config.
[    4.764503] Run /init as init process
Starting syslogd: OK
Starting klogd: OK
Running sysctl: OK
Saving random seed: [    6.814961] random: dd: uninitialized urandom read (512 bytes read)
OK
Starting network: OK

Welcome to Buildroot
buildroot login: root
                   __   _
                  / /  (_)__  __ ____ __
                 / /__/ / _ \/ // /\ \ /
                /____/_/_//_/\_,_//_\_\
                      / _ \/ _ \
   __   _ __      _  _\___/_//_/         ___  _
  / /  (_) /____ | |/_/__| | / /____ __ / _ \(_)__ _____  __
 / /__/ / __/ -_)>  </___/ |/ / -_) \ // , _/ (_-</ __/ |/ /
/____/_/\__/\__/_/|_|____|___/\__/_\_\/_/|_/_/___/\__/|___/
                  / __/  |/  / _ \
                 _\ \/ /|_/ / ___/
                /___/_/  /_/_/
  32-bit RISC-V Linux running on LiteX / VexRiscv-SMP.

login[70]: root login on 'console'
root@buildroot:~# ls
root@buildroot:~# pwd
/root
root@buildroot:~# ls /bin
arch           dmesg          linux32        nice           setserial
ash            dnsdomainname  linux64        nuke           sh
base32         dumpkmap       ln             pidof          sleep
base64         echo           login          ping           stty
busybox        egrep          ls             pipe_progress  su
cat            false          lsattr         printenv       sync
chattr         fdflush        mkdir          ps             tar
chgrp          fgrep          mknod          pwd            touch
chmod          getopt         mktemp         resume         true
chown          grep           more           rm             umount
cp             gunzip         mount          rmdir          uname
cpio           gzip           mountpoint     run-parts      usleep
date           hostname       mt             sed            vi
dd             kill           mv             setarch        watch
df             link           netstat        setpriv        zcat
root@buildroot:~# 
```

```
                                   __   _
                                  / /  (_)__  __ ____ __
                                 / /__/ / _ \/ // /\ \ /
                                /____/_/_//_/\_,_//_\_\
                                      / _ \/ _ \
                      __   _ __      _\___/_//_/ __             _
                     / /  (_) /____ | |/_/__| | / /____ __ ____(_)__ _____  __
                    / /__/ / __/ -_)>  </___/ |/ / -_) \ // __/ (_-</ __/ |/ /
                   /____/_/\__/\__/_/|_|    |___/\__/_\_\/_/ /_/___/\__/|___/

                   Copyright (c) 2019-2022, Linux-on-LiteX-VexRiscv Developers
```
[![](https://github.com/litex-hub/linux-on-litex-vexriscv/workflows/ci/badge.svg)](https://github.com/litex-hub/linux-on-litex-vexriscv/actions) ![License](https://img.shields.io/badge/License-BSD%202--Clause-orange.svg)
> **Note:** Tested on Ubuntu 18.04/20.04 LTS.


[> Intro
--------

This project is an experiment to run Linux with [VexRiscv-SMP](https://github.com/SpinalHDL/VexRiscv) CPU, a 32-bits Linux Capable RISC-V CPU written in [Spinal HDL](https://github.com/SpinalHDL/SpinalHDL).  [LiteX](https://github.com/enjoy-digital/litex) is used to create the SoC around the VexRiscv-SMP CPU and provides the infrastructure and peripherals (LiteDRAM, LiteEth, LiteSDCard, etc...). All the components used to create the SoC are open-source and the flexibility of Spinal HDL/LiteX allow targeting easily very various FPGA devices/boards: Xilinx, Intel, Lattice, Microsemi, Efinix FPGAs are tested with very various configuration: SDRAM/DDR/DDR2/DDR3/DDR4 or HyperRAM RAMs, RMII/MII/RGMII/1000BASE-X Ethernet PHYs,  SDCard (in SPI or SD mode), SATA, PCIe, etc...

On Lattice ECP5 FPGAs, the [open source toolchain](https://github.com/SymbiFlow/prjtrellis) even allows creating full open-source SoC with open-source cores **and** toolchain!

This project demonstrates **how high level HDLs framework like Spinal HDL, LiteX can enable new possibilities and complement each other**. Results shown here are the results of a productive collaboration between various open-source communities.

[> Demo
----------

<p align="center"><img src="https://user-images.githubusercontent.com/1450143/156186177-ea06bddc-87b2-4d27-af60-d6d7f3f2929b.png" width="800"></p>

https://user-images.githubusercontent.com/1450143/156186677-87c40a39-2cf5-4ae0-9138-9d2aa0693ab6.mp4

[> Supported boards
-------------------
All boards supported in [LiteX-Boards](https://github.com/litex-hub/litex-boards) with...:

 - Enough FPGA logic to fit VexRiscv-SMP + LiteX SoC.
 - 32MB of RAM (Reduced to 8MB when rootfs can be put on a SDCard).
 - A UART.

... could run this project.

The board support is directly imported from LiteX-Boards and the configuration is just adapted for the project in `make.py`.

The current list of boards that have been tested and are supported can be obtained by running `./make.py --help`:

    ├── acorn
    ├── acorn_pcie
    ├── alveo_u250
    ├── alveo_u280
    ├── arty
    ├── arty_a7
    ├── arty_s7
    ├── butterstick
    ├── camlink_4k
    ├── colorlight_i5
    ├── de0nano
    ├── de10nano
    ├── de1soc
    ├── ecpix5
    ├── genesys2
    ├── hadbadge
    ├── icesugar_pro
    ├── kc705
    ├── kcu105
    ├── machdyne_konfekt
    ├── machdyne_noir
    ├── machdyne_schoko
    ├── minispartan6
    ├── mnt_rkx7
    ├── netv2
    ├── nexys4ddr
    ├── nexys_video
    ├── orangecrab
    ├── pipistrello
    ├── qmtech_ep4ce15
    ├── qmtech_ep4ce55
    ├── qmtech_wukong
    ├── sds1104xe
    ├── stlv7325
    ├── titanium_ti60_f225_dev_kit
    ├── trellisboard
    ├── trion_t120_bga576_dev_kit
    ├── ulx3s
    ├── vc707
    ├── versa_ecp5
    ├── xcu1525
    ├── zcu104

Adding support for another board from LiteX-Boards satisfying the requirements should only be a matter of adding a few lines to `make.py`.

> **Note:** Avalanche support can be found in [RISC-V - Getting Started Guide](https://risc-v-getting-started-guide.readthedocs.io/en/latest/linux-avalanche.html) thanks to [Antmicro](https://antmicro.com).

> **Note:** On FPGA without distributed ram (as Cyclone IV), consider using the --without-out-of-order-decoder option to reduce area.

[> Prerequisites
----------------
```sh
$ sudo apt install build-essential device-tree-compiler wget git python3-setuptools
$ git clone https://github.com/litex-hub/linux-on-litex-vexriscv
$ cd linux-on-litex-vexriscv
```

[> Pre-built Bitstreams and Linux/OpenSBI images
------------------------------------------------

Pre-built bistreams for the common boards and pre-built Linux images can be found [here](https://github.com/litex-hub/linux-on-litex-vexriscv/issues/164) and will get you started quickly and easily without the need to compile anything.

[> Installing LiteX
-------------------
```sh
$ wget https://raw.githubusercontent.com/enjoy-digital/litex/master/litex_setup.py
$ chmod +x litex_setup.py
$ ./litex_setup.py --init --install --user (--user to install to user directory)
```
For more information, please visit: https://github.com/enjoy-digital/litex/wiki/Installation

[> Installing a RISC-V toolchain
--------------------------------
```sh
$ wget https://static.dev.sifive.com/dev-tools/riscv64-unknown-elf-gcc-8.1.0-2019.01.0-x86_64-linux-ubuntu14.tar.gz
$ tar -xvf riscv64-unknown-elf-gcc-8.1.0-2019.01.0-x86_64-linux-ubuntu14.tar.gz
$ export PATH=$PATH:$PWD/riscv64-unknown-elf-gcc-8.1.0-2019.01.0-x86_64-linux-ubuntu14/bin/
```

[> Installing SBT (Only required for custom CPU configs)
--------------------------------
Some regular VexRiscv-smp configuration are already pregenerated, 
but for others, it need to run som SpinalHDL hardware generation, which require sbt.

Please visit: https://www.scala-sbt.org/1.x/docs/Installing-sbt-on-Linux.html#Installing+sbt+on+Linux

[> Installing Verilator (only needed for simulation)
----------------------------------------------------
```sh
$ sudo apt install verilator
$ sudo apt install libevent-dev libjson-c-dev
```

Check that the installed verilator version is >= 4.2xx. If not, you will have to compile it from sources.

[> Installing OpenOCD (only needed for hardware test)
-----------------------------------------------------
```sh
$ sudo apt install libtool automake pkg-config libusb-1.0-0-dev
$ git clone https://github.com/ntfreak/openocd.git
$ cd openocd
$ ./bootstrap
$ ./configure --enable-ftdi
$ make
$ sudo make install
```

[> Running the LiteX simulation
-------------------------------
You need to extract linux_???.zip from https://github.com/litex-hub/linux-on-litex-vexriscv/issues/164 into the images folder first, then :
```sh
$ ./sim.py
```
You should see Linux booting and be able to interact with it:
```
        __   _ __      _  __
       / /  (_) /____ | |/_/
      / /__/ / __/ -_)>  <
     /____/_/\__/\__/_/|_|

 (c) Copyright 2012-2019 Enjoy-Digital
 (c) Copyright 2012-2015 M-Labs Ltd

 BIOS built on May  2 2019 18:58:54
 BIOS CRC passed (97ea247b)

--============ SoC info ================--
CPU:       VexRiscv @ 1MHz
ROM:       32KB
SRAM:      4KB
MAIN-RAM:  131072KB

--========= Peripherals init ===========--

--========== Boot sequence =============--
Booting from serial...
Press Q or ESC to abort boot completely.
sL5DdSMmkekro
Timeout
Executing booted program at 0x20000000
--============= Liftoff! ===============--
VexRiscv Machine Mode software built May  3 2019 19:33:43
--========== Booting Linux =============--
[    0.000000] No DTB passed to the kernel
[    0.000000] Linux version 5.0.9 (florent@lab) (gcc version 8.3.0 (Buildroot 2019.05-git-00938-g75f9fcd0c9)) #1 Thu May 2 17:43:30 CEST 2019
[    0.000000] Initial ramdisk at: 0x(ptrval) (8388608 bytes)
[    0.000000] Zone ranges:
[    0.000000]   Normal   [mem 0x00000000c0000000-0x00000000c7ffffff]
[    0.000000] Movable zone start for each node
[    0.000000] Early memory node ranges
[    0.000000]   node   0: [mem 0x00000000c0000000-0x00000000c7ffffff]
[    0.000000] Initmem setup node 0 [mem 0x00000000c0000000-0x00000000c7ffffff]
[    0.000000] elf_hwcap is 0x1100
[    0.000000] Built 1 zonelists, mobility grouping on.  Total pages: 32512
[    0.000000] Kernel command line: mem=128M@0x40000000 rootwait console=hvc0 root=/dev/ram0 init=/sbin/init swiotlb=32
[    0.000000] Dentry cache hash table entries: 16384 (order: 4, 65536 bytes)
[    0.000000] Inode-cache hash table entries: 8192 (order: 3, 32768 bytes)
[    0.000000] Sorting __ex_table...
[    0.000000] Memory: 119052K/131072K available (1957K kernel code, 92K rwdata, 317K rodata, 104K init, 184K bss, 12020K reserved, 0K cma-reserved)
[    0.000000] SLUB: HWalign=64, Order=0-3, MinObjects=0, CPUs=1, Nodes=1
[    0.000000] NR_IRQS: 0, nr_irqs: 0, preallocated irqs: 0
[    0.000000] clocksource: riscv_clocksource: mask: 0xffffffffffffffff max_cycles: 0x114c1bade8, max_idle_ns: 440795203839 ns
[    0.000155] sched_clock: 64 bits at 75MHz, resolution 13ns, wraps every 2199023255546ns
[    0.001515] Console: colour dummy device 80x25
[    0.008297] printk: console [hvc0] enabled
[    0.009219] Calibrating delay loop (skipped), value calculated using timer frequency.. 150.00 BogoMIPS (lpj=300000)
[    0.009919] pid_max: default: 32768 minimum: 301
[    0.016255] Mount-cache hash table entries: 1024 (order: 0, 4096 bytes)
[    0.016802] Mountpoint-cache hash table entries: 1024 (order: 0, 4096 bytes)
[    0.044297] devtmpfs: initialized
[    0.061343] clocksource: jiffies: mask: 0xffffffff max_cycles: 0xffffffff, max_idle_ns: 7645041785100000 ns
[    0.061981] futex hash table entries: 256 (order: -1, 3072 bytes)
[    0.117611] clocksource: Switched to clocksource riscv_clocksource
[    0.251970] Unpacking initramfs...
[    2.005474] workingset: timestamp_bits=30 max_order=15 bucket_order=0
[    2.178440] Block layer SCSI generic (bsg) driver version 0.4 loaded (major 254)
[    2.178909] io scheduler mq-deadline registered
[    2.179271] io scheduler kyber registered
[    3.031140] random: get_random_bytes called from init_oops_id+0x4c/0x60 with crng_init=0
[    3.043743] Freeing unused kernel memory: 104K
[    3.044070] This architecture does not have kernel memory protection.
[    3.044472] Run /init as init process
mount: mounting tmpfs on /dev/shm failed: Invalid argument
mount: mounting tmpfs on /tmp failed: Invalid argument
mount: mounting tmpfs on /run failed: Invalid argument
Starting syslogd: OK
Starting klogd: OK
Initializing random number generator... [    4.374589] random: dd: uninitialized urandom read (512 bytes read)
done.
Starting network: ip: socket: Function not implemented
ip: socket: Function not implemented
FAIL


Welcome to Buildroot
buildroot login: root
login[48]: root login on 'hvc0'
# help
Built-in commands:
------------------
  . : [ [[ alias bg break cd chdir command continue echo eval exec
  exit export false fg getopts hash help history jobs kill let
  local printf pwd read readonly return set shift source test times
  trap true type ulimit umask unalias unset wait
#
```

[> Running on hardware
----------------------
### Build the FPGA bitstream (optional)
**The prebuilt bitstreams for the supported boards are provided**, so you can just use them for quick testing, if you want to rebuild the bitstreams you will need to install the toolchain for your FPGA:

| FPGA family       |      Toolchain        |
|-------------------|-----------------------|
| Xilinx Ultrascale |      Vivado           |
| Xilinx 7-Series   |   Vivado/SymbiFlow*   |
| Xilinx Spartan6   |        ISE            |
| Lattice ECP5      | Yosys+Trellis+Nextpnr |
| Altera Cyclone4   |    Quartus Prime      |

Once installed, build the bitstream with:
```sh
$ ./make.py --board=XXYY --cpu-count=X --build
```

> **Note:** \*=to select a different toolchain use the `--toolchain` option, i.e.:
> ```
> ./make.py --board=arty --toolchain=symbiflow --build
> ```

### Load the FPGA bitstream
To load the bitstream to you board, run:
```sh
$ ./make.py --board=XXYY --cpu-count=X --load
```
> **Note**: If you are using a Versa board, you will need to change J50 to bypass the iSPclock. Re-arrange the jumpers to connect pins 1-2 and 3-5 (leaving one jumper spare). See p19 of the Versa Board user guide.

### Load the Linux images over Serial
All the boards support Serial loading of the Linux images and this is the only way to load them when the board does not have others communications interfaces or storage capability.

To load the Linux images over Serial, use the [litex_term](https://github.com/enjoy-digital/litex/blob/master/litex/tools/litex_term.py) terminal/tool provided by LiteX and run:
```sh
$ litex_term --images=images/boot.json /dev/ttyUSBX (--safe : In case of CRC Error, slower but should always work)
```
The images should load and you should see Linux booting :)

> **Note**: litex_term is automatically installed with LiteX.

> **Note**: By default baudrate is set to 115200 bauds. You can use `--uart-baudrate` argument of `make.py` to increase it on the board and use `--speed` argument of `litex_term` to reflect the change. This is useful to increase upload speed when binaries can only be uploaded over Serial.

> **Note:** Since on some boards JTAG/Serial is shared, when you will run litex_term after loading the board, the BIOS serialboot will already have timed out. You will need to press Enter, see if you have the BIOS prompt and type *reboot*.

Since loading over Serial is working for all boards, **this is the recommended way to do initial tests** even if your board has more capabilities.

### Load the Linux images over Ethernet
For boards with Ethernet support, the Linux images can be loaded over TFTP. You need to copy the files from *images* directory to your TFTP root directory. The default Local IP/Remote IP are 192.168.1.50/192.168.1.100 but you can change it with the *--local-ip* and *--remote-ip* arguments.

Once the bistream is loaded, the board you try to retrieve the files on the TFTP server. If not successful or if the boot already timed out when you see the BIOS prompt, you can retry with the *netboot* command.

The images will be loaded to RAM and you should see Linux booting :)

### Load the Linux images to SDCard
For boards with SDCard support, the Linux images can be loaded from it. You need to copy the files from *images* directory to your SDCard root directory (with a FAT partition).

The images will be loaded to RAM and you should see Linux booting :)

> **Note**: For more information about the possible ways to load application code to the CPU with LiteX, please have a look at the LiteX's [wiki](https://github.com/enjoy-digital/litex/wiki/Load-Application-Code-To-CPU).

### Configure/Use the peripherals
Please visit the [HOWTO](https://github.com/litex-hub/linux-on-litex-vexriscv/blob/master/HOWTO.md) document to learn how to configure and use the peripherals from Linux.

[> Generating the Linux binaries (optional)
-------------------------------------------
```sh
$ git clone http://github.com/buildroot/buildroot
$ cd buildroot
$ make BR2_EXTERNAL=../linux-on-litex-vexriscv/buildroot/ litex_vexriscv_defconfig
$ make
```
The binaries are located in *output/images/* and *images/*.

[> Generating the Linux binaries with USB host support (optional)
-----------------------------------------------------------------
```sh
$ git clone http://github.com/buildroot/buildroot
$ cd buildroot
$ make BR2_EXTERNAL=../linux-on-litex-vexriscv/buildroot/ litex_vexriscv_usbhost_defconfig
$ make
```
The binaries are located in *output/images/* and *images/*.

[> Generating the OpenSBI binary (optional / part of the buildroot build sequence)
-------------------------------------------
```sh
$ git clone https://github.com/litex-hub/opensbi --branch 1.3.1-linux-on-litex-vexriscv
$ cd opensbi
$ make CROSS_COMPILE=riscv-none-embed- PLATFORM=litex/vexriscv
```

The binary will be located at *build/platform/litex/vexriscv/firmware/fw_jump.bin*.

[> Generating the VexRiscv Linux variant (optional)
---------------------------------------------------

If the VexRiscv configuration you ask isn't already generated, you will need to install java and SBT on your machine to enable their local on demande generation.

To install java and SBT see Install VexRiscv requirements: https://github.com/enjoy-digital/VexRiscv-verilog#requirements

[> Udev rules (optional)
----------------------------
Not needed but can make loading/flashing bitstreams easier:
```sh
$ git clone https://github.com/litex-hub/litex-buildenv-udev
$ cd litex-buildenv-udev
$ make install
$ make reload
```
