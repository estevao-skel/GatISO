Gatito Linux is an distro made by me, that has the only objective of being **the smallest distro while functional**, well, you may say: "wym functional", i will explain to you.
What i define an "functional" distro is: you can boot into it, it has an functional init & an functionall shell where you can write commands on it. Only that, internet, graphics, games, browsers or even editors for me are not 100% needed in an functional distro, OF COURSE if i can, they would appear in gatito linux, but the main objective is being the smallest distro while functional, as said before.

Minimal requirements:
17mb of ram (probably 20mb if you want to be comfortable but i didnt saw any problems with the minimal requirements while normal using it)
ANY cpu x86_64 (it only works on amd 64 bits, as the entire src is made in assembly 64 bits for pcs, it DOESNT work on any RISC, AARCH64 or any CELLPHONE)
2MB of storage (yes, you can install it! i DONT recommend you to install on your main pc, i recommend you to install on an vm, i tested in QEMU, any bugs found in any other vms open an issue for them and i will try to solve it! just remember the disk you have to install it, it has to be an RAW DISK, not qcow2 or the vb format, raw, .img)

Gatito Linux is a WIP! remember ANY of these things can change and somethings can be changed/erased.
Thank you for reading it! :)

YOU WANT TO KNOW A FUN FACT? BECAUSE OF SOME FCKIN LEGACY CODE IN SEABIOS THAT IS FROM IDK HOW MANY YEARS AGO I CANT TELL EXACTLY THE MINIMAL REQUIREMENTS FOR RAM BECAUSE OF 3 LINES OF CODE IN THE SEABIOS SRC, GATITO LINUX WOULD WORK WITH LIKE 13MB OF RAM, BUT THE DAMN LEGACY OF SEABIOS WONT LET IT WORK, SO BECAUSE OF A LOT OF VMS USE SEABIOS AS NORMAL, I WILL HAVE TO ADD AN EXTRA +1MB TO THE MINIMAL REQUIREMENTS BECAUSE OF A LEGACY CODE THAT WAS PROJECTED BECAUSE OF THE LIMIT OF AN MICROCPU MADE IN 1982, 44 YEARS AGO, AND STILL TO THESE DAYS THEY DONT CHANGE THE SRC, THAT IT WOULD TAKE THEM LESS THAN A HOUR AND WOULD MAKE EVERYTHING EASIER OMG
if you want to test gatito linux with less than 17mb of ram, i recommend you to change the bios, in qemu you use -bios to change, although i will NOT help any errors ocurred at any other bios. 
