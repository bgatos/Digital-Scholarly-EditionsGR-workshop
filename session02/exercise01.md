**Άσκηση 01 | exercise 01**

*Ενότητες*

- Α. Χρησιμοποιώ τον oXygen XML Editor

- Β. Δημιουργώ ένα well-formed XML



This exercise will walk you through creating an XML document in the oXygen editor and
introduce a variety of ways to mark this document up. You will first start a new document,
then insert some unmarked up text into the editor, and then mark up the stanzas or line-groups
(lg) and lines (l). You will learn to check that your document is well-formed or not.
Note: read each step before you do it.
3 Starting A New XML File
Let’s start a new XML file by following the following steps:
• Load up the oXygen XML Editor if it isn’t already loaded by using the Windows Start
Menu, or double-clicking the icon on the desktop.
• Once the editor has fully loaded you may wish to close any additional popup windows,
and optionally the ’views’ on the left and right-hand side. This will give you more space.
• From the ’File’ menu select ’New’ and double click on ’New Document’ select ’XML
Document’ This should open up a blank document with an XML Declaration added.
• An XML Declaration looks like:
                <?xml version="1.0" encoding="UTF-8"?> 
              
and the XML declaration in the element tells anything processing your XML file, including
the editor, that this is an XML file and what version of XML you are using through the
@version attribute. It also conveys which characters the program may expect in attribute
@encoding. XML version 1.0 is a W3C recommendation from 2008. UTF-8 (Universal
Character Set Transformation Format - 8 bit) contains most characters from all human
writing systems. The XML declaration needs no closing tag as it takes the form of a
special processing-instruction that starts and ends with an angle-bracket and a question
mark.
