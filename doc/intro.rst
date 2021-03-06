XMOS AVB Specification
======================

 +-------------------------------------------------------------------+
 |                       **Supported Standards**                     |
 +=================================+=================================+
 | Ethernet                        | IEEE 802.3 (via MII)            |
 +---------------------------------+---------------------------------+
 | AVB QoS                         | IEEE 802.1Qav, 802.1Qat         |
 +---------------------------------+---------------------------------+
 | Precision Timing Protocol       | IEEE 802.1AS                    |
 +---------------------------------+---------------------------------+
 | Audio Stream Encapsulation      | IEEE 1722                       |
 +---------------------------------+---------------------------------+
 | Audio Format                    | IEC 61883-6 AM824               |
 +---------------------------------+---------------------------------+
 | Enumeration and control         | IEEE P1722.1 (Draft 21)         |
 +---------------------------------+---------------------------------+
 |                       **Supported Devices**                       |
 +---------------------------------+---------------------------------+
 | XMOS Devices                    | | L16-128                       |
 |                                 | | L12-128                       |
 +---------------------------------+---------------------------------+
 |                       **Requirements**                            |
 +---------------------------------+---------------------------------+
 | Development Tools               | xTIMEComposer suite v12.0 or    |
 |                                 | later                           |
 +---------------------------------+---------------------------------+
 | Ethernet                        | | 1 x MII compatible 100Mbit PHY|  
 +---------------------------------+---------------------------------+ 
 | Audio                           | | Audio input/output device     |
 |                                 |   (e.g. Audio CODEC)            |
 |                                 | | PLL/Frequency synthesizer     |
 |                                 |   to generate CODEC master clock|
 +---------------------------------+---------------------------------+ 
 | Boot/Storage                    | Compatible SPI Flash Device     |
 +---------------------------------+---------------------------------+
 |                       **Licensing and Support**                   |
 +-------------------------------------------------------------------+
 | Reference code provided without charge under license from XMOS.   |
 | Support via http://www.xmos.com/secure/tickets.                   |
 | Reference code is maintained by XMOS Limited.                     |
 +-------------------------------------------------------------------+