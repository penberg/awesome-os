# Awesome Operating Systems

A curated list of awesome resources on operating system design and implementation.

## Conferences

Some of the conferences where to find publications on operating systems research:

* [ACM Architectural Support for Programming Languages and Operating Systems](https://dl.acm.org/conference/asplos) (ASPLOS)
* [ACM Symposium on Operating Systems Principles](https://dl.acm.org/conference/sosp) (SOSP)
* USENIX Annual Technical Conference (ATC)
* USENIX Symposium on Operating Systems Design and Implementation (OSDI)
* Horkshop on Hot Topics in Operating Systems (HotOS)

## Papers

"[The UNIX Time-Sharing System](https://dsf.berkeley.edu/cs262/unix.pdf)" (1974) by Dennis M. Ritchie and Ken Thompson.

The seminal paper on the UNIX operating system by its creators.

"[Exokernel: An Operating System Architecture for Application-Level Resource Management](https://web.eecs.umich.edu/~mosharaf/Readings/Exokernel.pdf)" (1995) by Dawson R. Engler et al.

The exokernel approach aims to eliminate operating system abstractions by having a small kernel that exports hardware resources with a low-level interface to untrusted _library operating systems_. 

"[The Design and Implementation of an Operating System to Support Distributed Multimedia Applications](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.38.8833&rep=rep1&type=pdf)" (1996) by Ian Leslie et al. IEEE Journal on Selected Areas in Communications

"[Corey: An Operating System for Many Cores](https://www.usenix.org/legacy/events/osdi08/tech/full_papers/boyd-wickizer/boyd_wickizer.pdf)" (2008) by Silas Boyd-Wickizer et al. OSDI '08

"[The Multikernel: A new OS architecture for scalable multicore systems](https://www.sigops.org/s/conferences/sosp/2009/papers/baumann-sosp09.pdf)" (2009) by Andrew Baumann et al. SOSP '09

This paper describes the multikernel design approach to operating system kernels, which aims to improve scalability, and support heterogenenous and diverse hardware. There's also an awesome [retrospective](https://www.sigops.org/2021/fish-in-a-barrel-an-insiders-retrospective-of-the-sosp09-multikernel-paper/).

"[seL4: Formal Verification of an OS Kernel](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.150.4815&rep=rep1&type=pdf)" (2009) by Gerwin Klein et al. SOSP '09

This paper describes seL4, the first formally proven general-purpose operating system.

"[Rethinking the Library OS from the Top Down](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/asplos2011-drawbridge.pdf)" (2011) by Donald E. Porter et al. ASPLOS '11.

"[Dune: Safe User-level Access to Privileged CPU Features](https://www.usenix.org/system/files/conference/osdi12/osdi12-final-117.pdf)" (2012) by Adam Belay et al. OSDI '12.

"[Unikernels: Library Operating Systems for the Cloud](https://anil.recoil.org/papers/2013-asplos-mirage.pdf)" (2013) by Anil Madhavapeddy et al. ASPLOS ’13

"[Arrakis: The Operating System is the Control Plane](https://www.usenix.org/conference/osdi14/technical-sessions/presentation/peter)" (2014) by Simon Peter et al. OSDI '14

"[IX: A Protected Dataplane Operating System for High Throughput and Low Latency](https://www.usenix.org/system/files/conference/osdi14/osdi14-paper-belay.pdf)" (2014) by Adam Belay et al. OSDI '14

"[Multiprogramming a 64 kB Computer Safely and Efficiently](https://www.tockos.org/assets/papers/tock-sosp2017.pdf)" (2017) by Amit Levy et al. SOSP '17.

This paper details an operating system design where the type-safety of Rust programming language provides memory protection on MMU-less hardware.

"[LegoOS: A Disseminated, Distributed OS for Hardware Resource Disaggregation](https://www.usenix.org/system/files/osdi18-shan.pdf)" (2018) by Yizhou Shan et al. OSDI '18

"[RedLeaf: Isolation and Communication in a Safe Operating System](https://www.usenix.org/conference/osdi20/presentation/narayanan-vikram)" (2020) by Vikram Narayanan et al. OSDI '20

"[Twizzler: a Data-Centric OS for Non-Volatile Memory](https://www.usenix.org/system/files/atc20-bittman.pdf)" (2020) by Daniel Bittman et al. ATC '20.

"[The Demikernel Datapath OS Architecture for Microsecond-scale Datacenter Systems](https://irenezhang.net/papers/demikernel-sosp21.pdf)" (2021) by Irene Zhang et al. SOSP '21

## Operating Systems

* [Barrelfish](http://www.barrelfish.org)
* [Demikernel](https://github.com/demikernel/demikernel)
* [Kerla](https://github.com/nuta/kerla)
* [Tock](https://www.tockos.org)
* [Twizzler](https://twizzler.io)
