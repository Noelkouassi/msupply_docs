+++
title = "Dashboard"
description = "Open mSupply Introduction."
date = 2022-03-17T18:20:00+00:00
updated = 2022-03-17T18:20:00+00:00
draft = false
weight = 5
sort_by = "weight"
template = "docs/page.html"

[extra]
lead = "The landing page"
toc = true
+++

## Too many Dashboards!

Yes, we use the term _Dashboard_ for more than one thing.
Open mSupply has a landing page which gives an overview of some statistics, and has some useful links, which we're talking about here, and also a system dashboard that uses Grafana, and gives an overview of all sites in your country (or organisation).

## What's on display?

![The dashboard!](/docs/introduction/images/dashboard.png)

You can see some statistics for shipments and stock:

- Replenishment
  - Inbound Shipments
    - **Today** Shows the number of inbound shipments created today
    - **This week** The number created during the current week
  - Internal Orders
    - **New** Shows the number of new internal orders
- Distribution
  - Shipments
    - **Have not been shipped** The number of outbound shipments that have not been set to `Shipped` (or later) status
  - Requisitions
    - **New** The number of new customer requisitions
- Inventory Management
  - Expiring Stock
    - **Expired batches** The number of stock lines in the current store which have expired
    - **Batches expiring in a month** The number of stock lines in the current store which will expire within the month
  - Stock levels
    - **Total items** A count of the number of items in this store
    - **Items with no stock** The item is visible in this store, but there is no stock recorded
    - **Items with less than 3 months of stock** Which is based on the average monthly consumption (AMC) for this item in the current store
    - **Items with more than 6 months of stock** As above, based on AMC for the item in the current store

As well, there are buttons toward the bottom of the page which allow you to create shipments and requisitions.

