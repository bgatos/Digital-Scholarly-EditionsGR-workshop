What is, Why  and How to make a TEI schema (ODD)
========================================================
author:
date: 
autosize: true

===================

<img src="images/tei_areas.jpg">

***

Customization of the TEI is motivated by two really important things:

- the diverse disciplinary needs and concerns of the TEI community

- The goal of reconciling the need for a common encoding language with the need for expressiveness


A schema
========================

- defines a vocabulary and a grammar, that is which elements and attributes are to be used, where and how (for example, which element you can use inside another element!)

- gives consistency to the encoding

- most importantly: it represents in a structured form your understanding of and approach towards the text to be encoded


Well formed or valid?
========================

- An XML document is **well formed** when it complies with the XML syntax (remember the *golden rules*!)


- An XML document is **valid** against a schema


Existing Schemas
=========================
TEI offers some community-maintained (ready-to-use) schemas; but it suggests to prepare a **customized** one, that better addresses your specific needs.

Here are some of the schemas made available and maintained by the TEI:

- **tei\_all** includes all elements and attributes and the rules for using them
- **tei\_lite** is a selection of elements and attributes, which allows for a basic encoding of a variety of texts
- **tei\_drama** is a selection of elements and attributes for encoding performance texts, for example theatre and cinema
- **tei\_speech** is a selection of elements and attributes for encoding transcription of speech and spoken texts

More at <http://www.tei-c.org/Guidelines/Customization/>


Associating a schema to a document
=========================
<img src="images/teiall.png" width="80%">

Let's try to change the schema associated with a document. What happens?


ODD and schema formats
=========================
An **ODD** (One Document Does it All) is a XML document that contains the schema **and** all the relative documentation (prose and structured).

An ODD can be transformed in one of the formats suitable for a schema (DTD, RELAX NG schema o W3C Schema), using the web application Roma and in [other ways](http://www.wwp.northeastern.edu/outreach/seminars/_current/presentations/customization/customization_overview_tutorial_13.xhtml).


ODD and schema formats
========================
<img src="images/tei_odd_customization_detail_iconed.png"/>


ODD and schema formats
========================
<img src="images/odd_stack.png">


The TEI Guidelines
===========
When we encounter the Guidelines as encoders, this is what we see: a [big list of elementsè](http://www.tei-c.org/release/doc/tei-p5-doc/en/html/REF-ELEMENTS.html) (vocabulary we can use in describing documents) with definitions of these elements that tell us how they should be used.

However, if we look closely, we can see that there is some additional information here as well. This information (like the module and class information) is useful for customization, and it’s what we will elucidate in the following slides.  


Elements
==============
left: 30%

<img src="images/tei_as_lego.png">

***

TEI has some 547 elements and a very large number of attributes. In order for humans to get a handle on these and be able to think of them without suffering from brain overload, it is very helpful to divide them up into sets or groupings. TEI does this in two ways:

First, it groups them into modules that represent the kinds of texts or features being represented: for instance, poetry, or manuscripts, or dictionaries.

Second, it groups them into classes that divide them by their functions, by the kinds of things the elements can do: for instance, elements that are parts of bibliographic items, or attributes that are needed on pointing elements.


Modules
===================
left: 30%

IMAGES OF LEGO KITS!

***

CUT THIS:

You can think of modules as being something like Lego kits for making specific kinds of things (like helicopters or castles). When you buy Lego, you can get a starter set with all the basic stuff: this is like the TEI’s basic modules (the ones you absolutely have to have: the core, the header, the text structure, and the TEI module itself). With the basic module/starter kit you can make all sorts of basic things, but if you want to build a helicopter you need the rotor and the landing gear and so on, and you get these by getting the helicopter kit. Similarly, in TEI if you want to encode drama you need the drama module (which gives you cast lists and other drama-specific things).

Each module corresponds to a chapter in the TEI guidelines, and each element belongs to one and only one module. In TEI customization, we start by choosing the modules that we need for the kinds of texts we’re going to encode.


The class system
============================
left: 40%

<img src="images/tei_classes_conceptual4.png">

***

We can think of the TEI class system as a way of grouping together elements that behave in the same way: that tend to go in the same place (like water fountains and bathrooms, or like all the overhead lights in a room of your house being on the same circuit).

Attribute classes are very similar: they are groupings of attributes that are related (so that when you want one of them, you typically want most of them).

IN PROGRESS
=====================
In progress from here:
http://www.wwp.northeastern.edu/outreach/seminars/_current/presentations/customization/customization_overview_tutorial_09.xhtml


ROMA - <http://www.tei-c.org/Roma/>
===============
<small>
The opening page for Roma offers several options
(<file:///C:/Users/Elena/Desktop/odd/TEI_%20Using%20Roma.html>):

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



==============
These slides reuse materials from

- the TEI-C resources, and in particular
  - <file:///C:/Users/Elena/Desktop/odd/TEI_%20Getting%20Started%20with%20ODDs.html>
  - <file:///C:/Users/Elena/Desktop/odd/TEI_%20Using%20Roma.html>

- the Women Writers Project educational resources, and in particular
  - <CUSTOMIZATION PRIMER>
  - <file:///C:/Users/Elena/Desktop/odd/Creating%20a%20Customization%20with%20Roma.xhtml>

