
You must understand the basics of the Linux boot sequence for the LPIC-1 exam. Before we get into the deeper details, this lesson is an overview of what goes on right after you press the power button on your Linux computer. We will also take a look at the kernel ring buffer, which will show us important information from the boot sequence.

The LPIC-1 candidate must be aware of and understand the init sequence using sysvinit. We will explore the layout of init in some depth, and show you how older Linux systems boot up.

The LPIC-1 candidate must be aware of upstart, the init replacement created by Ubuntu. With this lesson, we show you what improvements upstart attempted with regards to how it helped to get a computer to boot faster, along with some resiliency methods that it attempted.

Systemd is now the predominant initialization service used on Linux computers. The LPIC-1 candidate must understand the basics of systemd, and how it is used in the computer's boot up sequence.



*dmesg
*journalclt -k
*/etc/inittab
*/etc/rc.d
*S (sync) scripts and K (kill) scripts
*diff between init and upstart
*diff between systemd, upstart and init
	|-->units 
		|--> slices
			|-->slice types
