# microbit-demos-rust
<PRE>
clone of https://github.com/dtcristo/microbit-demosf, esp. did build &amp; deployed snake game really.

Bellow are on bash of WSL2.
1) git clone https://github.com/dtcristo/microbit-demos.git --recursive
2) cd microbit-demos
3) rustup target add thumbv6m-none-eabi
4) file bin/flash
5) more bin/flash
6) bin/flash snake
7) file target/thumbv6m-none-eabi/release/snake 
8) cp target/thumbv6m-none-eabi/release/snake /mnt/c/users/user/desktop
9) on windows command prompt: ren snake snake.bin
NOTICE: dap drive = if you connect micro:bit with pc via usb cable, then reveal drive of micro:bit.
10) drop snake.bin into  dap drive.
</PRE>
<IMG src="https://github.com/cobwebkanamachi/microbit-demos-rust/blob/main/IMG_4090.gif">
<IMG src="https://github.com/cobwebkanamachi/microbit-demos-rust/blob/main/IMG_4091.gif">

<BR>
Enjoy!
