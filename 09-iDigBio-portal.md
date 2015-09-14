---
layout: lesson
title: iDigBio Portal
root: .
---

##Searching the iDigBio Portal:

- Every field returns results, but handles the entered data differently. Most fields are exact matches, and all follow Darwin Core definitions put in those fields by the people providing data. Data normalization, or the standardization of some fields, is done by iDigBio to help with searching records. 
	- The meaning of present or missing fields refers to the field, not the value in the field.

- Scientific name is what people entered in the scientific name field (ie not higher taxonomy!). It is important to remember the definition of the Darwin Core fields, not how the name is generally understood.

> **Task**: Search by Membracidae
	

 

> **Task**: Find all records from ranches in Texas
		- [Data files and master spreadsheet](https://goo.gl/gyRwx7)
>
> 1.  Whitsett New Ranch in Texas (idigbio normalizes during searches), can only search by one word in a field or exact match. But you have the general search!
> 2. Download and open and scream! What are all these fields!?!?!
> 3.  Open downloads in text editor
> 3. Open downloads to view in excel
> 3. What is weird about the datasets? how are they different and explain differences.
		> What is Json? One output is normalized and one is not. How many decimal places are really good? User defined fields. Why so many identifiers?
		> hide all non-locality fields (how is this iteratively efficient?)
		> now download all things "Ranch". Remember to select only those with geocoordinates are present (limit by Armstrong Co.).
> 3. Duplicates when you are sorting, Why? Thats because this is specimen records, not locality unique locality records.


##Publishers Page
*  Our Data: Collections. Be sure you are represented.
*  Our Data: Publisher recordset
*  Our Data: API

**Task**: Explore the added benefits of having your data in iDigBio.

##Research Tools:
###PhyloJive
  - Tutorial: [Introduction to PhyloJive](http://phylojive.acis.ufl.edu/PhyloJive/Tutorial.jsp)

>**Task**: Try searching the tree for *Pseudopsallus*.

###LifeMapper
  - Tutorial: [Introduction to LifeMapper on iDigBio] (http://lifemapper.acis.ufl.edu/lm/map/tutorial)

>**Task**: *Solenopsis invicta* Red-imported fire ant





Previous: [Regular Expressions.](08-regular-expressions.html)