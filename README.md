# 6502 ASM for CotEditor
I made a simple syntax highlighting of the 6502 assembly language for the CotEditor. I wanted to do some hacks on my Commodore64, but 6502 asm wasn't supported by my favorite code editor!

It follows the syntax of the TASS64 assembler (which is pretty standard).

## Use it
* Download `6502.yaml`
* In CotEditor visit to `CotEditor > Preference > Format`
* Click on the gear icon on the bottom and choose `import...`

## Help me
This syntax file is far from complete. It only support instruction keywords, constants, addresses, labels and comments. It is missing all assembler directives, strings, etc.
If you want to see what's missing, look at the TASS64 reference: http://tass64.sourceforge.net
