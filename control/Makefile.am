# Makefile.am for installation/general

controldir = /etc/YaST2

control_DATA = \
	firstboot.xml 

# Note: The control.glade -> control.xml symlink is required to make xgettext
# auto-detect the type of this file (glade) so it will extract all
# <label>..</label> tags. The symlink is created in the toplevel
# configure.in.in file upon "autoconf" (via "make -f Makefile.cvs").
# Unfortunately, CVS doesn't support checking in symlinks - it would duplicate
# the file. 


EXTRA_DIST =  $(control_DATA)

include $(top_srcdir)/Makefile.am.common
