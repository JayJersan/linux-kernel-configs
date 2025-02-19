# Linux Kernel Configs for Popular Distros
![CI status](https://github.com/nyrahul/linux-kernel-configs/actions/workflows/ci-verify.yml/badge.svg)

There is often a need to check a kernel config and other OS configuration to make a dev/design decision. The question often pops-up, does the popular distributions support the kernel config that the implementation expects? This is an attempt to answer that.

**My specific use-case**:
[KubeArmor](https://github.com/kubearmor/kubearmor) leverages LSMs (Linux Security Modules) and eBPF for in-kernel policy controls. We had to refer to kernel configs for making design/dev decisions regarding whether we can depend on a certain kernel primitive. The boot configs part of this repo helped in making an informed choice.

