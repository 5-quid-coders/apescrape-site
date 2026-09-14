---
title: 2. Queries
layout: help_article
---

# Queries

A **Query** is one of the components that make up a **Collection**. It specifies exactly what data you want to be extracted from web pages.

A Query has two main parts:

- **Fields** (your schema)
- **Deduplication keys**


## Fields (Schema)

Each **Field** describes a specific piece of information you want to extract. A field has a **Name** and a **Description**.

The **Name** is how the field will be referred to when data is collected. Think of it as a column header in a spreadsheet.

The **Description** is a simple, one-sentence English explanation of exactly what the AI should look for on the page.


## Deduplication keys

**Deduplication keys** are used to combine duplicated records. Choose one or more of your fields as deduplication keys, and any records that share the same values for those keys (and don't otherwise conflict) will be merged into a single combined record.


> **Helpful Tip**
> When creating your Fields, picture the spreadsheet you want at the end. The **Name** is the column header, and the **Description** is the type of data that would fill that column.


## Now Let's Put It All Together

### Scenario:
Looking for information about **restaurants in Edinburgh** from a set of tourist websites.

### Fields:

- **Name:**
  Restaurant name
  **Description:**
  What is this restaurant called?

- **Name:**
  Restaurant summary
  **Description:**
  What is a one-sentence summary of this restaurant?

### Deduplication keys:
Set **Restaurant name** as a deduplication key so the same restaurant found on multiple pages is merged into one record.


## How to Make the Most of Your Query

- Be **specific** in your Field Descriptions to avoid confusion between similar data points.
- It helps to look at a few of the pages you want to collect from, so you can phrase your Descriptions to match what's actually on them.
