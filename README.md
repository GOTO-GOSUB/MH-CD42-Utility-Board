# MH-CD42-Utility-Board
A utility board for MH-CD42 LiPo boost &amp; charge modules

![PCB examples](https://github.com/GOTO-GOSUB/MH-CD42-Utility-Board/blob/21966ed0e30118d6ea344de2cdef770c52e23b9a/Images/MH-CD42%20Utility%20Board.jpg)

Very much a work in progress, this PCB acts as a utility board for MH-CD42.
It came about because a lot of these modules are cheap for a reason - they don't always work.
Put female headers or sprung test points ("pogo pins") in instead of soldering the module to the board to allow for rapid testing.

This board includes an optional voltage divider to provide a Raspberry Pi safe output voltage to trigger a GPI event (eg a low power shut-down). The silk screen provides the resistor values but I will provide a parts list shortly.

This little carrier board also has breakouts for 0V and 5V outputs should they be required.

Please do not consider this complete, I am still making changes to facilitate easy assembly and availabilty of parts. It is also worth pointing out that the output of MH-CD42 modules tend to "sag" if the +5V supply is removed. The voltage drop before the battery regulation kicks in properly may not be an issue to you but it will most likely lock up an SBC (such as a Raspberry Pi) which is undesirable. All MH-CD42's do this, perhaps future versions of this board will include a massive capacitor across the output to help reduce this.

**This has been really helpful ! Please take my money !**

That is very kind of you, but please pay it forward. If anything here has made your day a little bit better please consider making a small donation to MIND or Macmillan Cancer Support.

https://www.mind.org.uk/donate/

https://www.macmillan.org.uk/donate
