# RLUB
![image](https://user-images.githubusercontent.com/95242582/197305499-870d1005-d29e-4e7c-a228-bf41a5252177.png)

The RLUB is a USBC breakout board designed for DIY rectangle controllers to facilitate the use of both USBC to GC and USBC to USBA cables using a single port.    

It is a derivation of the [HTUB](https://github.com/HTangl/HTUB) design made by [Hadoe](https://github.com/HTangl/) which in turn is based on the design of the [Model U](https://github.com/Crane1195/Model-U/tree/main) made by [Crane](https://github.com/Crane1195). 

Compared to the original Model U, an MBR120 diode has been added to this board along with a dedicated VSYS pin so you do not need to wire in a diode if you are using a Raspberry Pi Pico as your microcontroller. Simply wire the VSYS pin on the RLUB directly to the VSYS pin on the Pico.  

The TX- and RX- pins have also been removed as they are generally not used for most DIY rectangles.  

The mounting holes are for M3 screws and are 3.2mm in diameter.  

The RLUB modifies the HTUB design by putting all the pins in a single row which enables a low-profile connection to a mainboard with right-angle dupont connectors.

![image](https://user-images.githubusercontent.com/95242582/197305344-89d29a79-eecf-42f5-b4ce-57b517009d39.png)


If you're not sure how to order these, Hadoe wrote a [guide](https://github.com/HTangl/Model-U) that explains how to get these fabricated by JLCPCB. The proccess is essentially the same for both the Model U and the RLUB with the one exception being you **MUST USE 0.8mm BOARD THICKNESS**. If you order these with the standard 1.6 board thickness JLC will not be able to manufacture them.  


![image](https://user-images.githubusercontent.com/95242582/197304992-0854b75f-0698-448e-8b3d-817bd7dc62ad.png)

![image](https://user-images.githubusercontent.com/95242582/197304977-9b35634a-77ec-46a5-99ac-824032f6fe27.png)

Other notes:

These files were panelized with [KiKit](https://github.com/yaqwsx/KiKit)

The USB port component is often out of stock on JLC.  However, it can be pre-ordered for a relatively low price, with a few weeks of lead time.
