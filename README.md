All-to-DPS
==========

This will convert multiple files (jpg, jpeg, png and PDF) to a DPS readable format.

This script is based upon a Adobe Released Script found here:
[Adobe's script](http://www.adobe.com/devnet/digitalpublishingsuite/articles/dps-pdf-to-indesign.html)

This script is a heavilly modified version of that so lets recap the differences:
Adobe's version

+ PDF conversion to InDesign
+ Creates a flipbook like style book
+ Automatically Fits the Pages

RedactiePartners Version:

+ PDF, JPG/JPEG, PNG conversion to InDesign
+ Creates a Flipbook like style book
+ Create Single full screen Pages for Single Paged Books
+ Automatically Fits the Pages
+ Inputs for RGB Values for background Color
+ Support for multiple Devices by providing your own resolution

a good resolution resource can be found here: 
[Screensizes](http://www.screensiz.es)


Installation
============

1. Download the .jsx file
2. Copy it into the appropriate InDesign "Scripts/Scripts Panel" folder

Instructions
============

1. Create a single file for each page (be it PDF, JPG or PNG every page needs it's own file)
2. follow the following naming convention for the files

	Cover page:  
	PCN1_publication-name-here_date-here.extension-here  
	Inside Cover:  
	PCV2_publication-name-here_date-here.extension-here  
	Inside Back:  
	PCV3_publication-name-here_date-here.extension-here  
	Backside:  
	PCV4_publication-name-here_date-here.extension-here  

Like so:  
![Example File naming](http://i.imgur.com/SKsycgW.jpg)

4. In InDesign open the Scripts Panel
5. Run the script
6. Choose your options and choose the appropriate folder
7. Profit!

Upcoming Updates
================

+ Look at possibilities for more advanced cropping system (currently it uses the PDF TrimBox)

License
=======
Copyright 2013 Adobe Inc. and RedactiePartners  
http://redactiepartners.nl/

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
