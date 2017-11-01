---
title: PSK Introduction
separator: <!--s-->
verticalSeparator: <!--v-->
theme: solarized
revealOptions:
    transition: 'fade'
---
# PSK Data mode

## Martin Murphy - EI2HIB
### 2017-08-28 

<!--s-->

# PSK

* Teletype mode
* PSK31 designed for typing speed
* Data converted to audio to be sent
* Encoded using Binary Phase Shift Keying
* approx 31 baud
* variable bits per character
* most common characters are shorter
* lowercase is shorter

<!--s-->

# Software
* fldigi
* hrd
* others

<!--s-->

# Macros
* you can type, most people use macros
* &lt;TX&gt; CQ CQ CQ DE EI2HIB EI2HIB PSE K&lt;RX&gt;
* lowercase is faster to send
* &lt;TX&gt; cq cq cq de ei2hib ei2hib pse k&lt;RX&gt;

<!--v-->
# Macros 2
* Configure software with your details:
  * MYNAME = Martin
  * MYCALL = EI2HIB
  * MYQTH = Tramore, Ireland
  * MYLOC = IO62kd
* &lt;TX&gt; cq cq cq de &lt;MYCALL&gt; &lt;MYCALL&gt; pse k&lt;RX&gt;

<!--v-->
# Macros 3
* Configure software with your details:
  * MYNAME = Martin
  * MYCALL = EI2HIB
  * MYQTH = Tramore, Ireland
  * MYLOC = IO62kd
* &lt;TX&gt; &lt;YOURCALL&gt; de &lt;MYCALL&gt; &lt;MCALL&gt; kn&lt;RX&gt;

<!--v-->
# Macros 4
* Configure software with your details:
  * MYNAME = Martin
  * MYCALL = EI2HIB
  * MYQTH = Tramore, Ireland
  * MYLOC = IO62kd
* &lt;TX&gt; &lt;YOURCALL&gt; rsq: &lt;RSTOUT&gt; &lt;RSTOUT&gt; name: &lt;MYNAME&gt; qth: &lt;MYQTH&gt; loc: &lt;MYLOC&gt;&lt;RX&gt;

<!--s-->

# Radio setup
* Disable any audio processing
* Disable auto gain control

<!--s-->

# Tips
* watch first, see how QSOs are working
* probably best to initially just answer someones call
* When you've done that for a while try CQ
* Check on pskreporter.info if you've been heard

<!--s-->

# Questions?
## Martin Murphy - EI2HIB
### 2017-08-28 

<!--s-->

# References

* [pskreporter](https://www.pskreporter.info/)
* [fldigi](http://www.w1hkj.com/)
* [SEARG](http://www.searg.ie)
* [Presentation Template](https://github.com/martinmurphy/slidestemplate)
