
# Assignment-1
Extract text blocks from a PDF document with each paragraph as a separate line and text being in reading order going from first column from top to bottom and then into second column and then third column. Dump the output in an excel file.
I have employed the pymupdf and openpyxl libraries. I read the page as blocks using PyMuPDF. I was able to locate the paragraphs using the coordinates given by PyMuPDF . After extracting the paragraphs into a dataframe, I made a few minor cleaning improvements. I then dumped it all onto Excel. Any PDF page in the provided PDF can be run using this code.



# Assignment-2
Detect and locate tables inside a page using DNN, then parse the table to extract a dataframe that should not lose any information and structure of the table. The output should be an excel file containing the extracted table.
The solution should be a general solution that can work on different pages of different PDFs.

# Assignment-3
Train a named entity recognition model to identify the various entities present in the database. The final input will be a text string and the program should output all the named entities along with the entity text in dictionary format.


