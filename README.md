## Use at your own risk
###### Patches developed and offered only for the last, stable line (not EOL). 
###### Active support is offered only for this kernel line. 
###### Any others are not supported anymore, but you can find patchsets for previous versions of kernel in "archive" directory. 
###### The patchset not includes upstream bugfixes patches from kernel line 5.XX. 
###### You should applied them on your own. It should be possible to applied patchset on any supported version of kernel, but I personally support only the last possible version of kernel from stable branch.
###### The patchset contains various patches developed by their authors, always in the newest versions and sometimes with fixes from master branch or from the other authors when it's necessary. 

***

* [bfq improvements](https://groups.google.com/forum/#!forum/bfq-iosched) - latest fixes authored by Paolo Valente and BFQ Team

* ~~[bfq-dev](https://github.com/Algodev-github/bfq-mq/tree/dev-bfq-on-5.6) - latest fixes authored by Paolo Valente and BFQ Team~~

* ~~[bfq-dev-lucjan](https://github.com/sirlucjan/bfq-mq-lucjan/tree/dev-bfq-on-5.6-lucjan) - latest fixes authored by Paolo Valente and BFQ Team and forked by Piotr Gorski~~

* ~~[bfq-dev-lucjan-rc](https://github.com/sirlucjan/kernel-patches/tree/master/5.11/bfq-dev-lucjan) / [bfq-dev-lucjan-rc](https://gitlab.com/sirlucjan/kernel-patches/tree/master/5.11/bfq-dev-lucjan) - specific patches authored by Paolo Valente and Piotr Gorski~~

* [bfq-lucjan](https://github.com/sirlucjan/kernel-patches/tree/master/5.12/bfq-lucjan) / [bfq-lucjan](https://gitlab.com/sirlucjan/kernel-patches/tree/master/5.12/bfq-lucjan) - specific patches authored by Paolo Valente and Piotr Gorski

* [graysky's GCC/Clang patch](https://github.com/graysky2/kernel_compiler_patch) - version for gcc v11/clang v12

* [Project C](https://gitlab.com/alfredchen/linux-prjc/tree/linux-5.12.y-prjc) / [Project C blog](http://cchalpha.blogspot.com) - contains the newest vesion with latest fixes

* [random fixes from zen-kernel](https://github.com/zen-kernel/zen-kernel/tree/5.12/master) - specific patches authored by Jan Alexander Steffens and ZEN Kernel Team

* [random fixes from pfkernel](https://github.com/pfactum/pf-kernel/tree/pf-5.12) / [random fixes from pfkernel](https://gitlab.com/post-factum/pf-kernel/tree/pf-5.12) - for example patches from Arch Linux or specific patches authored by Oleksandr Natalenko

* [fixes from ClearLinux](https://github.com/clearlinux-pkgs/linux) - specific patches authored by ClearLinux Team

* [AUFS](https://github.com/sfjro/aufs5-standalone/tree/aufs5.12) / [AUFS](http://aufs.sourceforge.net) - advanced multi-layered unification filesystem

* [UKSM (sources)](https://github.com/dolohow/uksm) / [UKSM (info)](https://www.usenix.org/sites/default/files/conference/protected-files/fast18_slides_xia.pdf) - resync from dolohow’s github

* [LL-patches](https://github.com/sirlucjan/kernel-patches/tree/master/5.12/ll-patches) / [LL-patches](https://gitlab.com/sirlucjan/kernel-patches/tree/master/5.12/ll-patches) - specific patches authored by Piotr Gorski

* [LL-branding](https://github.com/sirlucjan/kernel-patches/tree/master/5.12/ll-branding) / [LL-branding](https://gitlab.com/sirlucjan/kernel-patches/tree/master/5.12/ll-branding) - specific patches authored by Piotr Gorski

***

###### Some patches for BFQ/block-stable conflict with patches for BFQ-dev/block-mainline.

###### To use lucjan-kernels smoothly apply ll-reverts before linux-lucjan patch. Otherwise the kernel will not compile.

* ~~[ll-reverts](https://github.com/sirlucjan/kernel-patches/tree/master/5.11-dev/ll-reverts) / [ll-reverts](https://gitlab.com/sirlucjan/kernel-patches/tree/master/5.11-dev/ll-reverts) - specific patches authored by Piotr Gorski~~

#### You've been warned. 
