# What

_v9fs_ is the code-name for the linux kernel client implementation of the [Plan 9](https://9p.io/plan9/) remote file system protocol [9p](http://ericvh.github.io/9p-rfc/).  The original kernel port was documented in [this paper](https://www.usenix.org/conference/2005-usenix-annual-technical-conference/presentation/grave-robbers-outer-space-using-9p20), it later added support for virtio so that it could be used as a [paravirtualized file system](https://citeseerx.ist.psu.edu/document?repid=rep1&type=pdf&doi=6d643fee833b7cf1db33b53fa2a6d96a217a3170#page=109) interface for KVM.  Documentation for how to use v9fs with qemu/kvm can be found (here)[https://wiki.qemu.org/Documentation/9psetup], and there are also examples of how to use [9p as your root filesystem](https://wiki.qemu.org/Documentation/9p_root_fs).

This Github group contains a mirror of the official [kernel.org development trees](https://git.kernel.org/pub/scm/linux/kernel/git/ericvh/v9fs.git) for v9fs as well as mirrors of several of the more popular servers, as well as support repositories for testing and performance measurement.

# Where

You can contribute to v9fs by joining the [mailing list](mailto:v9fs+subscribe@lists.linux.dev), the archives of the mailing list are available [here](https://lore.kernel.org/v9fs/)
