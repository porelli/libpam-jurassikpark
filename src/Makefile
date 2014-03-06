prefix = /usr
bindir = $(prefix)/bin
sharedir = $(prefix)/share
pamconfigdir = $(sharedir)/pam-configs
mandir = $(shkkaredir)/man
man1dir = $(mandir)/man1

clean:
	echo "Nothing to do!"

install: 
	mkdir -p $(DESTDIR)$(bindir)
	mkdir -p $(DESTDIR)$(sharedir)/libpam-jurassikpark
	mkdir -p $(DESTDIR)$(pamconfigdir)
	install -m 644 usr/bin/youdidntsaythemagicword $(DESTDIR)$(bindir)
	install -m 644 usr/share/libpam-jurassikpark/youdidntsaythemagicword.ogv $(DESTDIR)$(sharedir)/libpam-jurassikpark
	install -m 644 usr/share/pam-configs/jurassikpark $(DESTDIR)$(pamconfigdir)
