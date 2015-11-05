# bkeeper
bkeeper is a set of command line shell scripts to manage and ease creation of bhyve guests.

## Usage:

bin/add-new-hyve [-s disk_size:mem_size:cpu_size:link] [-c iso_name] [-o vm_os] [-a] vm_name

## Examples:

### Add a new hyve

bin/add-new-hyve -s 16G:256M:1:tap0 -c install58.iso -o openbsd58 -a openbsd58

