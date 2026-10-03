# Unbound-Power
A unlocking TGP tool for laptops


A short introduction:

Damn im not good in the explanation things but i give it a try.

This project was started and made by myself. Im use a pcs recoil 3 16" thats equal to a A25 from xmg or hydroc 16 G2. These laptops share cross the board the same barebone at all.
I was given the laptop to TechModLab and he installed a shunt up to 250w for the gpu.

this barebone can easly handle that wattage also for dayli usage.

after 6 months straight using this laptop i never noticed any problem with this shunt but im hitting some power clamps in some cases.

At first i thinking ok im just hitting my power limit for the gpu thats also extremly optimised in this state.

But after monts of using i was wondering what caused that clamps and at this time Mvolt was released that give us the access to Xbar.

After alot tweaking and noticed how strange the power policy on laptop could be im start to code some stuff via a custom kernel. I was able to find while debugging any limits what was be set from nvidia and was able to bypass them.

But here was the next big wall i had to overcome by getting it running into a normal windows session without changing the nvidia sys kernel at all.

It took me nearly a month to find ways to get this values changed and also i was search for some help by 1usmus. I was asking him in exchange for my code for some tipps how i could handle some strange ways but he was straight ghosting me the admins on hydra discord also >.>

So back to reality i was able to find step by step the needed paths by myself. I couldnt deeply explain how im done it correctly otherwise nvidia could fix my used paths.

Here a very short expl. how this tool in generell works:

My tool is reading at startup the ec/vbios and driver values. after choosing the wanted values it start to change values and pls dont ask about the path im using here. simply im able to give the sys commands to change things im want by himself. that allowed a full functional and useable nvidia driver by not bypassing any kind of security. this allowed some bigger options. This tool runs 100% in a normal windows session with secure boot activated and by not customise the kernel u can also play anti cheat games by not risking ur accs.

if ur restart ur laptop all option are back to normal because we didnt hardcode/write values into the kernel. that was the biggest problem for me to getting running.

this whole project is compiled into a portable exe that should get his own folder anywhere on ur laptop. after first starting it creates a gui folder where the exe still present. here are saved the ec and vbios and driver stock values also the startup protocol if something went wrong.

Now some pics of my tool.

<img width="1080" height="568" alt="image" src="https://github.com/user-attachments/assets/50bd6620-73f2-4fca-b535-0e128deb11ab" />
Mvolt + My tool + Msi Afterburner

Im just startup my tool set the limits i want went over to afterburner and apply my fav custome curve and went over to mvolt to do some thin tuning for xbar and voltage.


<img width="1080" height="522" alt="image" src="https://github.com/user-attachments/assets/a9372642-b079-4588-9849-d02973cf21ae" />

<img width="1080" height="547" alt="image" src="https://github.com/user-attachments/assets/c3aaecce-e1fd-4de5-a6eb-0ac8fb530042" />

with this tweeks im able to get These scores on a 5090 laptop

<img width="1080" height="759" alt="image" src="https://github.com/user-attachments/assets/ff0672e1-7da2-490c-a0b5-e1f4db037c07" />
<img width="1080" height="701" alt="image" src="https://github.com/user-attachments/assets/3db9c908-2a0f-4bd4-b0c3-3f9d103b2a2a" />
<img width="1080" height="690" alt="image" src="https://github.com/user-attachments/assets/a3a98b2e-7ec0-404f-8a16-a83fefbbdb8f" />







Im just startup my tool set the limits i want went over to afterburner and apply my fav custome curve and went over to mvolt to do some thin tuning for xbar and voltage.


A quick greetings to prema at this point. we try to get any possible power out of this laptop gpus but i get this place back soon hehe

At the end im trying consistently to create more and more compatibility for dif laptops / gpus / vbios / ec versions. at least the 4000gen should also be supportet but again this tool is mostly for exp user that known the hardware limits in particular they vrms and heat limits.

sooooo here is the good thing:
https://mega.nz/folder/PDxAUCTD#VXxBml-B-ITZhN9NboLkMA

(had to change to mega caused by drive strikes xD)

At least: dont try to burn ur laptops :D and if ur wanna follow the active development u could join the xmg discord into the A25 channel. Also if u have a 4000gen feel free to contact me


LATEST UPDATE:
17:56 utc+2
03.10.26

