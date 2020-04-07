### Feature Description

This utility is to execute commands on a remote host and get the result back.

The problem scenario could arise when you have to run automated tests/certain commands from your jenkins pipeline and the test/environment setup cannot be created on fly.
We can login to a specified virtual machine using this utility and execute our commands there.

The utility uses `JSch` library to achieve this.
