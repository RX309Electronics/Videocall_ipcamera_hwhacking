## DISCLAIMER: 
The creator: RX309Electronics, the uploader and maintainer of this subreddit is not responsible for any damage or harm caused to/by the product. If you brick or damage your device dont ask me about a refund or to pay for the damages. I uploaded this because i was interested in the product and my main target was hacking the device and if you also want to dive deeper into this feel free to follow my instructions. But be warned because i am just a hobbyist tinkerer and not a profesional in this sector. This is just for fun and learning things in the process. 
If you are the manufacturer or a lawyer of the manufacturer of this product and wish for this repository to be removed, feel free to email me at 309Electronics_customersupport@gmail.com and i will happily cooperate because i dont like breaking laws/patents or getting in trouble. If you mail me respectfully i will coperate as soon as possible.

## NOTICE & LICENSE
Please note that this product uses software/components licensed under the GNU GPL license. Primarily:
1. Linux, version: 4.9.37. Linux is a free opensource Unix-like kernel developed by Linus Torvald which is designed to support a large amount of hardware and is designed to be POSIX compatible and function about te same as UNIX. It powers many devices and a large part of the internet.
2. Uboot (Das UBOOT in full). Uboot is a free and opensource Bootloader that is designed to be used in embedded devices and supports a lot of hardware.
3. Busybox. Busybox is a package thats basically a swiss army knife of different Unix and *NIX utilities and tools/commands. Its the basis userland of many embedded Linux devices and provides standard UNIX(-like) functions and commands.

## STORY
So i was scroling arround aliexpress and after some scrolling arround i found a quite interesting product: https://nl.aliexpress.com/item/1005008096157627.html?spm=a2g0o.productlist.main.1.22dcn9vzn9vzoe&algo_pvid=eff6c6e7-bbd0-49f5-92e5-ca2a9615dbd0&algo_exp_id=eff6c6e7-bbd0-49f5-92e5-ca2a9615dbd0-0&pdp_ext_f=%7B%22order%22%3A%2276%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21EUR%2151.95%2117.19%21%21%21399.00%21132.03%21%402103956b17428357484891106e5c3d%2112000043707738078%21sea%21NL%210%21ABX&curPageLogUid=YuDSl05XZukt&utparam-url=scene%3Asearch%7Cquery_from%3A. This seems to be a ip camera which can be controlled by an app. One feature stands out though, and that is that this actually has a screen on it while previous camera's i took a look at and hacked did not have a screen. Now i am curious to see what software and hardware is used for it to be able to output graphics. It could have some device node in /dev for the screen and or some custom drivers/kernel modules so this could be interesting so i bought it. After a few days of waiting it arrived and this is the product itself:
![IMG20241207145552](https://github.com/user-attachments/assets/f4c826eb-b537-44ae-9c53-06d55671d8cf) 
![IMG20241207145545](https://github.com/user-attachments/assets/88233d62-d0c9-409a-8efc-539c1fa33dba) 
![IMG20241207145549](https://github.com/user-attachments/assets/0afc4b3e-8bf8-4da4-bc9b-35f6d8063038) 

## Opening it up 
![IMG20241207145600](https://github.com/user-attachments/assets/3fb8aa26-ebd5-4865-85c3-756bd1ff7bec) 
To open it you first have to remove this screw which connects the shaft of the stepper motor for left and right to the base and the device. Like shown above. 


![IMG20241207145620](https://github.com/user-attachments/assets/0fec1280-3088-403e-a756-800e7d909130) 
After that's undone you find 2 screws you also have to undo. After undoing those, its just some clips holding everything together.

After that, its open!

## Exploring the insides
![IMG20241207145726](https://github.com/user-attachments/assets/922c42ec-83d9-4657-b949-b52952c62a6c) 

![IMG20241207145742](https://github.com/user-attachments/assets/1f923392-02ef-4b4b-ba70-f672d2225901) 
![IMG20241207145947](https://github.com/user-attachments/assets/2ce28c12-39ab-4d6c-817b-9347458ac302) 

![IMG20241207150015](https://github.com/user-attachments/assets/93536d5e-f6c9-4687-9b63-623c91e9c4fd) 

![IMG20241207150123](https://github.com/user-attachments/assets/ffc84c08-21dc-4077-b8da-5c65d1b95b12) 

![IMG20241207150126](https://github.com/user-attachments/assets/cdebdcce-32da-4a96-b363-3f029e385e97) 

