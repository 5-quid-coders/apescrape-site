---
title: 3. Datasources
layout: help_article
---

# Datasources
The **Datasource** is the second component of your **Workflow**. This is where you can list all the websites that you want to collect data from.

For each website you want to include, simply fill in the **Name** field with the name of the website and the **URL** field with the website address.

## Scenario:
Looking for information about **restaurants in Edinburgh** from a set of tourist websites.

### Datasources:

- **Name:**  
  Food in Edinburg
  **URL:**  
  https://www.foodinedinburg.com

- **Name:**  
  Foodie Traveller   
  **URL:**  
  https://foodytraveller.com

- **Name:**  
  Food4Fun   
  **URL:**  
  https://www.food4fun.com


## When to Use Specific Page URLs vs Root URLs?

- **Specific page URLs** should be used **only** if you would like to start crawling a website from a specific point rather than just the home page.
- **Root URLs** should be used in **every other circumstance**

> **Helpful Tip**  
> The root URL of a website starts with `https://` and includes everything before the next `/`.  
> For example, ApeScrape’s root URL is:  
> `https://apescrape.com/`


To quickly add Datasources through **CSV import**, choose the **Import** button located on the Datasource Creation Screen.

![Image showing the exact location of the import CSV button](/assets/import_csv_button.png)

> **Helpful Tip**  
> Once your Datasource is created, you can select it again when making new Workflows to get up and running even quicker—perfect if you're collecting from the same websites repeatedly.
