TEI Customization - ODD and schema
========================================================
author: DiXiT Workshop 'Scholarly Digital Editions and Modern Greek Studies'
date: Athens, 24-28 April 2017
autosize: true



CHAPTER 1
=========

# Have we met before?


Well formed and valid
========================
<br/>
Remember?
<br/><br/>
- An XML document is **well formed** when it complies with the XML syntax
<br/><br/>
- An XML document is **valid** against a schema


Associate schema to a document
=======================

<img src="images/teiall.png">

***

<img src="images/help.jpg">

Schema helps you!

Suggestions, code completion, pop-up descriptions ...



Associate schema to a document
=========================
<img src="images/teiall.png">


***

<img src="images/angryfingershe.jpg" width="30%">&#8195;
<img src="images/angryfingerhe.jpg" width="30%">

Schema controls you!

Red square, error messages, invalid document ...


A schema
========================
<br/>
## defines **vocabulary** and **grammar**
<br/>
### which elements and attributes are to be used, where and how 
<br/>
e.g. which element you can use inside another element, which values you can give to an attribute


===============

<img src="images/angryfingershe.jpg" width="23%">&#8195;&#8195;
<img src="images/help.jpg" width="30%">&#8195;&#8195;
<img src="images/angryfingerhe.jpg" width="23%">
<br/>
<br/>

The good news is . . .
<br/>

## that you can create or adjust the schema !


TEI customization
===================
<img src="images/tei_areas.jpg">

***

Customization of the TEI is motivated by two really important things:

- the **diverse disciplinary needs and concerns** of the TEI community

- The goal of reconciling the need for a **common encoding language** with the need for **expressiveness**


Community-maintained TEI schemas
=========================
<br/>

- **tei\_all** 
- **tei\_lite** (light and basic encoding)
- **tei\_drama** (performance texts)
- **tei\_speech** (speech and spoken texts)

<small>
More at <http://www.tei-c.org/Guidelines/Customization/>
</small>
<br/><br/><br/>
Have you met them before?


Community-maintained TEI schemas
=========================
<br/>

- **tei\_all** 
- **tei\_lite** (light and basic encoding)
- **tei\_drama** (performance texts)
- **tei\_speech** (speech and spoken texts)

<small>
More at <http://www.tei-c.org/Guidelines/Customization/>
</small>
<br/><br/><br/>
Have you met them before? Yes, they are available in **oXygen** thanks to its TEI framework.



What happens if you change the schema?
=========================
<img src="images/teiall.png" width="60%">

Among the community-maintained schemas: 

- tei_all 
- tei_lite



Recap
========================
<br/>
## A schema defines **vocabulary** and **grammar** 
#### which elements and attributes are to be used, where and how 

# &#8679;

#### it represents in a structured and formalized way
## your **understanding of** and **approach towards** 
## the text to be encoded


=================

*A note on terminology:*
<br/><br/>
## TEI Customization = TEI Schema
<br/>
#### If you want to mark a difference, you can refer to the 
#### TEI Customization as the model  
#### and to the 
#### TEI Schema as the document where that model is implemented



=========================
## **ODD** (One Document Does it All) 
<br/>

- TEI document (that is a XML document)
- schema (for the machine)
- documentation (for the user, like the Guidelines)

<br/>

=========================
## **ODD** (One Document Does it All) 
<br/>

- TEI document (that is a XML document)
- schema (for the machine)
- documentation (for the user, like the Guidelines)

<br/>

#### E.g. ***tei\_dixit.xml*** or you can change the extension to ***tei\_dixit.odd***



Schema formats
==========================
left: 30%

<img src="images/teiall.png">

***

<br/>
*Do we associate the ODD to the document?*
<br/>

#### No! Most of the time we need to convert the ODD in a format the the XML processor will recognize as a schema.

- Which are this formats? DTD, RELAX NG schema, W3C Schema, etc.

- How do I generate a schema from an ODD? Using the web application Roma (we will do it) and in [other ways](http://www.wwp.northeastern.edu/outreach/seminars/_current/presentations/customization/customization_overview_tutorial_13.xhtml).


The ODD tree
=============
<img src="images/odd-tree.png">


========================
<img src="images/odd_stack.png">
<small>[A view of the whole system](http://www.wwp.northeastern.edu/outreach/seminars/_current/presentations/basic_odd/basic_odd_simple_tutorial_13.xhtml)</small>
<br/><small><small><small><small>From: Syd Bauman, Julia Flanders, and the Women Writers Project</small></small></small></small>


========================
<img src="images/tei_odd_customization_detail_iconed.png"/>
<small>[TEI customization under the hood (in a nutshell)](http://www.wwp.northeastern.edu/outreach/seminars/_current/presentations/customization/customization_overview_tutorial_12.xhtml)</small>
<br/><small><small><small><small>From: Syd Bauman, Julia Flanders, and the Women Writers Project</small></small></small></small>



Chapter 2
===============
# The TEI bricks


The TEI is ...
===========
<br/><br/>
not only a [big list of elements](http://www.tei-c.org/release/doc/tei-p5-doc/en/html/REF-ELEMENTS.html) ...
<br/><br/><br/>
They are structured in modules and classes

Elements
==============
left: 30%

<img src="images/tei_as_lego.png">

***

TEI has some 550 elements and a very large number of attributes!

They are grouped into **modules** that represent the kinds of texts or features being represented: for instance, poetry, or manuscripts, or dictionaries.

They are also grouped into **classes** that divide them by their functions, by the kinds of things the elements can do: for instance, elements that are parts of bibliographic items, or attributes that are needed on pointing elements.


Modules
===================
left: 30%

<img src="images/TEI_modules_simple.png">

***

Modules are like lego kits for making specific kinds of things(like helicopters or castels). There are basic kits and specialized kits.

- Each module corresponds to a chapter in the TEI guidelines
- Each element belongs to one and only one module.


The class system
============================
We can think of the TEI class system as a way of grouping together elements that **behave in the same way** and that tend to **go in the same place**.

- Classes of elements are named model.*the class* (e.g. model.global)

Attribute classes are very similar: they are **groupings of attributes that are related**, so that when you want one of them, you typically want most of them.

- Classes of attributes are named att.*the class* (e.g. att.global)


The class system. Some classes of elements
============================
<img src="images/tei_classes_conceptual4.png">


The class system
=========================

And now ... [exercise time](exerciseClasses.pdf) (3 mins :)


Chapter 3
================
Customizing the TEI


Customization options
=====================
Options for customization:

- Select modules
- Delete unnecessary elements
- Add new elements or attributes
- Change element or attribute names
- Constrain attribute values
- Constrain structure
- Manipulate functional groupings of elements
- Produce an internationalized version of the TEI


TEI under the hood (in a nutshell)
==================================
<img src="images/tei_odd_detail.png">

***

<small>
The TEI exists as a universe of possible schemas, and the actual schema (the "file") consists of a large number of little pieces representing the definitions of individual elements, attributes, classes, and so forth.

The 'custom-made-car dealership' metaphor:
- you select the parts: core + optional
- the car is generated (including user manual!)
</small>

ODD is TEI
======================

This TEI universe of possible schemas (including your actual schema) are written using a specialized part of the TEI language: a special set of elements and attributes that are designed for describing and documenting the parts of a schema.


TEI customization under the hood
==========================
left: 70%

<img src="images/tei_odd_customization_detail_iconed.png">

***

The ODD needs to be transformed into another format (RNG, RNC, DTD, ...) for being understood by XML processors


TEI customization under the hood
========================
<img src="images/odd_stack.png">


ODD processors
=======================
The transformation 'ODD ---> RNG, RNC, DTD' can be made using one of the following

- Roma: a web interface (available at the TEI site)
- oXygen's built-in stylesheets (instructions)
- Oxford University's OxGarage multi-transformer
- roma: a command-line tool (installation instructions) that does all the conversions (RELAX NG, HTML, PDF, DTD, XML Schema, Schematron) at once
- etc.

Recap
==========================
- **Customization**: reflects your scientific choices, reinforce consistency, document your work

Recap
==========================
- **Customization**: reflects your scientific choices, reinforce consistency, document your work

- A TEI document should be **well formed** (XML rules) and **valid** (schema rules)

Recap
==========================
- **Customization**: reflects your scientific choices, reinforce consistency, document your work

- A TEI document should be **well formed** (XML rules) and **valid** (schema rules)

- The TEI Guidelines are organized with **elements**, **modules** and **classes** (for elements and attributes)

Recap
==========================
- **Customization**: reflects your scientific choices, reinforce consistency, document your work

- A TEI document should be **well formed** (XML rules) and **valid** (schema rules)

- The TEI Guidelines are organized with **elements**, **modules** and **classes** (for elements and attributes)

- The TEI Guidelines consists of a **universe of possible schemas**, from very large and permissive to very narrow and restrictive ... select the parts and **create yours**!

Recap
==========================
- **Customization**: reflects your scientific choices, reinforce consistency, document your work
- A TEI document should be **well formed** (XML rules) and **valid** (schema rules)
- The TEI Guidelines are organized with **elements**, **modules** and **classes** (for elements and attributes)
- The TEI Guidelines consists of a **universe of possible schemas**, from very large and permissive to very narrow and restrictive ... select the parts and **create yours**!
- The TEI customization expressed in **ODD** is transformed in **other formats** (using **Roma** and other processors); the file generated will be the schema that you associate to your TEI document




ROMA - <http://www.tei-c.org/Roma/>
===============
<small>
The opening page for Roma offers several options

- **Build schema**.
This option allows you to start building your schema customization by starting with a very minimal schema and adding modules to it. This is a good starting point if you want to build a fairly small, tightly constrained schema.
- **Reduce schema**. This option allows you to start building your schema customization by starting with a very large schema including all of the TEI modules, and then removing what you don't need. This is a good starting point if you want to build a very extensive schema including most of the TEI modules.
- **Create customization from template**. This option allows you to build a schema starting from one of the templates listed in the accompanying menu; these serve as convenient starting points from which you can then make further modifications, such as adding or deleting modules or elements.
- **Open existing customization**. This option allows you to upload an existing customization file, either one that you may already have saved, or one that you have received from someone else. You can then make further customizations to this file and save the revised version.
</small>

ROMA - Metadata of your customization
================
Enter some basic metadata about the schema specification you're creating:

- **Title**: this is the title by which you refer to your schema; it will appear in the accompanying documentation and in the TEI header for your customization file.
- **Filename**: this is the filename for your customization file (the name under which it will be saved on your computer)
- **Prefix**: this is the prefix that will be used within the schema to designate TEI pattern names
- **Language**: this allows you to choose a language for the Roma interface (it does not affect the language of the resulting schema or documentation)
- **Author name**: the name of the author of the schema customization
- **Description**: a brief description of the schema you're creating, perhaps with some explanation of what it is intended for. This description will appear as a descriptive paragraph at the start of your customization file.



================
Subsequent pages have a row of tabs for each of the major tasks involved in making a customization (Modules, Add elements, Change classes, and Language) for creating various outputs from a customization (Schema and Documentation) and for acting on your customization (New, Customize, and Save). Several of these tabs are explained briefly in the instructions that follow.

WORK IN PROGRESS ...

Credits and links
==============
<small>

These slides reuse materials from

- the TEI-C resources, and in particular
  - <http://www.tei-c.org/Guidelines/Customization/odds.xml>
  - <http://www.tei-c.org/Guidelines/Customization/use_roma.xml>

- the Women Writers Project educational resources, and in particular
  - <http://www.wwp.northeastern.edu/outreach/resources/customization.html>
  - <http://www.wwp.northeastern.edu/outreach/seminars/_current/handouts/exercise-roma.xhtml>
  
  Please visit these links if you want to know more!
</small>

==========
Elena Spadini

DiXiT Workshop 'Scholarly Digital Editions and Modern Greek Studies'

Athens, 24-28 April 2017

CC-BY-NC-SA

