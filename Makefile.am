#
#  Original xinput:
#  Copyright 1996 by Frederic Lepied, France. <Frederic.Lepied@sugix.frmug.org>
#  Copyright 2005 Adam Jackson.
#
#  Original xrandr:
#  Copyright © 2001 Keith Packard, member of The XFree86 Project, Inc.
#  Copyright © 2002 Hewlett Packard Company, Inc.
#  Copyright © 2006 Intel Corporation
#
#  xrandr-align:
#
#  Copyright © 2012 Paul Wolneykien <manowar@altlinux.org>, ALT Linux Ltd.
#
#  Permission is hereby granted, free of charge, to any person obtaining a
#  copy of this software and associated documentation files (the "Software"),
#  to deal in the Software without restriction, including without limitation
#  on the rights to use, copy, modify, merge, publish, distribute, sub
#  license, and/or sell copies of the Software, and to permit persons to whom
#  the Software is furnished to do so, subject to the following conditions:
#
#  The above copyright notice and this permission notice (including the next
#  paragraph) shall be included in all copies or substantial portions of the
#  Software.
#
#  THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
#  IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
#  FITNESS FOR A PARTICULAR PURPOSE AND NON-INFRINGEMENT.  IN NO EVENT SHALL
#  ADAM JACKSON BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
#  IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
#  CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

AUTOMAKE_OPTIONS = foreign
SUBDIRS = src man scripts configs

MAINTAINERCLEANFILES = ChangeLog INSTALL

.PHONY: ChangeLog INSTALL

INSTALL:
	$(INSTALL_CMD)

ChangeLog:
	$(CHANGELOG_CMD)

dist-hook: ChangeLog INSTALL

autostartdir = $(sysconfdir)/xdg/autostart
autostart_DATA = xrandr-align-monitor.desktop xrandr-align-gravitate.desktop
