# oWrite Basic Editor with merge, print and export

The library implements a basic oWrite editor for the purpose of demonstrating minimal requirements to add rich-text editing features to Omnis Studio libraries, as well as the oWrite core features of merging data, printing and exporting documents.

To build the library you will require the OWrite, PDFDevice and OSpell2 external components by Brainy Data.

If you do not have them, demo versions of our external components are available at https://demos.brainydata.com. Furthermore, additional support files are required which can be downloaded from https://demos.brainydata.com/software/owrite_basic_merge_print_exp.zip.

Please refer to the online documentation for further information.
https://www.brainydata.com/supportpublic/documentation.htm

## Minimum requirements

Omnis Studio 10.2<br>
oWrite Desktop v5 beta 1<br>
pdfDevice v4.0.0<br>
oSpell2 v3.3.0


## Contents

### /src/OWriteBasicMergePrintExp

This folder contains the JSON source files for the Omnis library in Github.

To restore these files in Omnis Studio, click 'Libraries' in the Studio Browser, then click 'New Lib from JSON'. In the import dialog, navigate to this source folder (containing library.json), then specify a different location for the new Library. Click on Import and open the library in the Studio Browser.

To test your builds, simply replace the library with the identical name in the downloaded folders, with the ones you have just build. We use the GitHub repository as our version control system that will always provide the most up to date stable builds of our libraries. The GitHub repository makes it especially easy to spot differences between different commits.

#### ./OSpell2

Contains the example classes for implementing interactive spell checking.

#### ./OWrite

Contains the oWrite editor interface example classes for editing, merging, printing and exporting oWrite documents.

### /lib

The example library in binary format plus some additional support files. further support files are required which can be downloaded from the links above.
