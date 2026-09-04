---
title: "Support for Fast and Reliable VMM Live Upgrades in Libvirt"
collection: talks
type: "Talk"
permalink: /talks/live-upgrade-kvm-forum
venue: "KVM Forum 2021"
date: 2021-09-15
location: "(online)"
slidesurl: "https://prachatos.github.io/files/vmm-live-upgrade.pptx"
videourl: "https://www.youtube.com/watch?v=0C_OtcIJgpU"
---

This talk discussed an end-to-end solution for live upgrades, i.e. upgrading the hypervisor without a reboot, using local live migration (for KVM/qemu/libvirt). We discussed how to minimize memory and state transfer during a local migration through passing FDs between co-operating qemu processes, orchestrated by libvirt.

