#Objective: To create a camera with AI recognition functionality.

## SoC
I tried selecting from available development boards on the market, 
but many of them are not sold on LSCS (such as SG2002, RTL8735...), 
or they have very limited reference materials. Ultimately, I found the K210, 
which has many open-source development boards and plenty of related resources.

## choose compenents
I referred to the datasheet and various development boards to design the circuit concept, which includes USB-C power supply, additional 32M flash memory, a 24-pin camera, a 16-pin LCD, and a microphone. The datasheet originally showed a 40-pin LCD, so I assumed I had to use a 40-pin LCD. However, I couldn’t find a 40-pin LCD, and later realized that I could remove some pins and use an LCD with a different interface.