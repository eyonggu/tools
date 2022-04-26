# tools

- pagemap

  print process's physical pages for a given virtual address range.

  Usage:  pagemap <pid> <start va> <end va>

- pcimem

  mmap and read/write to pci device memory (BAR resource).

  Usage:  pcimem [r|w] <bb:dd:ff> <bar> <offset> <width> [<data>]
