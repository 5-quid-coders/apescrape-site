---
title: 5. Viewing Your Data
layout: help_article
---

# Viewing Your Data

Once a **Run** finishes, ApeScrape organises everything it found into clean, structured **records**.

To see them, open the **Run** you started. Each Query in your Collection gets its own table of **combined records**, with a column for every field in your schema and a count of how many records were found.

The records table is:

- **Sortable**: click a column header to sort by that field.
- **Paginated**: browse large result sets a page at a time.
- **Deduplicated**: records that share your deduplication keys are already merged into a single row.

## Re-running deduplication

If you change your deduplication keys after a Run, open the Run and use **Re-Deduplicate Run** under **Developer Options** to merge your records again with the updated keys, with no need to crawl the sites a second time.

Congratulations, your data is ready to explore!
