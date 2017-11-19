EXTRA_DIST = \
	Lioshi \
	Lioshi-Mono-Dark \
	COPYING \
	AUTHORS \
	README.md

themedir = $(datadir)/icons

install-data-hook:
	$(MKDIR_P) $(DESTDIR)$(datadir)/icons
	cp -Rv Lioshi $(DESTDIR)$(datadir)/icons/.
	cp -Rv Lioshi-Mono-Dark $(DESTDIR)$(datadir)/icons/.

uninstall-hook:
	test -e $(DESTDIR)$(datadir)/icons/Lioshi && rm -rfv $(DESTDIR)$(datadir)/icons/Lioshi
	test -e $(DESTDIR)$(datadir)/icons/Lioshi-Mono-Dark && rm -rfv $(DESTDIR)$(datadir)/icons/Lioshi-Mono-Dark
