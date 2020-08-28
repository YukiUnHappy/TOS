# TOS
Frankenstein

## elf-dump-fix
>  This resp include two utils about dumping and fixing arm elf32/elf64 from the memory.
>
>  - dump  
>    - Run on android, can dump ELF from a process memory and fix it, Rebuild the Section Header for better IDA analysis.
>  - sofix
>    - Run on PC, can fix an ELF file dumped from memory and rebuild the Section Header for better IDA analysis.
>
>  The main target is to rebuild the Section Header of an ELF by memory dumped.Useful in breaking packed so file like UPX or something like 360 libjiagu.so

## MemDumper
> Dump Memory Segment From Process Memory and Rebuild So(Elf) Libraries

## Credits
- [elf-dump-fix](https://github.com/maiyao1988/elf-dump-fix) (maiyao1988)
- [MemDumper](https://github.com/kp7742/MemDumper) (kp7742)
