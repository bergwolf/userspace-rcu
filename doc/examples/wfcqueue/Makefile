# Copyright (C) 2013  Mathieu Desnoyers <mathieu.desnoyers@efficios.com>
#
# THIS MATERIAL IS PROVIDED AS IS, WITH ABSOLUTELY NO WARRANTY EXPRESSED
# OR IMPLIED.  ANY USE IS AT YOUR OWN RISK.
#
# Permission is hereby granted to use or copy this program for any
# purpose,  provided the above notices are retained on all copies.
# Permission to modify the code and to distribute modified code is
# granted, provided the above notices are retained, and a notice that
# the code was modified is included with the above copyright notice.
#
# This makefile is purposefully kept simple to support GNU and BSD make.

all:
	$(MAKE) -f Makefile.cds_wfcq_enqueue
	$(MAKE) -f Makefile.cds_wfcq_dequeue
	$(MAKE) -f Makefile.cds_wfcq_splice

.PHONY: clean
clean:
	$(MAKE) -f Makefile.cds_wfcq_enqueue clean
	$(MAKE) -f Makefile.cds_wfcq_dequeue clean
	$(MAKE) -f Makefile.cds_wfcq_splice clean
