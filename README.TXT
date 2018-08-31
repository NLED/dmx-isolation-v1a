THERE IS NO WARRANTY FOR THE PROGRAM, TO THE EXTENT PERMITTED BY APPLICABLE LAW. 
EXCEPT WHEN OTHERWISE STATED IN WRITING THE COPYRIGHT HOLDERS AND/OR OTHER PARTIES 
PROVIDE THE PROGRAM “AS IS” WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESSED OR IMPLIED,
INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS 
FOR A PARTICULAR PURPOSE. THE ENTIRE RISK AS TO THE QUALITY AND PERFORMANCE OF THE 
PROGRAM IS WITH YOU. SHOULD THE PROGRAM PROVE DEFECTIVE, YOU ASSUME THE COST OF ALL 
NECESSARY SERVICING, REPAIR OR CORRECTION.

 Original Author: Jeffrey Nygaard
 Company: Northern Lights Electronic Design, LLC
 Date: August 30, 2018
 Contact: JNygaard@NLEDshop.com
 Copyright© 2018 by Northern Lights Electronic Design, LLC. All Rights Reserved
 
;=============          www.NLEDShop.com/miscproducts          ============
;=============     www.NorthernLightsElectronicDesign.com       ============

This work is licensed under a Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)
https://creativecommons.org/licenses/by-nc/4.0/legalcode

Free to use for personal use, but please attribute the original author.

Commercial licenses versions are available for a donation of any amount. Contact JNygaard@NLEDshop.com for details.

================================================================================================================

Ready-made devices are available for purchase, and large batch manufacturing of any device can be requested.
Please see the webpage www.NLEDShop.com/miscproducts

NLED is available for custom design and manufacturing, please contact via phone or email to discuss your project.

================================================================================================================

This simple device offers full electrical isolation for differential signals, such as DMX or RS485. Based on the 
venerable SN75176 transciever with a dual digital isolator and 1:1 DC-DC transformer. The device accepts a TTL input 
signal when setup to transmit and outputs a TTL signal when setup to receive. The differential conversion is handled
by the transciever. Accepts voltages from 5 to 12 volts, but always outputs TTL(0 to 5 volt) signals. This device 
works with many NLED products and controllers, but would also work with any Arduino or other embedded device as it 
communciates with standard TTL signals. For details on electrical isolation specifications, please use the BOM to 
look up part datasheets for details.

Minimum Input Voltage: 5 volts
Maximum Input Voltage: 12 volts
See CRE1S0505S3C  datasheet for electrical isolation details

Jumper settings:

	Close jumper VREG-J if voltage input is 5 volts.
	If voltage is higher than 5 volts, leave jumper open.

	Must close DIR-J to 'T' for transmitting, or 'R' for reception

	Jumper TERM is the signal terminator. Close jumper if receiving and
	the last or only receiver on the DMX network.

BOM:
	1x CRE1S0505S3C 
	1x SI8621AB-B-IS 
	1x SN75176BDR 
	1x AP2210K-5.0TRG1 
	2x C1Q 250 fuses
	1x 10uF 0805 capacitor
	2x 0.1uF 0805 capacitor
	1x 100pF 0805 capacitor
	1x 120 ohm 0805 resistor