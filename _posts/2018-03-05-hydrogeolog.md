---
layout: post
title: webpage install try
---
<!---this is comment---> 
# 1. making raspberry pi connecting with arduino using gpio without ftdi
  I have been thinking about this a lot and finally got solution:

![image](/images/rpi_arduino_serial.png)

{% highlight bash %}
npm install -g phant
{% endhighlight %}

more information
  oscar Liang was using 1.6k and 3.3k as voltage divider. while Deanmao was using 10k and 15k. the latter was found ok to receive data but not upload script. the former works perfectly

reference:
http://redhunter.com/blog/2015/01/09/raspberry-pi-arduino-ide-via-gpio/
https://github.com/deanmao/avrdude-rpi
http://www.deanmao.com/2012/08/12/fixing-the-dtr-pin/
https://oscarliang.com/raspberry-pi-and-arduino-connected-serial-gpio/
