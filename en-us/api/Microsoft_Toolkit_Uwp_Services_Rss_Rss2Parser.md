---
permalink: /en-US/api/Microsoft_Toolkit_Uwp_Services_Rss_Rss2Parser.htm
title: Microsoft.Toolkit.Uwp.Services.Rss.Rss2Parser API 
description: API page for Microsoft.Toolkit.Uwp.Services.Rss.Rss2Parser
keywords: windows, app, toolkit, UWP, API
layout: default
search.product: eADQiWindows 10XVcnh
---


# Rss2Parser class

Rss reader implementation to parse Rss content.

## Members

The **Rss2Parser** class has this types of members

* [methods](#methods)

* [fields](#fields)

### methods

#### LoadFeed(System.Xml.Linq.XDocument doc)

This override load and parses the document and return a list of RssSchema values.

##### parameters



| name | description | type |
#### ParseItem(System.Xml.Linq.XElement item)

Parses XElement item into strong typed object.

##### parameters



| name | description | type |
#### ParseRDFItem(System.Xml.Linq.XElement item)

Parses RSS version 1.0 objects.

##### parameters



| name | description | type |
#### ParseRssItem(System.Xml.Linq.XElement item)

Parses RSS version 2.0 objects.

##### parameters



| name | description | type |
#### GetItemAuthor(System.Xml.Linq.XElement item)

Retrieve item author from item.

##### parameters



| name | description | type |
### fields

#### NsRdfNamespaceUri

RDF Namespace Uri.

#### NsRdfElementsNamespaceUri

RDF Elements Namespace Uri.

#### NsRdfContentNamespaceUri

RDF Content Namespace Uri.