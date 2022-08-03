# Hardware

## What would be the apropriate hardware for my home server?

I have a Respberry 3, but is seams that it would not be able to host docker containers because of RAM limitations.
Raspberry is already in use with Pi Hole. Blocking some dns request. Since availability of Pi Hole must be high, I decided 
to deploy it to a dedicated hardware. 

Having docker running on the server requires CPU and RAM. 
I made some research on CPU. Especially Intel has a lot of models in low level segment.
At the current state an Intel Atom N6005 would be a good choice having CPU/"Power consumption" ratio in mind. Its TDP is around 10W.

## Now lets take price into the equation!

There is practicaly no market for dedicated efficient home servers. 

What is about **refurbished hardware**? The market is full of workstations with 4rd generation of Intel core i5 CPUs. Looking at the TDP (> 75 W)
I'have skipped the idea of having older hardware.

What is about **NAS servers**. I have a qnap [TS-231](https://www.qnap.com/de-de/product/ts-231). It supports docker! 
![image](https://user-images.githubusercontent.com/7858781/182562336-a9d08aff-b003-4d0c-8e30-ccf04fa67dbf.png)


But:

* the CPU is an RAM is most probably not sufficient
* The most valueable I have in the network is my data. I've decided to avoid any experiments in my NAS in order to avoid unintentional data exposure.

All **new compact workstations** with latest Intel Atom N6XXX have a worser value/price ration in comparision with the 4rd generation of Intel Atom L4XXX.
There I can get a workstation with 8G RAM for 150€. Filtering to 16G RAM reduces the number of deals significant. I'm no sure if an Atom L4xxx would be
sufiicient, but 8G of RAM most probably can become a bottleneck. 

## My choice

Now I'm ready for Amazon's Prime day!

Finally my choice was: "CHUWI CoreBox Mini PC, Windows 10 Mini Desktop Computer mit Core i5-8259U 16GB DDR4 RAM 512GB SSD ROM"
The price was 350€, what is x2 more than I was looking for, but:

* Intel Core i5 8th generation delivers double the performance of a L4XXX 
* and a 512GM SSD is x4 than my reference workstation was
* 16G RAM is x2 and would be sufficient for future needs
* TDP 25W is OK
* Price 350€ is 100€ below the next offer in that segment
* the user perception is around 4,5 stars, but the most of bad reviews are about the noise under high load. I don't care about noise in my IT rack in basement.

https://www.amazon.de/gp/product/B09PQW9PYW/ref=ppx_yo_dt_b_asin_title_o01_s00?ie=UTF8&psc=1

![image](https://user-images.githubusercontent.com/7858781/182542072-9b051154-c849-4790-90d6-ec6608f24476.png)

