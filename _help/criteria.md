---
title: Criteria
layout: help_article
---

## Criteria

Apescrape lets you target webpages based on their content, and search those pages for specific information. This is what we call 'Criteria'.

A Criteria has two parts, 'Page Validators' and 'Fields'. The Page Validator is an english description of what qualifies a page as valuable to your search, an example of such a description could be:

`Pages containing information regarding restaurants in Edinburgh`

The Fields of a Criteria describes the specific categories of information you want to extract from webpages, each field has a name and an English description of what sort of data to look for, such as these:

Name: `Restaurant Name`
Description: `What is this restaurant called?`

Name: `Restaurant Type`
Description: `What type of restaurant is this?`

You can also classify a Field as being unique per record, which allows information from multiple pages to be combined based on a common factor. In the previous example, you would mark the restaurant name as being unique so that information about the same restaurant from different sites can be combined.