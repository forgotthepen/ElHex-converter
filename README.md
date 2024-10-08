# ElHex-converter
ARM32 executable .Elf to Intel .HEX converter

## How to build
`g++ arm-elf-to-hex-converter.cpp -o elhex-converter.exe`

## How to use
`elhex-converter.exe "path\to\input elf file" "path\to\output hex file"`

## References
### ELF file format
[ELF and ABI Standards: Tool Interface Standard (TIS) Portable Formats Specification, version 1.2](https://refspecs.linuxfoundation.org/elf/elf.pdf)

[ARM ELF File Format](http://infocenter.arm.com/help/topic/com.arm.doc.dui0101a/DUI0101A_Elf.pdf)

[Wikipedia: Executable_and_Linkable_Format](https://en.wikipedia.org/wiki/Executable_and_Linkable_Format)

### Intel HEX format
[GENERAL: INTEL HEX FILE FORMAT](http://www.keil.com/support/docs/1584/)

