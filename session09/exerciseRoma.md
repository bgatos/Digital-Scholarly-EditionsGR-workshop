	
# Working on Schema customization with ROMA

This exercise reuses tutorials at

- <http://www.wwp.northeastern.edu/outreach/seminars/_current/handouts/exercise-roma.xhtml> Licence: CC-BY-NC-SA

- <http://www.tei-c.org/Guidelines/Customization/use_roma.xml> Licence: CC-BY

## Before you start
In this exercise, you will use Roma, a web tool available from the TEI web site. You will need access to the internet and a web browser such as Firefox or Opera and once you have your schema you will also need an XML-aware editor to use it (e.g., oXygen).

These instructions only cover part of Roma’s functionality. They describe the steps needed to
- select modules,
- delete elements,
- delete attributes, and
- constrain attribute values

These instructions do not cover some other capabilities of Roma, including adding elements; changing an element’s class membership, contents, or description; changing an attribute's permitted values (other than to a closed list of values); changing the language of Roma interface itself or of the elements & attributes generated.

## Getting started
Open the Roma application. When you are on-line, you can point your favorite web browser to <http://www.tei-c.org/Roma/>.

You should get to the Roma start screen, which says something like 'Roma: generating validators for the TEI' at the top. 

Check the 'Open existing customization' radio button, upload the file at ...... and click Submit!

## Metadata
Now enter basic metadata of your customization:

- For the **title** choose a meaningful (for you!) name, like 'My first TEI customization' or 'Athens Workshop Customization'.
- For the **filename**, it’s a good idea to avoid characters that may confuse operating systems, like slashes, back-slashes, colons, spaces, etc. You can use something like 'myTEI' or 'athensTEI'.
- Choose the **language** you prefer. Remember that this will only affect Roma and NOT the customization (inlcuding the documentation) that you are creating
- The **author** is you!
- Adding a short **description** is a good practice, for you (in order to remember months later) and for others

Press the Submit button (and don't worry if nothing happens, it works and you can continue)

## Modules

In this page (List of TEI modules) you can choose the modules which will be included in the schema. The full list of available TEI modules is listed on the left, and at the right there is a ‘List of selected modules’ which is the list currently selected for your schema.

For this exercise, remove the module Dictionary.

## Elements 

It is often the case that the modules chosen contain many more elements than are desired. Removal of elements is performed on a module by module basis. 

First click on a module name from the List of selected Modules (the right column). For this exercise, click on the module Core. This should take you to the appropriate Change module page.

Have a look at the elements listed and find one that will not be used in the encoding of letters (like the ones we have worked with). For example, the element 'analytic'. Now you can Exclude it. 

Here it is another example: if you know that the material you are encoding does not contain any poetry, you will probably wish to click the Exclude radio buttons for 'l' and 'lg'.

Don't forget to Submit your changes before leaving the page!

## Attributes

For each element in the Change modules page there is a Change attributes link on the right. Clicking on this link will bring you to a page for changing or adding attributes called Added Attributes.

For this exercise, click on the element ?????

For each attribute, its canonical name is provided on the left, and radio buttons for inclusion and exclusion just as for elements follow. 

Clicking on an attribute’s name from the left column brings you to a page that permits you to customize that attribute for the given element. If you want to change an attribute for all elements on which it occurs, you would need to change it in its class (Roma permits this, but it is not covered in this document).

For this exercise, click on the attribute ???


---- 
Notes on what follows .... IN PROGRESS!!

The page for attribute modification permits you
Choose whether the attribute is required or optional
Select its content, e.g. data.enumerated for a list of particular values
Choose a default value (should be left blank unless you know your software handles these)
Choose whether a list of values is open (values other than those listed are permitted) or closed (only the listed values are permitted). This should have no effect unless there is a list of values.
Specify a list of values: a comma-separated list of XML Names.
Write a more detailed or specific description of the attribute. This description will appear in the reference documentation for your schema.


Submit your changes!

## Saving your ODD files

blablabla


## Outputs


blablabla documentation rng blablabla



---
**About this exercise**

Publication: DiXiT Workshop *Digital Scholarly Editions and Modern Greek Studies*. Athens, 24-28 April 2017.

Author: Elena Spadini

Reusing materials published by TEI-C and Women Writers Project, as specified above.

Licence: CC-BY-NC-SA <https://creativecommons.org/licenses/by-nc-sa/3.0/>
