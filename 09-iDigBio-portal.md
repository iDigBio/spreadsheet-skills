---
layout: lesson
title: iDigBio Portal
root: .
---

##Searching the iDigBio Portal:

1. Every field returns results, but handles the entered data differently. Most fields are exact matches, and all follow Darwin Core definitions put in those fields by the people providing data. Data normalization, or the standardization of some fields, is done by iDigBio to help with searching records. 

2. Scientific name is what people entered in the scientific name field (ie not higher taxonomy!). It is important to remember the definition of the Darwin Core fields, not how the name is generally understood.

> Task: Search by Membracidae
	
3. The meaning of present or missing fields refers to the field, not the value in the field. 

> Task: Find all records from ranches in Texas
>
> 1.  Whitsett New Ranch in Texas (idigbio normalizes during searches), can only search by one word in a field or exact match. But you have the general search!
> 2. Download and open and scream! What are all these fields!?!?!
	data files and master spreadsheet: https://goo.gl/gyRwx7
- Open downloads in text editor
- Open downloads to view in excel
- What is weird about the datasets? how are they different and explain differences.
		> What is Json? One output is normalized and one is not. How many decimal places are really good? User defined fields. Why so many identifiers?
		> hide all non-locality fields (how is this iteratively efficient?)
		> now download all things "Ranch". Remember to select only those with geocoordinates are present (limit by Armstrong Co.).
> duplicates when you are sorting, why? Thats because this is specimen records

test

###Publishers Page
*  Our Data: Collections. Be sure you are represented.
*  Our Data: Publisher recordset
*  Our Data: API
 (breakout group?): The added benefits of having your data in iDigBio:

###Research Tools:
* PhyloJive
* Tutorial: http://phylojive.acis.ufl.edu/PhyloJive/Tutorial.jsp

*PhyloJive video demo:
http://idigbio.adobeconnect.com/p42g9c33loj/
http://phylojive.acis.ufl.edu/PhyloJive/ManageTrees.jsp
Try: Pseudopsallus

*LifeMapper
Tutorial: http://lifemapper.acis.ufl.edu/lm/map/tutorial/
Try: Solenopsis invicta Red-imported fire ant
Lifemapper, the SPNHC demo was recorded at: 
https://idigbio.adobeconnect.com/_a1130716096/p8li8yf35x9/?launcher=false&fcsContent=true&pbMode=normal





Previous: [Regular Expressions.](08-regular-expressions.html)