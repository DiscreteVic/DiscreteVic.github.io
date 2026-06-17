# Duo Module 01
<link rel="stylesheet" type="text/css" href="/css/style.css">

This story started when I began looking for the simplest and smallest Linux platform based on RISC-V with the lowest possible power consumption.

Naturally, I started by exploring Chinese platforms. I found several SoCs, but they came with plenty of issues: missing documentation, very expensive development boards, and many other limitations. Having already accumulated a lot of unused and useless development boards, I learned to be more careful about the development ecosystem. It sounds obvious, but the development board market (especially the Chinese one) is flooded with fancy boards packed with peripherals. However, when you try to modify low-level components (the boot chain, JTAG debugging, and so on), you discover that they are completely locked down, with cut traces, missing documentation, and other obstacles. In the end, they turn into little more than bricks on which you can only boot a prebuilt Linux image from an SD card.
