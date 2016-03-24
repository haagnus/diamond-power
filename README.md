Sega Genesis, Kid Chameleon 24-03-2016

with this mod you can give each character a own unique amount of diamond requirement

INSTALL
change on address 0x03F666, 4EF86FB4 (which will make it jumps to the new piece of code)
then on address 0x6FB4, you place all the bytes from the file diamond (0x1BE number of bytes)


FC46
00 the kid
01 skycutter
02 cyclone
03 red stealth
04 eyeclops
05 juggernaut
06 iron knight
07 berzerker
08 manaixe
09 micromax


how it select the pointer for each different character and diamond power. it jump a number of byes from address 0x03F6CE
for the first diamond power it takes the helmet value and multiply it two times which is the number of bytes
for the second diamond power is goes party the same only there is added 0xA before the calculation
