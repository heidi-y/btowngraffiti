---
title: Technical Documentation
layout: page
permalink: /technicaldoc.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---



# Technical Documentation 
Here you'll find information about the way this collection is organized. You can use this page to better understand how to navigate and interact with the collection. You can also use this page to add new pieces to the collection properly as you document your own changes to the Warehouse in Bloomington!

## Context, Content, and Users

The context of this metadata scheme is that is has been designed by Heidi Yarger, a student of library science and folklore who has a research interest in street art and graffiti, specifically in relation to questions of space, time, and representation of identity. The content of the collection is 50 images of graffiti art that surround The Warehouse on the <a href="https://bloomington.in.gov/parks/trails/b-line-trailanchor"> B-Line Trail</a> in Bloomington, Indiana.  

Time of creation and graffiti writer's identity (legal name) is unknown in most cases. With that in mind, information regrading the date of each photograph is provided so that users can have a reference point to compare any changes that may occur to the art around the Warehouse. Additionally, someone that visits the Warehouse frequently may be able to estimate a window of time when a particular piece was created. Information about the pieces focuses primarily on observable aspects of the work including style and form. Creator information is provided when known is and given in the form of the writer's tag, the crew name the writer belongs to (if applicable), and/or the Instagram handle of the writer. 

It is also important to note that there is a certain curatorial aspect to  this collection as not all graffiti around the Warehouse has been chosen for inclusion in this library. See the {% include feature/button.html text="Why Graffiti Section" link="https://heidi-y.github.io/collectionbuilder-draft/whygraffiti.html" color="success" %} for more details!

## Metadata Scheme Information 

| Element Name | DC Mapping | Obligation | Cardinality |    Visible?       |    Description| 
|--------------|------------|------------|-------------|-------------------|---------------|
| Objectid | Identifier | required | 1 | no | Required identifcation element for CollectionBuilder |
| Filename | Description | required | 1| no | Required identfication element for CollectionBuilder | 
| Title | Title | required | 1 | yes | Title of the piece | 
| Format | Format | required | 1| yes | Format of the image | 
| Location | Location | required | 1| yes | Location on the building | 
| Creator | Creator | required if available | 1 or more | yes | Graffiti writer/artist name and/or crew name | 
| Subject | Subject | required when applicable | 1 or more | yes | Style of piece (see glossary) | 
|Form | Description | Not required | 1 or more | yes | Descripition of style of piece | 
|Relation | Relation | Required if available | 1 or more | yes | Relation to other pieces in the collection | 
|Date | Date| required | 2| yes | Date of photo and date of piece (when applicable) | 
|Rights | Rights | required| 1 | yes | Rights statement indicating the rights of the artists and fair use | 
|Genre | Type| not required | 1 or more | yes | Type of visual work presented | 
||||||

## Content Guidelines 

**Objectid**  
- Description: According to CollectionBuilder (CB) Guidelines, the Ojectid is the field used to identify each object within CB. 
- Formatting: The Objectid must be a unique string, all lowercase, with no spaces or special characters. Underscores and dashes are okay, but slashes are not. For the purposes of this collection, each Objectid beging with "ware" and ends with a unique string of numbers, ascending from 000 onward. 
- Examples: ware001, ware002, ware 003 

**Filename** 
- Description: According to CB guidelines, the filename should be an all lowercase unique string with no spaces or special characters. 
- Formatting: For the purposes of this collection, filenames will directly correspond to Objectid numbers, so thtat the item with Objectid ware001 has the filename ware_001.jpg 
- Examples: ware_001.jpg, ware_002.jpg, ware_003.jpg 

**Title** 
- Description: Each item may have only one title. The title should be unique, succinct, and descriptive. As this collection is composed of graffiti pieces and murals, most pieces do not have allocated titles. Research on the knowledge organization of graffiti collections show that the most common way to organize graffiti pieces is by artist name. 

-Formatting: Most items in the collection are photos of the artists' stylized representation of their name with spray paint (tag name). If you are unsure about the word that is represented in graffiti lettering, look to other items by the artist in the collection for reference. Additionally, look for subtitles or phrases written next to the artist's signature. If you are still unsure, write 'unknown'. All graffiti pieces that use a tag name as their title should be followed by a number (#1, #2, #3) even if you are labeling the first instance of a piece by a given artist. This will allow for proper categorizing of new pieces as they emerge on the Warehouse. 

- Examples: BRISK #1; BRISK #2; BRISK #3

**Format**

- Description: Another required CB field, this field indicates the object file format. All items in this collection are jpeg images. 

- Formatting: Type and subtype seperated by /

- Examples: image/jpeg 

**Location** 

- Description: All items in the collection are in the same location, the exterior walls of the Warehouse at 1525 S. Rogers Street, Bloomington, IN. However, works appear on different parts of the exterior Warehouse building. 

- Formatting: Location information should indicate where on the building the work appears and indicate the wall (front, back, right, or left) followed by the location on the wall (left, right, center). Values are seperated by a /

- Examples: back/center 

**Creator** 

- Description: The creator field indicates the wrtier who created the graffiti piece. The name used should be the writer's tag name, even if their legal name is known. In some cases, a work has been created by a Graffiti Crew. When known, the cretor field should reflect crew affiliation. If a work is signed, use the name the the work has been signed with. In some cases, the graffiti writer may indicate their Instagram handle. In these instances, both the tag name and the handle should appear in the creator field.

- Formatting: Crew names should appear first and are followed by a ; symbol. Crew member names are listed in alphabetical order. Tag names should be written as they appear on the work. Instagram handles follow tag names and are seperated by a ; symbol and begin with a @ symbol. Unknown creators are marked 'unknown'. 

- Examples: Act Crew; Jet One, Total Fun, Ulcer Storm
cilhaos; @cilhaos 

**Genre** 

- Description: Type terms come from <a href="https://www.getty.edu/research/tools/vocabularies/aat/">The Getty Art and Architecture Thesaurus </a>, the <a href="https://americanfolkloresociety.org/resources/afs-ethnographic-thesaurus/">AFS Ethnographic Thesaurus </a>, and the <a href="https://www.loc.gov/pictures/collection/tgm/">Thesaurus for Graphic Materials </a>. Type terms are used to catgorize the broad artistic type that the artwork falls under as well as the topics that relate to the items in the collection. 

-Formatting: Terms should be seperated by a ; symbol

-Examples: street art; urban art; graffiti; graffiti art

**Subject** 

- Description: This field indicates the **graffiti style** that the piece that the piece is created in. Information for style classification is taken from Lisa Gottlieb's classification system. A link to her text is found at the bottom of this document. Additionally, see the glossary for descriptions of each style. 

- Terms should be seperated by a semi-colon 

- Examples: Semi-wild 

**Form** 

- Description: This field is used to indicate the form of the graffiti art. Form categories are taken from Lisa Gottlieb's *Graffiti Art Styles*. See the end of the document for a link to her text. Descriptive categories to consider include linerarity, use of arrows, symmetry, letter storkes, fill consistency, number of colors present, letter shape consistency, fill effects, negative space, legibility, letter outlines, letter overlap, and dimensionality. Definitions are found in Lisa Gottlieb's text. 

- Formatting: Terms should be identified from applicable resources. Descriptions should be written in brief and complete sentences. Note: You do not need to input information for every possible descriptive category. Choose three to four that are clearly visible to you. 

- Examples: This is a 2-dimensional piece with curved lineraity and interlocking letters. This piece is illegible. 

**Relation** 

- Description: The relation element is used when applicable to denote when a work has a significant relationship to another work. For example, when one piece has been covered up by another piece, or when pieces seem to be apart of a series. 

- Formatting: Relation is indicated by the title of the related work, multiple related works values are seperated by a ; 

- Examples: Moosey #1; Moosey #2 

**Date**

- Description: Dates should be given to indicate the date that the photo was taken in every case. If the piece is signed and dated, that information should be provided. If you observe a new piece in a distinct window of time (for example, you visit the Warehouse on Saturday November 19th and go back on Sunday November 20th and see a brand new piece) you may also indicate that here. 

- Formatting: All dates should appear in yyyy-mm-dd format. All photo dates will follow this format. For pieces that are signed with less specific date information (e.g. yeear only), follow yyyy-mm or yyyy formatting. When availble, date of the piece appears first, followed by photo date. Date values are seperated by a ; 

- Example: 2022; 2022-09-29 

**Rights** 

- Description: All items in the collection should use the same rights statement to indicate the rights of the artist. 

- Formatting: The items in this collection fall under a Creative Commons License. Educational use, including non-commercial use of the text and images for research and teaching purposes is permitted. All rights to the designs represented in this collection rest with the artists and any reuse or reproduction of their work is not permitted under any circumstances. 

**Important Reference Works** 

Gottlieb, Lisa. (2008) *Graffiti art style: a classification system and theoretical analysis.* Jefferson, N.C.; McFarland. 
 <a href="https://www.worldcat.org/title/228608106">World Cat entry </a>

{% include feature/image.html objectid="https://raw.githubusercontent.com/heidi-y/collectionbuilder-draft/main/assets/img/graffitistyles.jpeg" width="75" alt="Graffiti Art Styles Cover" caption="This book is a must have for this collection!"%}

 Graf, Ann M. 2020. “Domain Analysis Applied to Online Graffiti Art Image Galleries to Reveal Knowledge Organization
Structures Used Within an Outsider Art Community.” Knowledge Organization 47(7): 543-557. 34 references. DOI:10.5771/0943-7444-2020-7-543.

