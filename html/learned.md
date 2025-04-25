# Lessons Learned

<br> Home: &#x2302; [Introduction](../index.md) &#x2302;  

##

## Lessons

### Measuring Capacitor and Diode Ratings

While it wasn't pertinent to understanding the intended functionality of the circuit in this dissection, understanding how capacitors and diodes function and how their ratings affect said function may be required for this purpose. However, it did prove useful for somewhat accurately determining the bill of materials for the SL-100L calculator.

### Taking and Reading Timing Diagrams

Timing diagrams can provide invaluable insight into component implementation and the logic driving a system. Everything from the recorded voltage levels to the frequency of a signal can help determine how specific components are being utilized or provide hints to the underlying logic driving them. For example, the timing diagrams recorded as a part of this dissection revealed the bias of the LCD and the debouncing logic used to receive stable input from the keypad.

### General Component Analysis

Understanding the specifications of individual components may help to prevent the misinterpretation of the system’s overall functionality or implementation. For example, there are multiple ways to drive LCDs; knowing these variations exist and their subtle or not-so subtle differences helps drive the analysis of measurements or the general circuit to determine which implementation is in use in a given system. With regards to this dissection, simply looking at the number of traces connecting the LCD to the microcontroller and knowing how many segments the LCD contains revealed that it was dynamically driven and not static.

### Markdown

Unrelated to the performing of the dissection itself, this report has been fully written and formatted using Markdown as a base before being translated to HTML. Overall, a deeper appreciation for Markdown and an understanding of its versatility/original purpose was developed as a part of this effort.

### Additional Experiences

* Flex-cables are not as fragile as they first appear, yet one should still refrain from bending or twisting them
* Wire insulation should be stripped to a reasonable length before soldering lest one wishes to meld it with their solder
* One should always watch the tip of their iron closely
* Screws are prone to becoming lost

##

<br> Prev: ◄— [Reassembly](../html/reassembly.md) ◄—

##
