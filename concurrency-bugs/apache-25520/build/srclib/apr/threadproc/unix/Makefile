srcdir = /home/tyu/Documents/concurrency-bugs/apache-25520/httpd-2.0.48/srclib/apr/threadproc/unix
VPATH = /home/tyu/Documents/concurrency-bugs/apache-25520/httpd-2.0.48/srclib/apr/threadproc/unix

TARGETS = \
	proc.lo \
	procsup.lo \
	thread.lo \
	threadpriv.lo \
	signals.lo

# bring in rules.mk for standard functionality
include /home/tyu/Documents/concurrency-bugs/apache-25520/build/srclib/apr/build/apr_rules.mk

INCDIR=../../include
DEFOSDIR=$(INCDIR)/arch/unix
INCLUDES=-I$(INCDIR) -I$(srcdir)/$(INCDIR) -I$(DEFOSDIR) -I$(srcdir)/$(DEFOSDIR)

# DO NOT REMOVE
