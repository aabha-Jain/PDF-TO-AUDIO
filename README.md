# PDF-TO-AUDIO

This file uses python libraries to convert pdf text to speech

Libraries used are :

pyttsx3: It is a Python library for Text to Speech. It has many functions which will help the machine to communicate with us. It will help the machine to speak to us

PyPDF2: It will help to the text from the PDF. A Pure-Python library built as a PDF toolkit. It is capable of extracting document information, splitting documents page by page, merging documents page by page etc.

Approach:

Import the PyPDF2 and pyttx3 modules.

Open the PDF file.

Use PdfFileReader() to read the PDF. We just have to give the path of the PDF as the argument.

Use the getPage() method to select the page to be read.

Extract the text from the page using extractText().

Instantiate a pyttx3 object.

Use the say() and runwait() methods to speak out the text.
