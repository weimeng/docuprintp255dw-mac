Fuji Xerox DocuPrint P255 dw Mac driver
=======================================

The [Fuji Xerox DocuPrint P225 dw](http://www.fujixeroxprinters.com.au/en/products/blackwhiteprinters/docuprintp255dw.aspx)
is a nice, cost-effective black & white laser printer. Unfortunately, official
driver support for Mac OSX is terrible to the point of rendering the printer
nearly unusable.

After extensive searching around the internet for a solution, I managed to find
a decent alternative driver for those of us on OSX.

Special thanks to David Webb who converted the Windows PPD file for use with
Ubuntu. You can find his original post and driver [at his blog](http://thebigbyte.blogspot.sg/2013/07/linux-printer-drivers-fuji-xerox.html).

I've fixed some minor typos and also added the proper default printer icon for
use on the Mac. To get the icon, first install the
[official Mac OSX drivers from Fuji Xerox](http://www.fujixeroxprinters.com.au/en/Downloads.aspx?product=11252&category=5726&os=8192&dl=1).

Install Instructions
--------------------

1. Download the [driver](https://raw.github.com/weimeng/docuprintp255dw-mac/master/fxtpn1a.ppd)
2. Add a printer through the Printers panel in System Preferences
3. When choosing a driver, select "Other" under the "Use" dropdown menu, and select the downloaded driver file
4. Done!
