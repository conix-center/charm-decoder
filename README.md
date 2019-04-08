# charm-decoder
Charm coherent combining decoder for LoRa packets.

This is for the sake of collecting source code created in CONIX to a single location. 
Code repository at https://github.com/WiseLabCMU/charm-decoder

# Publication 

This work is documented by SRC publication [P093121](https://www.src.org/library/publication/p093121/p093121.pdf#search=charm). 

```
Adwait Dongare, Revathy Narayanan, Akshay Gadre, Anh Luong, Artur Balanuta, Swarun Kumar, Bob Iannucci, and Anthony Rowe. 2018. 
Charm: exploiting geographical diversity through coherent combining in low-power wide-area networks. 
In Proceedings of the 17th ACM/IEEE International Conference on Information Processing in Sensor Networks (IPSN '18). 
IEEE Press, Piscataway, NJ, USA, 60-71. DOI: https://doi.org/10.1109/IPSN.2018.00013
```

## Abstract

> Low-Power Wide Area Networks (LPWANs) are an emerging wireless platform which can support battery-powered devices lasting
10-years while communicating at low data-rates to gateways several
kilometers away. Not all such devices will experience the promised
10 year battery life despite the high density of LPWAN gateways
expected in cities. Transmission from devices located deep within
buildings or in remote neighborhoods will suffer severe attenuation
forcing the use of slow data-rates to reach even the closest gateway,
thus resulting in battery drain.
This paper presents Charm, a system that enhances both the
battery life of client devices and the coverage of LPWANs in large
urban deployments. Charm allows multiple LoRaWAN gateways
to pool their received signals in the cloud, coherently combining
them to detect weak signals that are not decodable at any individual
gateway. Through a novel hardware and software design at the
gateway, Charm carefully detects which chunks of the received
signal need to be sent to the cloud, thereby saving uplink bandwidth.
We present a scalable solution to decoding weak transmissions at
city-scale by identifying the set of gateways whose signals need
to be coherently combined over time. In evaluations over a test
network and from simulations using traces from a large LoRaWAN
deployment in Pittsburgh, Pennsylvania, Charm demonstrates a
gain of up to 3× in range and 4×in client battery-life.
