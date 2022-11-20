---
title: Technical Documentation
layout: about
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

| Element Name | DC Mapping | Obligation | Cardinality | Visible? | Description| 
|--------------|------------|------------|-------------|-------------------|------------|
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
- Description: 