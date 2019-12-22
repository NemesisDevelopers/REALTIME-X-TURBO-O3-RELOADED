# REALTIME-X

Pre-Patched Linux Kernel Sources REALTIME-X
This Linux Kernel Have Some Additions That Are Not In The Main Tree.
Some Of Them Are Optimizations And New Features Like : >

1. CONFIG_PREEMPT_RT Patches > https://rt.wiki.kernel.org/index.php/Main_Page
   Selecting Expert Mode In Kernel Config

2. ZEN-SOURCES -ZEN Patches > https://github.com/zen-kernel/zen-kernel
   ZEN-INTERACTIVE
   mm-Proactive-compaction
   ZEN-Add-sysctl-and-CONFIG-to-disallow-unprivileged-C 
   
3. Con Kolivas -CK Patches > http://ck-hack.blogspot.com/ 
   MuQSS version 0.196 for linux-5.4 Multiple Queue Skiplist Scheduler As An Optional Choice.

4. Distro Specific Patches ArchLinux + Gentoo/Linux + Debian/Ubuntu + Intel Clear/Linux.

5. Added Script To Debloat The Linux Kernel And Free It Of Privative Firmware And Convert It Into -libre -gnu Linux.

6.Some Optimizations And Fixes Added .
  LL-kconfig-add-750Hz-timer-interrupt-kernel-config Thanks To Piotr Górski .
  zswap-b-tree.patch
  0003-v5.3_turbosched-v4.patch
  0011-ZFS-fix.patch
  -O3 patch To Compile With The Level 3 Of Compilers Optimizations.
  graysky's GCC patch To Be Able To Select -march=native.
  0001-ksm-patches.patch userspace-assisted KSM Thanks To  Oleksandr Natalenko .

7. Wireward Patches Updates For 5.4 Kernel. 
   0001-WireGuard-fast-modern-secure-kernel-VPN-tunnel.patch
   https://www.wireguard.com/


8.Conflict Fixing ETC.


Carlos Jimenez (JavaShin-X) 2019-2020.


The Linux Kernel is provided under:

	SPDX-License-Identifier: GPL-2.0 WITH Linux-syscall-note

Being under the terms of the GNU General Public License version 2 only,
according with:

	LICENSES/preferred/GPL-2.0

With an explicit syscall exception, as stated at:

	LICENSES/exceptions/Linux-syscall-note

In addition, other licenses may also apply. Please see:

	Documentation/process/license-rules.rst

for more details.