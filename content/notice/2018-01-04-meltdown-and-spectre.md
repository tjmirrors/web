---
title: "Meltdown和Spectre漏洞修复状态跟踪"
date: 2018-01-04T23:00:00+08:00
---

影响大量现代CPU的[Meltdown](https://meltdownattack.com/)和[Spectre](https://spectreattack.com/)漏洞近期引起了业界的广泛关注。Google的Project Zero团队于1月3日公布了这批漏洞的[技术细节](https://googleprojectzero.blogspot.com/2018/01/reading-privileged-memory-with-side.html)。这批漏洞目前存在3个已知变体，分别是[CVE-2017-5753](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2017-5753), [CVE-2017-5715](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2017-5715), [CVE-2017-5754](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2017-5754)。下面整理了部分Linux发行版、操作系统厂商、虚拟化厂商等针对这批漏洞的跟进状态，方便用户及时获取安全补丁信息。

---

- [Android](https://support.google.com/faqs/answer/7622138#android)
- CentOS: [Meltdown and Spectre](https://www.centos.org/forums/viewtopic.php?t=65591), [The CentOS-announce January 2018 Archive by thread](https://lists.centos.org/pipermail/centos-announce/2018-January/)
- debian: [CVE-2017-5753](https://security-tracker.debian.org/tracker/CVE-2017-5753), [CVE-2017-5715](https://security-tracker.debian.org/tracker/CVE-2017-5715), [CVE-2017-5754](https://security-tracker.debian.org/tracker/CVE-2017-5754)
- RHEL: [Kernel Side-Channel Attacks](https://access.redhat.com/security/vulnerabilities/speculativeexecution)
- SUSE: [SUSE Addresses Meltdown and Spectre Vulnerabilities](https://www.suse.com/c/suse-addresses-meltdown-spectre-vulnerabilities/)
- Ubuntu: [Spectre And Meltdown](https://wiki.ubuntu.com/SecurityTeam/KnowledgeBase/SpectreAndMeltdown)

---

- Apple: [About speculative execution vulnerabilities in ARM-based and Intel CPUs](https://support.apple.com/en-us/HT208394)
- Microsoft: [ADV180002 | Guidance to mitigate speculative execution side-channel vulnerabilities](ADV180002 | Guidance to mitigate speculative execution side-channel vulnerabilities), [Windows Server Guidance to protect against the speculative execution side-channel vulnerabilities](https://support.microsoft.com/en-us/help/4072698/windows-server-guidance-to-protect-against-the-speculative-execution-s)

---

- VMware: [VMware ESXi, Workstation and Fusion updates address side-channel analysis due to speculative execution](https://www.vmware.com/us/security/advisories/VMSA-2018-0002.html)
- Xen: [Information leak via side effects of speculative execution](https://xenbits.xen.org/xsa/advisory-254.html)

---

- [Chrome](https://support.google.com/faqs/answer/7622138#chrome)
- Firefox: [Mitigations landing for new class of timing attack](https://blog.mozilla.org/security/2018/01/03/mitigations-landing-new-class-timing-attack/)

---

- ARM: [Vulnerability of Speculative Processors to Cache Timing Side-Channel Mechanism](https://developer.arm.com/support/security-update), [Cache Speculation Side-channels whitepaper](https://developer.arm.com/support/security-update/download-the-whitepaper)
- Intel: [Speculative Execution and Indirect Branch Prediction Side Channel Analysis Method](https://security-center.intel.com/advisory.aspx?intelid=INTEL-SA-00088&languageid=en-fr), [Speculative Execution Branch Prediction Side Channel and Branch Prediction Analysis Method](https://01.org/security/advisories/intel-oss-10002), [Speculative Execution Data Cache and Indirect Branch Prediction Method Side Channel Analysis](https://01.org/security/advisories/intel-oss-10003)
- NVIDIA: [Security Notice: Speculative Side Channels](http://nvidia.custhelp.com/app/answers/detail/a_id/4609)

