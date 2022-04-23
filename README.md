# HTUB
 HTUB (HTangl USBC Breakout) - A USBC breakout for DIY rectangle controllers
![](https://raw.githubusercontent.com/HTangl/HTUB/main/Pictures/Model%202.png)  

The HTUB is a USBC breakout board designed for DIY rectangle controllers to facilitate the use of both USBC to GC and USBC to USBA cables using a single port.    

It is based on the design of the [Model U](https://github.com/Crane1195/Model-U/tree/main) made by [Crane](https://github.com/Crane1195) but differs in several ways.  

I added a MBR120 diode to the board along with a dedicated VSYS pin so you do not need to wire in a diode if you are using a Raspberry Pi Pico as your microcontroller. Simply wire the VSYS pin on the HTUB directly to the VSYS pin on the Pico.  

I've also removed the TX- and RX- pins as they are generally not used for most DIY rectangles.  

The mounting holes are for M3 screws and are 3.2mm in diameter.  

If you're not sure how to order these I wrote a [guide](https://github.com/HTangl/Model-U) that explains how to get these fabricated by JLCPCB. The proccess is essentially the same for both the Model U and the HTUB with the one exception being you **MUST USE 0.8mm BOARD THICKNESS**. If you order these with the standard 1.6 board thickness JLC will not be able to manufacture them.  

![](https://raw.githubusercontent.com/HTangl/HTUB/main/Pictures/Panel%208.png)
