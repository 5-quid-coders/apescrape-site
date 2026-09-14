---
title: 4. Collecting Your First Data
layout: help_article
---

# Collecting Your First Data

## Step 1: Create a Workspace
A **Workspace** is where you and your team keep your work. If you don't have one yet, click **New Workspace** and give it a name. For more on workspaces and inviting teammates, see [this guide](./8teams.html).

## Step 2: Create a Collection
Open your Workspace and click **New Collection**. Give it a name. This is how it will appear in your list of Collections.

Optionally, set a **schedule** (a cron expression) if you want this Collection to run automatically on a recurring basis. You can leave this blank and run it manually instead.

## Step 3: Add a Query
A **Query** tells the Collection what data to collect. Create a Query and add your **Fields**:

1. Enter a **field name**. This becomes a column of collected data.
2. Enter a **description** of exactly what data you want for that field. See [this helpful guide](./4criteria.html) for tips on writing good descriptions.
3. Repeat to add as many fields as you need.

If you want duplicate records merged, set one or more fields as **deduplication keys**.

## Step 4: Add a Source
A **Source** tells the Collection where to collect data from. Create a Source and enter:

1. A **name** for the website.
2. The **URL** of the site you want to collect from.

ApeScrape reads through the site for you. You can add as many Sources as you need. See [this guide](./5datasource.html) for more detail.

## Step 5: Start a Run
Open your Collection and click **Start New Run**. ApeScrape will crawl your Sources and extract data using your Query.

## Step 6: View Your Data!
When the Run finishes, open it to see all the records ApeScrape has collected for you. Congratulations, you just collected your first set of data!
