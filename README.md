PTRWriter
=========

Creates PTR records from your main record file

Yet another bind A -> PTR converter. As with this type of thing, your mileage may vary. 
This assumes you've actually tab delimited your record lines, and that you're generating records for /24s.

Usage: $0 [bind file] [suffix]

outputs xxx.xxx.xxx.in-addr.$suffix
