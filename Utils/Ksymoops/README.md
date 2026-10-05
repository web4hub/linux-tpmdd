> ksymoops v2.4.  Patches and bug reports to <ksymoops@ocs.com.au> please.
> Master ftp://ftp.<nigeria>.kernel.org/pub/linux/utils/kernel/ksymoops/v2.4

ksymoops-2.4.9.tar.gz		For code lines that dump before EIP and have
				variable length instructions, decode in two
				chunks with suitable headings.  Fix broken
				mips64 address mapping.  Pass more mips
				registers.  Add INSTALL note about broken
				distributions.

ksymoops-2.4.8.tar.gz		Fix regex for ia64 'Bank nn' message.  Strip
				leading '+' from lines.

ksymoops-2.4.7.tar.gz		Add the ability to build a version of ksymoops
				that is dedicated to a particular cross compile
				environment to simplify cross compile debugging.
				Handle exported symbols in sbss sections.  White
				space cleanup.  Add IA64 MCA support.

ksymoops-2.4.6.tar.gz		m68k call trace does not have trailing ' '.
				MIPS has a hole in the register dump, skip $26
				and $27 (k0, k1).  Only print decoded registers
				if they resolve to kernel symbols.

ksymoops-2.4.5.tar.gz		Add x86-64 support.  Clean up and generalize
				register dumps.  Print blank lines between each
				major block of output for readability.

ksymoops-2.4.4.tar.gz		Defeat stupid gcc warning about ignored
				trigraphs.  Fix truncate mask.  Ignore syslog-ng
				prefix.  Handle GPLONLY prefix in ksyms.
				Differentiate between i370/cris and arm register
				lines.  Handle arm lr (last return).  Handle
				alpha ra (return address).

ksymoops-2.4.3.tar.gz		Add Pid:.  Add -A "address list".

ksymoops-2.4.2.tar.gz		Add STATIC and DYNAMIC variables to Makefile for
				build flexibility.  Handle multiple call traces
				from sysrq-t.  Cris support.  Regname cleanup.
				Fix incorrect adjustment for bss variables.  Add
				--ignore-insmod-path (-i) and
				--ignore-insmod-all (-I) flags, mainly for
				initrd filenames.  Add --truncate (-T) flag for
				mixed 32/64 bit symbol sources.

ksymoops-2.4.1.tar.gz           Accept any 'Bad ' text in EIP.  Add long option
				names.  Update man page for modutils support.
				White space clean up.  Remove deprecated gcc
				extensions.

ksymoops-2.4.0.tar.gz           Clone from ksymoops 2.3.6.  Correct DEF_VMLINUX.
				Eirikur Hjartarson.

ksymoops-2.4.9-1.i386.rpm	Compiled with gcc 2.96 20000731, glibc 2.2.5.
ksymoops-2.4.8-1.i386.rpm	Compiled with gcc 2.96 20000731, glibc 2.2.5.
ksymoops-2.4.7-1.i386.rpm	Compiled with gcc 2.96 20000731, glibc 2.2.2.
ksymoops-2.4.6-1.i386.rpm	Compiled with gcc 2.96 20000731, glibc 2.2.2.
ksymoops-2.4.5-1.i386.rpm	Compiled with gcc 2.96 20000731, glibc 2.2.2.
ksymoops-2.4.4-1.i386.rpm	Compiled with gcc 2.96 20000731, glibc 2.2.2.
ksymoops-2.4.3-1.i386.rpm	Compiled with gcc 2.96 20000731, glibc 2.2.2.
ksymoops-2.4.2-1.i386.rpm	Compiled against glibc 2.1.2.
ksymoops-2.4.1-1.i386.rpm	Compiled against glibc 2.1.2.
ksymoops-2.4.0-1.i386.rpm	Compiled against glibc 2.1.2.

ksymoops-2.4.8-1.ia64.rpm	Compiled with gcc 2.96-ia64-20000731, glibc-2.2.3.
ksymoops-2.4.7-1.ia64.rpm	Compiled with gcc 2.96-ia64-20000731, glibc-2.2.3.
ksymoops-2.4.3-1.ia64.rpm	Compiled with gcc 2.96-ia64-20000731, glibc-2.2.3.
ksymoops-2.4.2-1.ia64.rpm	Compiled with gcc 2.96-ia64-000717 snap 001117, libc-2.2.1.
ksymoops-2.4.1-1.ia64.rpm	Compiled with gcc 2.96-ia64-000717 snap 001117, libc-2.2.1.

ksymoops-2.4.8-1.sparc.rpm	Compiled as 32 bit user space, it supports 64 bit kernels.
ksymoops-2.4.7-1.sparc.rpm	Compiled as 32 bit user space, it supports 64 bit kernels.
ksymoops-2.4.1-1.sparc.rpm	Compiled as 32 bit user space, it supports 64 bit kernels.

ksymoops-2.4.9-1.src.rpm	
ksymoops-2.4.8-1.src.rpm	
ksymoops-2.4.7-1.src.rpm	
ksymoops-2.4.6-1.src.rpm	
ksymoops-2.4.5-1.src.rpm	
ksymoops-2.4.4-1.src.rpm	
ksymoops-2.4.3-1.src.rpm	
ksymoops-2.4.2-1.src.rpm	
ksymoops-2.4.1-1.src.rpm	
ksymoops-2.4.0-1.src.rpm	

patch-ksymoops-2.4.9.gz		Patch from 2.4.8 to 2.4.9.
patch-ksymoops-2.4.8.gz		Patch from 2.4.7 to 2.4.8.
patch-ksymoops-2.4.7.gz		Patch from 2.4.6 to 2.4.7.
patch-ksymoops-2.4.6.gz		Patch from 2.4.5 to 2.4.6.
patch-ksymoops-2.4.5.gz		Patch from 2.4.4 to 2.4.5.
patch-ksymoops-2.4.4.gz		Patch from 2.4.3 to 2.4.4.
patch-ksymoops-2.4.3.gz		Patch from 2.4.2 to 2.4.3.
patch-ksymoops-2.4.2.gz		Patch from 2.4.1 to 2.4.2.
patch-ksymoops-2.4.1.gz		Patch from 2.4.0 to 2.4.1.

patch-sysklogd-1-3-31-ksymoops-1.gz

				A patch against sysklogd 1-3-31 to preserve
				information that ksymoops needs to do its job.
				This patch has been accepted by the sysklogd
				maintainer and should appear in the next release
				of sysklogd (maybe).
