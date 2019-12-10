## Use at your own risk
###### Patches developed and offered only for the last, stable line (not EOL). 
###### Active support is offered only for this kernel line. 
###### Any others are not supported anymore, but you can find patchsets for previous versions of kernel in "archive" directory. 
###### The patchset not includes upstream bugfixes patches from kernel line 5.XX. 
###### You should applied them on your own. It should be possible to applied patchset on any supported version of kernel, but I personally support only the last possible version of kernel from stable branch.
###### The patchset contains various patches developed by their authors, always in the newest versions and sometimes with fixes from master branch or from the other authors when it's necessary. 

***

* [bfq improvements](https://groups.google.com/forum/#!forum/bfq-iosched) - latest fixes authored by Paolo Valente and BFQ Team

* [bfq-dev](https://github.com/Algodev-github/bfq-mq/tree/dev-bfq-on-5.4) - latest fixes authored by Paolo Valente and BFQ Team

* [bfq-lucjan-dev](https://github.com/sirlucjan/bfq-mq-lucjan/tree/dev-bfq-on-5.4-lucjan) - latest fixes authored by Paolo Valente and BFQ Team and forked by Piotr Gorski
 
* [graysky's GCC patch](https://github.com/graysky2/kernel_gcc_patch) - version for gcc 9.1

* [BMQ](https://gitlab.com/alfredchen/linux-bmq/tree/linux-5.4.y-bmq) / [BMQ blog](http://cchalpha.blogspot.com) - contains the newest vesion with latest fixes

* [random fixes from zen-kernel](https://github.com/zen-kernel/zen-kernel/tree/5.4/master) - specific patches authored by Jan Alexander Steffens and ZEN Kernel Team

* [random fixes from pfkernel](https://github.com/pfactum/pf-kernel/tree/pf-5.4) / [random fixes from pfkernel](https://gitlab.com/post-factum/pf-kernel/tree/pf-5.4) - for example patches from Arch Linux or specific patches authored by Oleksandr Natalenko

* [fixes from ClearLinux](https://github.com/clearlinux-pkgs/linux) - specific patches authored by ClearLinux Team

* ~~[AUFS](https://github.com/sfjro/aufs5-standalone/tree/aufs5.4) / [AUFS](http://aufs.sourceforge.net) - advanced multi-layered unification filesystem~~

* [WireGuard](https://git.zx2c4.com/WireGuard) - fast and secure kernelspace VPN

* [LL-patches](https://github.com/sirlucjan/kernel-patches/tree/master/5.4/ll-patches) / [LL-patches](https://gitlab.com/sirlucjan/kernel-patches/tree/master/5.4/ll-patches) - specific patches authored by Piotr Gorski

* [LL-branding](https://github.com/sirlucjan/kernel-patches/tree/master/5.4/ll-branding) / [LL-branding](https://gitlab.com/sirlucjan/kernel-patches/tree/master/5.4/ll-branding) - specific patches authored by Piotr Gorski

***

###### Some patches for BFQ conflict with patches for BFQ-dev.

###### To use lucjan-kernels smoothly apply bfq-reverts before linux-lucjan patch. Otherwise the kernel will not compile.

* ~~[bfq-reverts](https://github.com/sirlucjan/kernel-patches/tree/master/5.4/bfq-reverts) / [bfq-reverts](https://gitlab.com/sirlucjan/kernel-patches/tree/master/5.4/bfq-reverts) - specific patches authored by Piotr Gorski~~

#### You've been warned. 
