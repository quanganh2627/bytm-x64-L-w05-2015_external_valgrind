
include $(top_srcdir)/Makefile.tool-tests.am

dist_noinst_SCRIPTS = \
	invoker simulate_control_c make_local_links \
	filter_gdb filter_make_empty \
	filter_memcheck_monitor filter_stderr filter_vgdb \
	filter_helgrind_monitor send_signal

EXTRA_DIST = \
	README_DEVELOPERS \
	hginfo.stderrB.exp \
	hginfo.stderr.exp \
	hginfo.stdinB.gdb \
	hginfo.stdoutB.exp \
	hginfo.vgtest \
	mcblocklistsearch.stderr.exp \
	mcblocklistsearch.stdinB.gdb \
	mcblocklistsearch.vgtest \
	mcblocklistsearch.stderrB.exp \
	mcbreak.stderrB.exp \
	mcbreak.stderr.exp \
	mcbreak.stdinB.gdb \
	mcbreak.stdoutB.exp \
	mcbreak.stdout.exp \
	mcbreak.vgtest \
	mcclean_after_fork.stderrB.exp \
	mcclean_after_fork.stderr.exp \
	mcclean_after_fork.stdinB.gdb \
	mcclean_after_fork.stdoutB.exp \
	mcclean_after_fork.vgtest \
	mchelp.stderrB.exp \
	mchelp.stderr.exp \
	mchelp.stdoutB.exp \
	mchelp.vgtest \
	mcinfcallRU.stderrB.exp \
	mcinfcallRU.stderr.exp \
	mcinfcallRU.stdinB.gdb \
	mcinfcallRU.vgtest \
	mcinfcallWSRU.stderrB.exp \
	mcinfcallWSRU.stderr.exp \
	mcinfcallWSRU.stdinB.gdb \
	mcinfcallWSRU.vgtest \
	mcinvokeRU.stderrB.exp \
	mcinvokeRU.stderr.exp \
	mcinvokeRU.stdoutB.exp \
	mcinvokeRU.vgtest \
	mcinvokeWS.stderrB.exp \
	mcinvokeWS.stderr.exp \
	mcinvokeWS.stdoutB.exp \
	mcinvokeWS.vgtest \
	mcleak.stderrB.exp \
	mcleak.stderr.exp \
	mcleak.stdinB.gdb \
	mcleak.stdoutB.exp \
	mcleak.vgtest \
	mcmain_pic.stderrB.exp \
	mcmain_pic.stderr.exp \
	mcmain_pic.stdinB.gdb \
	mcmain_pic.stdoutB.exp \
	mcmain_pic.stdout.exp \
	mcmain_pic.vgtest \
	mcmain_pic.stderrB.exp \
	mcmain_pic.stderr.exp \
	mcmain_pic.stdinB.gdb \
	mcmain_pic.stdoutB.exp \
	mcmain_pic.stdout.exp \
	mcsignopass.stderrB.exp \
	mcsignopass.stderr.exp \
	mcsignopass.stdinB.gdb \
	mcsignopass.stdoutB.exp \
	mcsignopass.vgtest \
	mcsigpass.stderrB.exp \
	mcsigpass.stderr.exp \
	mcsigpass.stdinB.gdb \
	mcsigpass.stdoutB.exp \
	mcsigpass.vgtest \
	mcvabits.stderrB.exp \
	mcvabits.stderr.exp \
	mcvabits.stdinB.gdb \
	mcvabits.stdoutB.exp \
	mcvabits.vgtest \
	mcwatchpoints.stderrB.exp \
	mcwatchpoints.stderr.exp \
	mcwatchpoints.stdinB.gdb \
	mcwatchpoints.stdoutB.exp \
	mcwatchpoints.vgtest \
	mssnapshot.stderrB.exp \
	mssnapshot.stderr.exp \
	mssnapshot.stdinB.gdb \
	mssnapshot.stdoutB.exp \
	mssnapshot.vgtest \
	nlcontrolc.stderrB.exp \
	nlcontrolc.stderr.exp \
	nlcontrolc.stdinB.gdb \
	nlcontrolc.stdoutB.exp \
	nlcontrolc.vgtest \
	nlfork_chain.stderr.exp \
	nlfork_chain.stdout.exp \
	nlfork_chain.vgtest \
	nlgone_abrt.stderr.exp \
	nlgone_abrt.stderrB.exp \
	nlgone_abrt.stdinB.gdb \
	nlgone_abrt.stdoutB.exp \
	nlgone_abrt.vgtest \
	nlgone_exit.stderr.exp \
	nlgone_exit.stderrB.exp \
	nlgone_exit.stdinB.gdb \
	nlgone_exit.stdoutB.exp \
	nlgone_exit.vgtest \
	nlgone_return.stderr.exp \
	nlgone_return.stderrB.exp \
	nlgone_return.stdinB.gdb \
	nlgone_return.stdoutB.exp \
	nlgone_return.vgtest \
	nlpasssigalrm.vgtest \
	nlpasssigalrm.stderrB.exp \
	nlpasssigalrm.stderr.exp \
	nlpasssigalrm.stdinB.gdb \
	nlpasssigalrm.stdoutB.exp \
	nlself_invalidate.stderrB.exp \
	nlself_invalidate.stderr.exp \
	nlself_invalidate.stdinB.gdb \
	nlself_invalidate.vgtest \
	nlsigvgdb.vgtest \
	nlsigvgdb.stderr.exp \
	nlsigvgdb.stderrB.exp \
	nlsigvgdb.stdinB.gdb \
	nlvgdbsigqueue.vgtest \
	nlvgdbsigqueue.stderrB.exp \
	nlvgdbsigqueue.stderr.exp \
	nlvgdbsigqueue.stdinB.gdb \
	nlvgdbsigqueue.stdoutB.exp

check_PROGRAMS = \
	clean_after_fork \
	fork_chain \
	gone \
	main_pic \
	passsigalrm \
	self_invalidate \
	sleepers \
	t \
	watchpoints

AM_CFLAGS   += $(AM_FLAG_M3264_PRI)
AM_CXXFLAGS += $(AM_FLAG_M3264_PRI)

LDADD = -lpthread

main_pic_LDFLAGS = -pie
main_pic_CFLAGS	 = $(AM_CFLAGS) -fPIC
