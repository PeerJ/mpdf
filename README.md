mpdf
====
This is a fork of Ian Back's mPDF code found at
http://www.mpdf1.com/mpdf/index.php

Currently, using v5.2 as appears to be the most stable.

Note that this fork now deviates a bit in order to add additional font data without chaging the code.

Usage:

```
$mpdf = new mPDF(array("unifont" => array('R' => "unifont.ttf")));
$mpdf->mPDF('s');
```
