# Virtual Machines and Containers

- Bug detection
    - [HyperFuzzer: An Efficient Hybrid Fuzzer for Virtual CPUs](https://www.microsoft.com/en-us/research/uploads/prod/2021/09/hyperfuzzer-ccs21.pdf)(CCS'21)
    - [Scavenger:Misuse Error Handling leading to QEMU/KVM Escape](https://github.com/hustdebug/scavenger/blob/main/as-21-Pan-Scavenger-Misuse-Error-Handling-Leading-To-QEMU-KVM-Escape.pdf)(Black Hat Asia'21)
    - [Nyx: Greybox Hypervisor Fuzzing using Fast Snapshots and Affine Types ](https://git.ece.iastate.edu/data-storage-lab/papers/virtual-machines-and-containers/-/blob/master/paper/sec21-summer_schumilo.pdf) (Security'21)
    - [Agamotto: Accelerating Kernel Driver Fuzzing with Lightweight Virtual Machine Checkpoints ](https://git.ece.iastate.edu/data-storage-lab/papers/virtual-machines-and-containers/-/blob/master/paper/sec20-song_VMfuzzing.pdf) (Security'20)
- Debugging
    - [Reverse Debugging of Kernel Failures in Deployed Systems ](https://git.ece.iastate.edu/data-storage-lab/papers/virtual-machines-and-containers/-/blob/master/paper/atc20-ge.pdf) (ATC'20)
    - [Debugging Operating Systems with Time-Traveling Virtual Machines](https://git.ece.iastate.edu/data-storage-lab/papers/virtual-machines-and-containers/-/blob/master/paper/05_king.pdf)  (ATC'05)
- Provenance
    - [Panorama: Capturing System-wide Information Flow for Malware Detection and Analysis](https://dl.acm.org/doi/pdf/10.1145/1315245.1315261?casa_token=B5YUvs3s4boAAAAA:9qPP4FVMypioPSJ3tHki16f_Iiq85L0uONv0nQ0jbpRm2LlUBYYGJxTIbObmO_iP7F2EquNjE_8)  (CCS'07)
- QEMU Design & Extended
    - [A KVM-Based Logging and Replay System for Debugging Non-Deterministic Executions](https://www.researchgate.net/publication/269086963_A_KVM-Based_Logging_and_Replay_System_for_Debugging_Non-Deterministic_Executions) (CCV'10)
    - [Dynamically Translating x86 to LLVM using QEMU](http://infoscience.epfl.ch/record/149975/files/x86-llvm-translator-chipounov_2.pdf) (Technical Report 2010)
    - [QEMU, a Fast and Portable Dynamic Translator](https://git.ece.iastate.edu/data-storage-lab/papers/virtual-machines-and-containers/-/blob/master/paper/05_bellard.pdf)  (ATC'05)
- Deduplication
    - [UKSM: Swift Memory Deduplication via Hierarchical and Adaptive Memory Region Distilling](https://www.usenix.org/system/files/conference/fast18/fast18-xia.pdf) (FAST '18)
- Benchmarking
    - [CNSBench: A Cloud Native Storage Benchmark](https://www.usenix.org/system/files/fast21-merenstein.pdf) (FAST'21)
- Containers 
    - [Bare-metal, Virtual Machines and Containers in OpenStack](https://edisciplinas.usp.br/pluginfile.php/5539472/course/section/6024418/bare_metal_virtual_machines_and_containers_in_openstack.pdf) (ICIN'17)

# QEMU reference

- QEMU paper
    1. [On the interfacing between QEMU and SystemC for virtual platform construction: Using DMA as a case](https://git.ece.iastate.edu/data-storage-lab/papers/virtual-machines-and-containers/-/blob/master/QEMU_reference/1-s2.0-S1383762112000045-main.pdf)
    2. [TQSIM: A fast cycle-approximate processor simulator based on QEMU](https://git.ece.iastate.edu/data-storage-lab/papers/virtual-machines-and-containers/-/blob/master/QEMU_reference/1-s2.0-S1383762116300297-main.pdf)
    3. [A QEMU and SystemC-Based Cycle-Accurate ISS for Performance Estimation on SoC Development](https://git.ece.iastate.edu/data-storage-lab/papers/virtual-machines-and-containers/-/blob/master/QEMU_reference/05737847.pdf)
    4. [A Fault Injection System Based on QEMU Simulator and Designed for BIT Software Testing](https://git.ece.iastate.edu/data-storage-lab/papers/virtual-machines-and-containers/-/blob/master/QEMU_reference/AMM.347-350.580.pdf)
    5. [QEMU, a Fast and Portable Dynamic Translator (ATC'05)](https://git.ece.iastate.edu/data-storage-lab/papers/virtual-machines-and-containers/-/blob/master/QEMU_reference/bellard.pdf)
    6. [Configurable system call tracer in QEMU emulator](https://git.ece.iastate.edu/data-storage-lab/papers/virtual-machines-and-containers/-/blob/master/QEMU_reference/isp_30_2018_3_93.pdf)
- Book chapter
    1. [QEMU Detailed Study](https://git.ece.iastate.edu/data-storage-lab/papers/virtual-machines-and-containers/-/blob/master/QEMU_reference/pdfhC5rVdz7U8.pdf)
    2. [QEMU + GDB Debugging Environment](https://git.ece.iastate.edu/data-storage-lab/papers/virtual-machines-and-containers/-/blob/master/QEMU_reference/qemu_gdb.pdf)
    3. [QEMU Emulator User Documentation](https://git.ece.iastate.edu/data-storage-lab/papers/virtual-machines-and-containers/-/blob/master/QEMU_reference/qemu-doc.pdf)
    4. [Fuzzing QEMU Device Emulation](https://www.qemu.org/2019/11/07/device-fuzzing/)
    5. [Developer manual](https://qemu.readthedocs.io/en/latest/devel/code-of-conduct.html)
- Presentation
    1. [Security in QEMU How Virtual Machines provide Isolation -Stefan Hajnoczi](https://git.ece.iastate.edu/data-storage-lab/papers/virtual-machines-and-containers/-/blob/master/QEMU_reference/stefanha-kvm-forum-2018.pdf)
    2. [Tracing in the QEMU emulator user case study -Stefan Hajnoczi](https://git.ece.iastate.edu/data-storage-lab/papers/virtual-machines-and-containers/-/blob/master/QEMU_reference/TracingSummit2014-Tracing-Qemu.pdf)
    3. [QEMU: Architecture and Internals Lecture for the Embedded Systems Course -Manolis Marazakis](https://git.ece.iastate.edu/data-storage-lab/papers/virtual-machines-and-containers/-/blob/master/QEMU_reference/qemu-internals-slides-may6-2014.pdf)
    4. [QEMU Code Overview - Stefan Hajnoczi](https://git.ece.iastate.edu/data-storage-lab/papers/virtual-machines-and-containers/-/blob/master/QEMU_reference/qemu-code-overview.pdf)
    5. [QEMU - Jussi Knuuttila](https://git.ece.iastate.edu/data-storage-lab/papers/virtual-machines-and-containers/-/blob/master/QEMU_reference/qemu.pdf)
    6. [VIRTIO 1.0](https://vmsplice.net/~stefan/virtio-devconf-2014.pdf)
    7. QEMU disk I/O injection framework: blkdebug:[example](https://git.qemu.org/?p=qemu.git;a=blob_plain;f=tests/qemu-iotests/046;h=e528b67cc62fca2b9bf64d898dcc259608a564dc;hb=HEAD)
    8. [Using NVDIMM under KVM](https://vmsplice.net/~stefan/stefanha-fosdem-2017.pdf): [video](https://archive.fosdem.org/2017/schedule/event/iaas_usinvdund/)
    9. [Applying Polling Techniques to QEMU](https://vmsplice.net/~stefan/stefanha-kvm-forum-2017.pdf): [video](https://www.youtube.com/watch?v=g2Wlia9bo88)
    10. [Security in QEMU-How Virtual Machines provide Isolation](https://vmsplice.net/~stefan/stefanha-kvm-forum-2018.pdf)
    11. [Bring SCSI support into QEMU block layer](https://static.sched.com/hosted_files/kvmforum2020/36/Chinamobile-Bring%20SCSI%20support%20into%20QEMU%20block%20layer.pdf)
    12. [QEMU snapshots are slow. Really?](https://static.sched.com/hosted_files/kvmforum2020/8b/FastVM%20snapshots.pdf)
    13. [Virtual Device Fuzzing in QEMU](https://static.sched.com/hosted_files/kvmforum2020/c7/Fuzzing_KVMForum_2020.pdf)
    14. [Virtio-(balloon|pmem|mem): Managing Guest Memory](https://static.sched.com/hosted_files/kvmforum2020/8e/KVM%20Forum%202020%20Virtio-%28balloon%20pmem%20mem%29%20Managing%20Guest%20Memory.pdf)

