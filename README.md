# Split-XMLFiles
## Purpose
This is a python routine that splits a file that contains multiple XML documents in individual XML documents in order they can be processed by Python XML parsing library, this couldn't be done with all the XML documents contained in a single XML.
## What it does
It takes the big XML file and looks for the initiation markers of each XML document. 
It creates a directory for each big XML file processed and drops the splited XML file in that directory.
