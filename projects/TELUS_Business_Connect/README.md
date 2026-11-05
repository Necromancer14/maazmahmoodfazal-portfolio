# TELUS Business Connect: order processing

HachiAi, telecom.

[Back to portfolio](../../README.md)

## Problem

Order processing meant validating and re-entering customer and order data across several systems by hand, which caused errors and long turnaround times.

## What I built

A UiPath automation on REFramework that:

1. Reads customer and order data from emails and Excel.
2. Validates it and creates the order in the internal system through APIs.
3. Sends response files and email confirmations, with dynamic subjects for auto-replies.

Error handling and retries are built into the framework.

## Result

- Process efficiency went from **70% to 97%**
- Average handling time per order went from **15 minutes to 3**
- Manual intervention fell by **60%**

## Stack

UiPath, REFramework, APIs, Excel, Outlook
