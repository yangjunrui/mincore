mincore
=======

just a wrapper of the `mincore' syscall

How To
=======

<code>
  $ make
  -h
  --help
    print this message.
  -p
  --path
    path to file or directory you want to inspect.
  -t
  --touch
    whether to touch pages of the file, in order to load them into memory.
  $ ./mincore -h
  $ ./mincore -p <file or directory> \[-t\]
</code>
