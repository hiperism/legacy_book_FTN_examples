legacy_book_FTN_examples
Fortran Examples for the Guide to Numerical Algorithm Design and Development
(01-29-2025)

These are files containing the Fortran examples for the book:

Guide to Numerical Algorithm Design and Development: Including Legacy Examples from Fortran and MathCAD in High Precision

George Delic, Ph.D. University Fellow, University of Wollongong, Wollongong, NSW, Australia

Each example is in a compressed format "*.tar.gz" created on a linux system and each has its own README file on how to compile and run the example on your own platform.

Changes may be necessary for the compile, Makefile, and run scripts.

After download follow these steps on your own platform for each example.

create a directory with the example name
copy the file to that directory
explore the contents of the file
unzip the file
untar the file
As an example for KERRIGAN these are the steps

mkdir KERRIGAN
cp kerrigan.tar.gz KERRIGAN
cd KERRIGAN
tar -tzvf kerrigan.tar.gz
gunzip kerrigan.tar.gz
tar -xvf kerrigan.tar
LICENSE AND COPYRIGHT This author's intent is to make the examples freely available within the limitations of previous copyright holders. Therefore please be sure to observe any special licensing or re-use requirements (especially for code previously published). For details see the README file acompanying each example.

If any of these examples are used in any derivative works the source must be acknowledged with a suitable citation of this book and the code origin.

FOOTNOTE ON THE FOLLOWING FORTRAN EXAMPLES:

STIR: Look at the PDF of report IKDA 73/8 to find the definitions of the coefficients in the output file

SPARSE: This is recent code in a parallel model. A serial version will be provided in a small package after extraction from a larger environmental/climate model. Stay tuned ...
