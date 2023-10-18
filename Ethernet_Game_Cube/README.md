# Ethernet GAME CUBE
<link rel="stylesheet" type="text/css" href="/css/style.css">

Progress about the development of a new custom broadband adapter to the Game Cube(GC).

- Front picture of the GAME CUBE with the BBA 
![GC bba front](/assets/gcbbafront.png)

- Pictures of the BBA (JAP. version)
![official bba front](/assets/officialbbafront.png)

![official bba back](/assets/officialbbaback.png)

- Down picture of the GAME CUBE withour the serial port 1 cover
![serial port 1](/assets/sp1port.png)



## Day 1: [17/10/2023]

### Researching

- The first step is to look for any kind of documentation and information about the Serial Port 1 and the broadband adapter (BBA).

As cover page the [GCForever Wiki](https://www.gc-forever.com/wiki/) gives a few, but important, information about the BBA, as the PCB pictures with the reference of the two ICs (MX98730EC  and  TDK TLA-6T118). Later, after some help (by Extrems user at webhdx discord) I have found a datasheet of a similar IC to the MX98730EC. That IC works as a converter from a (kind of) SPI to Ethernet.

## Day 2: [18/10/2023]

### Researching

With the [datasheet](https://stuff.mit.edu/afs/sipb/contrib/doc/specs/ic/network/mx98726.pdfhttps://stuff.mit.edu/afs/sipb/contrib/doc/specs/ic/network/mx98726.pdf) of the IC found yesterday, some aspects about the serial protocol used by the GC can be clarified. However, it can't be consider as the main document about the BBA. Probably it will help having some trace extracted directly from the GC.
