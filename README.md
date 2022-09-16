# asm_notes
asm x86-64
This is mostly notes from books that I've read regarding ASM (actually MASM) the first book I'm currently reading is called Assembly step-by-step by Jeff Dunteman. You can read it for free on archive.org
Programs used are EMU8086 (x86 cpu emulator), godbolt.org (gcc, gnu compiler on the web) and dosbox for emulating windows debugger

########################################## NOTES START HERE ##################################################
Some definitions:
Byte              BYTE              1              01H
Word              WORD              2              02H
Double word       DWORD             4              04H
Quad word         QWORD             8              08H
Ten byte          TBYTE             10             0AH
Paragraph         PARA              16             10H
Page              PAGE              256            
Segment           SEGMENT           64k (65,536)   10000H  -> Segment is the byte amount that the CPU can read in a full megabyte of memory (1m bytes)
