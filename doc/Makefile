# Makefile.in generated by automake 1.16.3 from Makefile.am.
# doc/Makefile.  Generated from Makefile.in by configure.

# Copyright (C) 1994-2020 Free Software Foundation, Inc.

# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.



# FIG : Facility for Interactive Generation of figures
# Copyright (c) 1985-1988 by Supoj Sutanthavibul
# Parts Copyright (c) 1989-2015 by Brian V. Smith
# Parts Copyright (c) 1991 by Paul King
# Parts Copyright (c) 2016-2021 by Thomas Loimer
#
# Any party obtaining a copy of these files is granted, free of charge, a
# full and unrestricted irrevocable, world-wide, paid up, royalty-free,
# nonexclusive right and license to deal in this software and documentation
# files (the "Software"), including without limitation the rights to use,
# copy, modify, merge, publish, distribute, sublicense and/or sell copies
# of the Software, and to permit persons who receive copies from any such
# party to do so, with the only requirement being that the above copyright
# and this permission notice remain intact.
#
#
# doc/Makefile.am
# Author: Thomas Loimer, 2016, 2021


am__is_gnu_make = { \
  if test -z '$(MAKELEVEL)'; then \
    false; \
  elif test -n '$(MAKE_HOST)'; then \
    true; \
  elif test -n '$(MAKE_VERSION)' && test -n '$(CURDIR)'; then \
    true; \
  else \
    false; \
  fi; \
}
am__make_running_with_option = \
  case $${target_option-} in \
      ?) ;; \
      *) echo "am__make_running_with_option: internal error: invalid" \
              "target option '$${target_option-}' specified" >&2; \
         exit 1;; \
  esac; \
  has_opt=no; \
  sane_makeflags=$$MAKEFLAGS; \
  if $(am__is_gnu_make); then \
    sane_makeflags=$$MFLAGS; \
  else \
    case $$MAKEFLAGS in \
      *\\[\ \	]*) \
        bs=\\; \
        sane_makeflags=`printf '%s\n' "$$MAKEFLAGS" \
          | sed "s/$$bs$$bs[$$bs $$bs	]*//g"`;; \
    esac; \
  fi; \
  skip_next=no; \
  strip_trailopt () \
  { \
    flg=`printf '%s\n' "$$flg" | sed "s/$$1.*$$//"`; \
  }; \
  for flg in $$sane_makeflags; do \
    test $$skip_next = yes && { skip_next=no; continue; }; \
    case $$flg in \
      *=*|--*) continue;; \
        -*I) strip_trailopt 'I'; skip_next=yes;; \
      -*I?*) strip_trailopt 'I';; \
        -*O) strip_trailopt 'O'; skip_next=yes;; \
      -*O?*) strip_trailopt 'O';; \
        -*l) strip_trailopt 'l'; skip_next=yes;; \
      -*l?*) strip_trailopt 'l';; \
      -[dEDm]) skip_next=yes;; \
      -[JT]) skip_next=yes;; \
    esac; \
    case $$flg in \
      *$$target_option*) has_opt=yes; break;; \
    esac; \
  done; \
  test $$has_opt = yes
am__make_dryrun = (target_option=n; $(am__make_running_with_option))
am__make_keepgoing = (target_option=k; $(am__make_running_with_option))
pkgdatadir = $(datadir)/xfig
pkgincludedir = $(includedir)/xfig
pkglibdir = $(libdir)/xfig
pkglibexecdir = $(libexecdir)/xfig
am__cd = CDPATH="$${ZSH_VERSION+.}$(PATH_SEPARATOR)" && cd
install_sh_DATA = $(install_sh) -c -m 644
install_sh_PROGRAM = $(install_sh) -c
install_sh_SCRIPT = $(install_sh) -c
INSTALL_HEADER = $(INSTALL_DATA)
transform = $(program_transform_name)
NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
subdir = doc
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/m4/ax_check_link_flag.m4 \
	$(top_srcdir)/version.m4 $(top_srcdir)/configure.ac
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
DIST_COMMON = $(srcdir)/Makefile.am $(dist_doc_DATA) \
	$(am__DIST_COMMON)
mkinstalldirs = $(install_sh) -d
CONFIG_HEADER = $(top_builddir)/config.h
CONFIG_CLEAN_FILES = xfig.man xfig_man.html
CONFIG_CLEAN_VPATH_FILES =
AM_V_P = $(am__v_P_$(V))
am__v_P_ = $(am__v_P_$(AM_DEFAULT_VERBOSITY))
am__v_P_0 = false
am__v_P_1 = :
AM_V_GEN = $(am__v_GEN_$(V))
am__v_GEN_ = $(am__v_GEN_$(AM_DEFAULT_VERBOSITY))
am__v_GEN_0 = @echo "  GEN     " $@;
am__v_GEN_1 = 
AM_V_at = $(am__v_at_$(V))
am__v_at_ = $(am__v_at_$(AM_DEFAULT_VERBOSITY))
am__v_at_0 = @
am__v_at_1 = 
SOURCES =
DIST_SOURCES =
am__can_run_installinfo = \
  case $$AM_UPDATE_INFO_DIR in \
    n|no|NO) false;; \
    *) (install-info --version) >/dev/null 2>&1;; \
  esac
am__vpath_adj_setup = srcdirstrip=`echo "$(srcdir)" | sed 's|.|.|g'`;
am__vpath_adj = case $$p in \
    $(srcdir)/*) f=`echo "$$p" | sed "s|^$$srcdirstrip/||"`;; \
    *) f=$$p;; \
  esac;
am__strip_dir = f=`echo $$p | sed -e 's|^.*/||'`;
am__install_max = 40
am__nobase_strip_setup = \
  srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*|]/\\\\&/g'`
am__nobase_strip = \
  for p in $$list; do echo "$$p"; done | sed -e "s|$$srcdirstrip/||"
am__nobase_list = $(am__nobase_strip_setup); \
  for p in $$list; do echo "$$p $$p"; done | \
  sed "s| $$srcdirstrip/| |;"' / .*\//!s/ .*/ ./; s,\( .*\)/[^/]*$$,\1,' | \
  $(AWK) 'BEGIN { files["."] = "" } { files[$$2] = files[$$2] " " $$1; \
    if (++n[$$2] == $(am__install_max)) \
      { print $$2, files[$$2]; n[$$2] = 0; files[$$2] = "" } } \
    END { for (dir in files) print dir, files[dir] }'
am__base_list = \
  sed '$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;s/\n/ /g' | \
  sed '$$!N;$$!N;$$!N;$$!N;s/\n/ /g'
am__uninstall_files_from_dir = { \
  test -z "$$files" \
    || { test ! -d "$$dir" && test ! -f "$$dir" && test ! -r "$$dir"; } \
    || { echo " ( cd '$$dir' && rm -f" $$files ")"; \
         $(am__cd) "$$dir" && rm -f $$files; }; \
  }
man1dir = $(mandir)/man1
am__installdirs = "$(DESTDIR)$(man1dir)" "$(DESTDIR)$(docdir)" \
	"$(DESTDIR)$(docdir)"
NROFF = nroff
MANS = $(man1_MANS)
DATA = $(dist_doc_DATA) $(doc_DATA)
am__tagged_files = $(HEADERS) $(SOURCES) $(TAGS_FILES) $(LISP)
am__DIST_COMMON = $(srcdir)/Makefile.in $(srcdir)/xfig.man.in \
	$(srcdir)/xfig_man.html.in TODO
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
ACLOCAL = ${SHELL} '/xfig-3.2.8a/missing' aclocal-1.16
AMTAR = $${TAR-tar}
AM_DEFAULT_VERBOSITY = 1
APPDEFAULTDIR = /etc/X11/app-defaults
APPLICATIONSDIR = /usr/share/applications
AR = ar
AUTOCONF = ${SHELL} '/xfig-3.2.8a/missing' autoconf
AUTOHEADER = ${SHELL} '/xfig-3.2.8a/missing' autoheader
AUTOM4TE = ${SHELL} '/xfig-3.2.8a/missing' autom4te
AUTOMAKE = ${SHELL} '/xfig-3.2.8a/missing' automake-1.16
AWK = gawk
CC = gcc
CCDEPMODE = depmode=gcc3
CFLAGS = -g -O2
COMPKEYDBDIR = /usr/share/xfig
CPP = gcc -E
CPPFLAGS = 
CYGPATH_W = cygpath -w
DEFS = -DHAVE_CONFIG_H
DEPDIR = .deps
DOCDIR = /usr/share/doc/xfig
ECHO_C = 
ECHO_N = -n
ECHO_T = 
EXEEXT = .exe
FGREP = /usr/bin/grep -F
GREP = /usr/bin/grep
GSEXE = gs
HTMLDIR = /usr/share/doc/xfig
ICONDIR = /usr/share/pixmaps
INSTALL = /usr/bin/install -c
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
LDFLAGS = 
LIBOBJS = 
LIBS = -lXpm -lpng -ljpeg 
LN_S = ln -s
LTLIBOBJS = 
MAKEINFO = ${SHELL} '/xfig-3.2.8a/missing' makeinfo
MKDIR_P = /usr/bin/mkdir -p
OBJEXT = o
PACKAGE = xfig
PACKAGE_BUGREPORT = thomas.loimer@tuwien.ac.at
PACKAGE_NAME = xfig
PACKAGE_STRING = xfig 3.2.8a
PACKAGE_TARNAME = xfig
PACKAGE_URL = https://sourceforge.net/projects/mcj/
PACKAGE_VERSION = 3.2.8a
PATH_SEPARATOR = :
PKGDATADIR = /usr/share/xfig
RANLIB = ranlib
RELEASE_DATE = Mar 2021
RELEASE_YEAR = 2021
SED = /usr/bin/sed
SET_MAKE = 
SHELL = /bin/sh
STRIP = 
VERSION = 3.2.8a
XCPPFLAGS = -DXAW_INTERNATIONALIZATION
XLDFLAGS = 
XLIBS = -lXaw3d -lXt -lX11
XMKMF = 
abs_builddir = /xfig-3.2.8a/doc
abs_srcdir = /xfig-3.2.8a/doc
abs_top_builddir = /xfig-3.2.8a
abs_top_srcdir = /xfig-3.2.8a
ac_ct_AR = ar
ac_ct_CC = gcc
am__include = include
am__leading_dot = .
am__quote = 
am__tar = $${TAR-tar} chof - "$$tardir"
am__untar = $${TAR-tar} xf -
appdefaultdir = /etc/X11/app-defaults
applicationsdir = ${datarootdir}/applications
bindir = ${exec_prefix}/bin
build_alias = 
builddir = .
compkeydbdir = ${datadir}/xfig
datadir = ${datarootdir}
datarootdir = ${prefix}/share
docdir = ${datarootdir}/doc/${PACKAGE_TARNAME}
dvidir = ${docdir}
exec_prefix = ${prefix}
host_alias = 
htmldir = ${docdir}
icondir = ${datarootdir}/pixmaps
includedir = ${prefix}/include
infodir = ${datarootdir}/info
install_sh = ${SHELL} /xfig-3.2.8a/install-sh
libdir = ${exec_prefix}/lib
libexecdir = ${exec_prefix}/libexec
localedir = ${datarootdir}/locale
localstatedir = ${prefix}/var
mandir = ${datarootdir}/man
mkdir_p = $(MKDIR_P)
oldincludedir = /usr/include
pdfdir = ${docdir}
prefix = /usr
program_transform_name = s,x,x,
psdir = ${docdir}
runstatedir = ${localstatedir}/run
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
srcdir = .
sysconfdir = ${prefix}/etc
target_alias = 
top_build_prefix = ../
top_builddir = ..
top_srcdir = ..
dist_doc_DATA = FORMAT1.3 FORMAT1.4 FORMAT2.0 FORMAT2.1 FORMAT3.0 \
	FORMAT3.1 FORMAT3.2 xfig-howto.pdf

doc_DATA = xfig_man.html xfig_ref_en.pdf
man1_MANS = xfig.man
EXTRA_DIST = html MAKEPS
CLEANFILES = html/images/xfig-title.fig
MAINTAINERCLEANFILES = Makefile.in
all: all-am

.SUFFIXES:
$(srcdir)/Makefile.in:  $(srcdir)/Makefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --foreign doc/Makefile'; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --foreign doc/Makefile
Makefile: $(srcdir)/Makefile.in $(top_builddir)/config.status
	@case '$?' in \
	  *config.status*) \
	    cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh;; \
	  *) \
	    echo ' cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__maybe_remake_depfiles)'; \
	    cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__maybe_remake_depfiles);; \
	esac;

$(top_builddir)/config.status: $(top_srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh

$(top_srcdir)/configure:  $(am__configure_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(ACLOCAL_M4):  $(am__aclocal_m4_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(am__aclocal_m4_deps):
xfig.man: $(top_builddir)/config.status $(srcdir)/xfig.man.in
	cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@
xfig_man.html: $(top_builddir)/config.status $(srcdir)/xfig_man.html.in
	cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@
install-man1: $(man1_MANS)
	@$(NORMAL_INSTALL)
	@list1='$(man1_MANS)'; \
	list2=''; \
	test -n "$(man1dir)" \
	  && test -n "`echo $$list1$$list2`" \
	  || exit 0; \
	echo " $(MKDIR_P) '$(DESTDIR)$(man1dir)'"; \
	$(MKDIR_P) "$(DESTDIR)$(man1dir)" || exit 1; \
	{ for i in $$list1; do echo "$$i"; done;  \
	if test -n "$$list2"; then \
	  for i in $$list2; do echo "$$i"; done \
	    | sed -n '/\.1[a-z]*$$/p'; \
	fi; \
	} | while read p; do \
	  if test -f $$p; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; echo "$$p"; \
	done | \
	sed -e 'n;s,.*/,,;p;h;s,.*\.,,;s,^[^1][0-9a-z]*$$,1,;x' \
	      -e 's,\.[0-9a-z]*$$,,;$(transform);G;s,\n,.,' | \
	sed 'N;N;s,\n, ,g' | { \
	list=; while read file base inst; do \
	  if test "$$base" = "$$inst"; then list="$$list $$file"; else \
	    echo " $(INSTALL_DATA) '$$file' '$(DESTDIR)$(man1dir)/$$inst'"; \
	    $(INSTALL_DATA) "$$file" "$(DESTDIR)$(man1dir)/$$inst" || exit $$?; \
	  fi; \
	done; \
	for i in $$list; do echo "$$i"; done | $(am__base_list) | \
	while read files; do \
	  test -z "$$files" || { \
	    echo " $(INSTALL_DATA) $$files '$(DESTDIR)$(man1dir)'"; \
	    $(INSTALL_DATA) $$files "$(DESTDIR)$(man1dir)" || exit $$?; }; \
	done; }

uninstall-man1:
	@$(NORMAL_UNINSTALL)
	@list='$(man1_MANS)'; test -n "$(man1dir)" || exit 0; \
	files=`{ for i in $$list; do echo "$$i"; done; \
	} | sed -e 's,.*/,,;h;s,.*\.,,;s,^[^1][0-9a-z]*$$,1,;x' \
	      -e 's,\.[0-9a-z]*$$,,;$(transform);G;s,\n,.,'`; \
	dir='$(DESTDIR)$(man1dir)'; $(am__uninstall_files_from_dir)
install-dist_docDATA: $(dist_doc_DATA)
	@$(NORMAL_INSTALL)
	@list='$(dist_doc_DATA)'; test -n "$(docdir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(docdir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(docdir)" || exit 1; \
	fi; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; \
	done | $(am__base_list) | \
	while read files; do \
	  echo " $(INSTALL_DATA) $$files '$(DESTDIR)$(docdir)'"; \
	  $(INSTALL_DATA) $$files "$(DESTDIR)$(docdir)" || exit $$?; \
	done

uninstall-dist_docDATA:
	@$(NORMAL_UNINSTALL)
	@list='$(dist_doc_DATA)'; test -n "$(docdir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	dir='$(DESTDIR)$(docdir)'; $(am__uninstall_files_from_dir)
install-docDATA: $(doc_DATA)
	@$(NORMAL_INSTALL)
	@list='$(doc_DATA)'; test -n "$(docdir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(docdir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(docdir)" || exit 1; \
	fi; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; \
	done | $(am__base_list) | \
	while read files; do \
	  echo " $(INSTALL_DATA) $$files '$(DESTDIR)$(docdir)'"; \
	  $(INSTALL_DATA) $$files "$(DESTDIR)$(docdir)" || exit $$?; \
	done

uninstall-docDATA:
	@$(NORMAL_UNINSTALL)
	@list='$(doc_DATA)'; test -n "$(docdir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	dir='$(DESTDIR)$(docdir)'; $(am__uninstall_files_from_dir)
tags TAGS:

ctags CTAGS:

cscope cscopelist:


distdir: $(BUILT_SOURCES)
	$(MAKE) $(AM_MAKEFLAGS) distdir-am

distdir-am: $(DISTFILES)
	@srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	topsrcdirstrip=`echo "$(top_srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	list='$(DISTFILES)'; \
	  dist_files=`for file in $$list; do echo $$file; done | \
	  sed -e "s|^$$srcdirstrip/||;t" \
	      -e "s|^$$topsrcdirstrip/|$(top_builddir)/|;t"`; \
	case $$dist_files in \
	  */*) $(MKDIR_P) `echo "$$dist_files" | \
			   sed '/\//!d;s|^|$(distdir)/|;s,/[^/]*$$,,' | \
			   sort -u` ;; \
	esac; \
	for file in $$dist_files; do \
	  if test -f $$file || test -d $$file; then d=.; else d=$(srcdir); fi; \
	  if test -d $$d/$$file; then \
	    dir=`echo "/$$file" | sed -e 's,/[^/]*$$,,'`; \
	    if test -d "$(distdir)/$$file"; then \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    if test -d $(srcdir)/$$file && test $$d != $(srcdir); then \
	      cp -fpR $(srcdir)/$$file "$(distdir)$$dir" || exit 1; \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    cp -fpR $$d/$$file "$(distdir)$$dir" || exit 1; \
	  else \
	    test -f "$(distdir)/$$file" \
	    || cp -p $$d/$$file "$(distdir)/$$file" \
	    || exit 1; \
	  fi; \
	done
	$(MAKE) $(AM_MAKEFLAGS) \
	  top_distdir="$(top_distdir)" distdir="$(distdir)" \
	  dist-hook
check-am: all-am
check: check-am
all-am: Makefile $(MANS) $(DATA)
installdirs:
	for dir in "$(DESTDIR)$(man1dir)" "$(DESTDIR)$(docdir)" "$(DESTDIR)$(docdir)"; do \
	  test -z "$$dir" || $(MKDIR_P) "$$dir"; \
	done
install: install-am
install-exec: install-exec-am
install-data: install-data-am
uninstall: uninstall-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am

installcheck: installcheck-am
install-strip:
	if test -z '$(STRIP)'; then \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	      install; \
	else \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	    "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'" install; \
	fi
mostlyclean-generic:

clean-generic:
	-test -z "$(CLEANFILES)" || rm -f $(CLEANFILES)

distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
	-test -z "$(MAINTAINERCLEANFILES)" || rm -f $(MAINTAINERCLEANFILES)
clean: clean-am

clean-am: clean-generic mostlyclean-am

distclean: distclean-am
	-rm -f Makefile
distclean-am: clean-am distclean-generic

dvi: dvi-am

dvi-am:

html: html-am

html-am:

info: info-am

info-am:

install-data-am: install-dist_docDATA install-docDATA install-man
	@$(NORMAL_INSTALL)
	$(MAKE) $(AM_MAKEFLAGS) install-data-hook
install-dvi: install-dvi-am

install-dvi-am:

install-exec-am:

install-html: install-html-am

install-html-am:

install-info: install-info-am

install-info-am:

install-man: install-man1

install-pdf: install-pdf-am

install-pdf-am:

install-ps: install-ps-am

install-ps-am:

installcheck-am:

maintainer-clean: maintainer-clean-am
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-am

mostlyclean-am: mostlyclean-generic

pdf: pdf-am

pdf-am:

ps: ps-am

ps-am:

uninstall-am: uninstall-dist_docDATA uninstall-docDATA uninstall-local \
	uninstall-man

uninstall-man: uninstall-man1

.MAKE: install-am install-data-am install-strip

.PHONY: all all-am check check-am clean clean-generic cscopelist-am \
	ctags-am dist-hook distclean distclean-generic distdir dvi \
	dvi-am html html-am info info-am install install-am \
	install-data install-data-am install-data-hook \
	install-dist_docDATA install-docDATA install-dvi \
	install-dvi-am install-exec install-exec-am install-html \
	install-html-am install-info install-info-am install-man \
	install-man1 install-pdf install-pdf-am install-ps \
	install-ps-am install-strip installcheck installcheck-am \
	installdirs maintainer-clean maintainer-clean-generic \
	mostlyclean mostlyclean-generic pdf pdf-am ps ps-am tags-am \
	uninstall uninstall-am uninstall-dist_docDATA \
	uninstall-docDATA uninstall-local uninstall-man uninstall-man1

.PRECIOUS: Makefile


# Below, $< is not fully portable, see info autoconf "Portable Make",
# use $? instead. man is sensitive to spaces after the options.
# Probably, groff -Thtml -mman xfig.man > $@ is more portable?

# Some files are not created when running make, but are created by the
# maintainer at distribution time, when running make dist. Also, these files are
# placed into the distribution tarball, not into the source tree.
#
# However, the concept of discriminating between distribution tarball and
# source tree does not hold very well. Nowadays, sources are also retrieved
# via the publicly accessible git source tree, not only by the point releases.
#
# Therefore, for these files, provide rules to build them _in the source tree_,
# not in the build tree. Also, make sure that they are put into the distribution
# tarball. However, the rules to build them must be explicitly called by the
# user. For convenience, a target is defined that creates all of these files,
# make documentation.
#
# The reason for distributing these files, instead of providing make rules for
# all users, is that the creation of these files demands further dependencies.
# In addition, the documentation is probably not changed by users, hence the
# version information as provided by the maintainer should remain with
# the documentation.

# %-style patterns are a gnu make extension. Do not use.

# Create the logo, xfig-title.png, which is included at the top of each html
# page and which shows the version string.
$(srcdir)/html/images/xfig-title.png $(distdir)/html/images/xfig-title.png: \
		$(srcdir)/html/images/xfig-title.fig.in $(top_srcdir)/version.m4
	test -r html/images/xfig-title.fig ||				\
			$(MAKE) -C .. doc/html/images/xfig-title.fig
	fig2dev -L png -S4 html/images/xfig-title.fig "$@"

$(srcdir)/xfig_ref_en.pdf: $(srcdir)/html/images/xfig-title.png
	cd $(srcdir)/html && htmldoc -f ../xfig_ref_en.pdf	\
		--no-title --webpage --header ..c -t pdf14 --size a4	\
		contents.html $$($(FGREP) '<a href=' contents.html |	\
				$(SED) 's/.*a href="//;s/["#].*//;' |	\
				uniq | $(FGREP) -v japanese)

# copy-paste from above (sigh)
$(distdir)/xfig_ref_en.pdf: $(distdir)/html/images/xfig-title.png
	cd $(distdir)/html && htmldoc -f ../xfig_ref_en.pdf	\
		--no-title --webpage --header ..c -t pdf14 --size a4	\
		contents.html $$($(FGREP) '<a href=' contents.html |	\
				$(SED) 's/.*a href="//;s/["#].*//;' |	\
				uniq | $(FGREP) -v japanese)

# This file remains in the src tree and is updated if necessary.
$(srcdir)/xfig_man.html.in $(distdir)/xfig_man.html.in: $(srcdir)/xfig.man.in
	man -Thtml -l "$(srcdir)/xfig.man.in" >"$@"

.PHONY: documentation

documentation: $(srcdir)/html/images/xfig-title.png $(srcdir)/xfig_ref_en.pdf

dist-hook:
	chmod u+w "$(distdir)" "$(distdir)/html" "$(distdir)/html/images"
	-chmod u+w "$(distdir)/xfig_man.html.in"			\
		"$(distdir)/html/images/xfig-title.png"
	$(MAKE) $(distdir)/html/images/xfig-title.png
	$(MAKE) $(distdir)/xfig_ref_en.pdf
	$(MAKE) $(distdir)/xfig_man.html.in

install-data-hook:
	cp -Rp "$(srcdir)/html" "$(DESTDIR)$(htmldir)"		\
		&& chmod -R u+rwX "$(DESTDIR)$(htmldir)"
	cd "$(DESTDIR)$(htmldir)/html"				\
		&& rm -f ja_JP.ujis && $(LN_S) japanese ja_JP.ujis
	cd "$(DESTDIR)$(htmldir)/html/images"			\
		&& rm -f xfig-title.fig xfig-title.fig.in

uninstall-local:
	rm -rf "$(DESTDIR)$(htmldir)/html"

# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
