# school-pictures
We have a picture frames that show all 12 school pictures but the photos need to be a weird size. 

Use this template to print the school pictures at the exact right size on a single 4x6 photo at Walmart or wherever.

Print as a PDF, then convert the PDF to a JPEG. If you are doing this on a Linux PC you can use this to do the conversion:

```sh
pdftoppm -jpeg -jpegopt quality=100 -r 300 ~/Downloads/School\ Pictures.pdf ~/Downloads/school-pictures
```
