# piids
the hard to find NIDS on Raspberry preinstalled disk image

# Anything here come without any warranty. I'm not responsible for any damage.
;)

What on earth is this weird repo?
================================= 

This repo contain [only link](https://telegram.me/halamanbelakang/210) (because of github limitation) to dirty-built diskimage of raspbian running as NIDS,
I use raspberry pi as SoHo NIDS and very excited to share it since I'm troubled at first place while searching people who already build one. XD 

I use [this guide](https://www.snort.org/documents/snort-2-9-8-x-on-ubuntu-12-lts-and-14-lts-and-15) to set up snort, barnyard2, and snorby on Raspbian (lite)

How to use this image?
======================

you can use dd to write this image to sdcard

boot it (you can resize partition using raspi-config to fill up your sdcard)

configure it according to your network setup

now you have running NIDS without hassle 

Blablablabla
============
In case you want to know :

hostname: piids

credential :

pi::sdiip

mysql user&root::sdiip

to open snorby web interface just poin your Raspberry IP addreas in your browser and use this account and pass : snorby@snorby.org::snorby
