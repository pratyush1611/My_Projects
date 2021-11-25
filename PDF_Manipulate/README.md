# README
------------
## Aim: 
To make an app which takes a pdf or a folder containing pdf files and outputs a ready to print optimised PDF or folder contining PDFs.

---------------
## Definitions

Optimised: 
Optimised as a booklet to print at TU Delft Library. 

Booklet size: 
A3 to minimise cost incurred (since both A4 and A3 prints cost the same)

Ready To Print: 
A3 booklet form with 2 A4 pages on each side, every even page   flipped by 180 degrees (because A3 print at Library doesn't flip along short edge of A3 page)

--------
## Why do this?
1. saves money
2. saves paper
3. saves electricity, by printing half the number of pages
4. dont have to deal with annoying flips in single stapled documents

---------
## Output
The modified PDF files will be found in a new folder named as `tempBookletOutput`

--------
## Future Work
check for scaling of pages and ensure that no matter what the input page size is, it doesnt affect the output, right now it assumes that you are providing only A4 size pages


