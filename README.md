# bannertopdf-test
This repository is made to test the functionality of the `bannertopdf` filter which is a part of the [cups-filters](http://github.com/openprinting/cups-filters) repository. 

## Directory structure

1. The `banners` directory contains the banner files which are converted to PDF.
2. The `originals` directory contains the PDF files which are used as templates to banner files.
3. The `converted` directory contains the PDF files after conversion from banner files.
4. The `converted_qpdf` directory contains the PDF files after conversion from banner files using the new `bannertopdf` filter which depends on `QPDF` instead of `Poppler`.
