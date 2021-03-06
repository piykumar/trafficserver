#  Licensed to the Apache Software Foundation (ASF) under one
#  or more contributor license agreements.  See the NOTICE file
#  distributed with this work for additional information
#  regarding copyright ownership.  The ASF licenses this file
#  to you under the Apache License, Version 2.0 (the
#  "License"); you may not use this file except in compliance
#  with the License.  You may obtain a copy of the License at
#
#      http://www.apache.org/licenses/LICENSE-2.0
#
#  Unless required by applicable law or agreed to in writing, software
#  distributed under the License is distributed on an "AS IS" BASIS,
#  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
#  See the License for the specific language governing permissions and
#  limitations under the License.

include $(top_srcdir)/build/plugins.mk

AM_LDFLAGS = $(TS_PLUGIN_LDFLAGS)

noinst_LTLIBRARIES = \
  add-header.la \
  append-transform.la \
  basic-auth.la \
  blacklist-0.la \
  blacklist-1.la \
  bnull-transform.la \
  cache-scan.la \
  file-1.la \
  hello.la \
  lifecycle-plugin.la \
  null-transform.la \
  output-header.la \
  protocol.la \
  psi.la \
  query-remap.la \
  remap.la \
  replace-header.la \
  response-header-1.la \
  server-transform.la \
  thread-1.la

add_header_la_SOURCES = add-header/add-header.c
append_transform_la_SOURCES = append-transform/append-transform.c
basic_auth_la_SOURCES = basic-auth/basic-auth.c
blacklist_0_la_SOURCES = blacklist-0/blacklist-0.c
blacklist_1_la_SOURCES = blacklist-1/blacklist-1.c
bnull_transform_la_SOURCES = bnull-transform/bnull-transform.c
cache_scan_la_SOURCES = cache-scan/cache-scan.cc
file_1_la_SOURCES = file-1/file-1.c
hello_la_SOURCES = hello/hello.c
lifecycle_plugin_la_SOURCES = lifecycle-plugin/lifecycle-plugin.c
null_transform_la_SOURCES = null-transform/null-transform.c
output_header_la_SOURCES = output-header/output-header.c
protocol_la_SOURCES = protocol/Protocol.c protocol/TxnSM.c
query_remap_la_SOURCES = query-remap/query-remap.c
remap_la_SOURCES = remap/remap.cc
replace_header_la_SOURCES = replace-header/replace-header.c
response_header_1_la_SOURCES = response-header-1/response-header-1.c
server_transform_la_SOURCES = server-transform/server-transform.c
thread_1_la_SOURCES = thread-1/thread-1.c
psi_la_SOURCES = thread-pool/psi.c thread-pool/thread.c

# The following examples do not build:
#
# prefetch_eg1_la_SOURCES = prefetch/prefetch-plugin-eg1.c
# redirect_1_la_SOURCES = redirect-1/redirect-1.c
# session_1_la_SOURCES = session-1/session-1.c
