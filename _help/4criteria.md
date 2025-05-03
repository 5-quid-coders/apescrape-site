---
title: 1. Criteria
layout: help_article
---

# Criteria

The **Criteria** is one of the components that make up a scraping **Workflow**. By specifying Criteria, you can indicate the exact data you want collected.

Let's get started!

A Criteria has two parts:

- **Page Validators**
- **Fields**


## Page Validators

The **Page Validator** is an English description that tells your Workflow whether a page it encounters is relevant to your search.


## Fields

Each **Field** of a Criteria describes the specific type of information you want to extract from web pages. It consists of:

- **Name**
- **Description**

The **Description** is a simple one-sentence English explanation of what data your Workflow should search for.

> **Helpful Tip**  
> When creating your Fields, think of a spreadsheet containing the data output. The **Name** part of the Field will be the column header, and the **Description** will be the type of data that would populate that column.


## Now Let's Put It All Together

### Scenario:
Looking for information about **restaurants in Edinburgh** from a set of tourist websites.

### Page Validator:
**Restaurant in Edinburgh**

> Now let’s say you are looking for the names of the restaurant and their descriptions:

### Fields:

- **Name:**  
  Restaurant name  
  **Description:**  
  What is this restaurant called?

- **Name:**  
  Restaurant type  
  **Description:**  
  What is a one-sentence summary of this restaurant?


## How to Make the Most of Your Criteria

- Be **specific** in the Field Descriptions to avoid confusion between similar data points.
- It is best practice to look at some of the websites you want to collect data from to get familiar with how to best phrase your Descriptions.
- Use the **Unique** indicator on Field items to ensure each value collected is distinct.

  > **Example:**  
  > In our restaurant example, you may want to set the **‘Restaurant name’** field as *Unique* so that if your Workflow finds the same restaurant on multiple web pages, it merges them into a single data point instead of duplicating them.

> **Helpful Tip**  
> Once your Criteria is created, you can reuse it when making new Workflows. This saves time if you want to collect the same types of information from different websites.
