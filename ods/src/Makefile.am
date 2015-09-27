lib_LTLIBRARIES =

# If xxx_CFLAGS is not specified, AM_CFLAGS will be used.
AM_CFLAGS = -I$(srcdir)/../include/

libods_la_SOURCES = ods_idx.c ods.c rbt.c ods_idx_priv.h ods_priv.h oidx_priv.h
libods_la_LIBADD = -ldl -lpthread
lib_LTLIBRARIES += libods.la

libidx_BXTREE_la_SOURCES = bxt.c bxt.h
libidx_BXTREE_la_LIBADD = libods.la
lib_LTLIBRARIES += libidx_BXTREE.la

libkey_BLKMAP_la_SOURCES = key_blkmap.c
lib_LTLIBRARIES += libkey_BLKMAP.la

libkey_SHA256_la_SOURCES = key_sha256.c
lib_LTLIBRARIES += libkey_SHA256.la

libkey_STRING_la_SOURCES = key_str.c
lib_LTLIBRARIES += libkey_STRING.la

libkey_UINT96_la_SOURCES = key_uint96.c
lib_LTLIBRARIES += libkey_UINT96.la

libkey_UINT64_la_SOURCES = key_uint64.c
lib_LTLIBRARIES += libkey_UINT64.la

libkey_UINT32_la_SOURCES = key_uint32.c
lib_LTLIBRARIES += libkey_UINT32.la

libkey_DOUBLE_la_SOURCES = key_double.c
lib_LTLIBRARIES += libkey_DOUBLE.la