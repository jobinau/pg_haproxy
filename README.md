# pg_haproxy : haproxy configurations for postgresql

## DESCRIPTION
These are haproxy configuraiton files which someone should be able to copy as /etc/haproxy/haproxy.cnf after editing server and credentail details. files are to indicate the use cases of each of them. rename them as haproxy.cnf so that haproxy will consider them.

# haproxy_pg_protocol_tcp.cfg
This file impliments PostgreSQL network Potocol V3. Idea is derived from repo : https://github.com/gplv2/haproxy-postgresql. Full credit to this project by Glenn Plas.
You may use online string to hex converter like : https://codebeautify.org/string-hex-converter for changing the credentails to hex. it requires "00" at the end of many of the hex string to mark the end of string.
