
More options

Skip to content

code Search Results · repo:git/git language:C

Filter:

More than 100 filesingit/git(press backspace or delete to remove)

ws.c

/* * Whitespace rules * * Copyright (c) 2007 Junio C Hamano */#define DISABLE_SIGN_COMPARE_WARNINGS

ws.h

#ifndef WS_H#define WS_Hstruct index_state;struct strbuf;/*

tar.h

#ifndef TAR_H#define TAR_H#define TYPEFLAG_AUTO		'\0'#define TYPEFLAG_REG		'0'#define TYPEFLAG_LNK		'2'#define TYPEFLAG_DIR		'5'

odb.c

#include "git-compat-util.h"#include "abspath.h"#include "commit-graph.h"#include "config.h"#include "dir.h"#include "environment.h"#include "gettext.h"

url.c

#include "git-compat-util.h"#include "hex-ll.h"#include "strbuf.h"#include "url.h"int is_rfc3986_unreserved(char ch){

tag.h

#ifndef TAG_H#define TAG_H#include "object.h"extern const char *tag_type;

hash.h

#ifndef HASH_H#define HASH_H#if defined(SHA1_APPLE)#define SHA1_BACKEND "SHA1_APPLE (No collision detection)"#include <CommonCrypto/CommonDigest.h>#elif defined(SHA1_OPENSSL)

blob.h

#ifndef BLOB_H#define BLOB_H#include "object.h"extern const char *blob_type;

fsck.h

#ifndef GIT_FSCK_H#define GIT_FSCK_H#include "object.h"#include "oidset.h"enum fsck_msg_type {

copy.c

#include "git-compat-util.h"#include "copy.h"#include "path.h"#include "gettext.h"#include "strbuf.h"#include "abspath.h"

utf8.h

#ifndef GIT_UTF8_H#define GIT_UTF8_Hstruct strbuf;

