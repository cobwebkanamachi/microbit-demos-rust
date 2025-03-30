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

https://github.com/user-attachments/assets/49e9a070-156d-4d1b-b5b6-93b7438d4e8c
https://github.com/user-attachments/assets/dd40a7dc-dc96-48bf-be47-8dc90f26bf13

Enjoy!
</PRE>
