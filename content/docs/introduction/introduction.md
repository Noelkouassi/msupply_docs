+++
title = "Introduction"
description = "Open mSupply Introduction."
date = 2022-03-17T18:20:00+00:00
updated = 2022-03-17T18:20:00+00:00
draft = false
weight = 1
sort_by = "weight"
template = "docs/page.html"

[extra]
lead = "Welcome to Open mSupply for Desktop, Web & Android!"
toc = true
top = true
+++

## History

Open mSupply builds on over 20 years of mSupply, over which time it has become the most used Logistics Management Information System (LMIS) in low & middle income countries.

## What platforms are supported?

Open mSupply runs on Desktop (Windows, Linux & Mac), as a web application in your browser, or also as an Android application (for tablets, not for phones at this stage).

## Where can I download it?

We provide a number of downloads on our [releases page](https://github.com/openmsupply/open-msupply/releases) hosted in our GitHub repository.
The latest version will be shown at the top of the list of releases - we generally recommend using the latest version where possible.

Within each release there is an `Assets` section which has the files you need to install Open mSupply.

### Windows

There are installers built for each release, providing:

- **Server**: which supports either SQLite or postgreSQL and runs as a windows service. The installer name for the server is `omSupply_Server_[version].exe`
- **Desktop**: A windows application which allows you to connect to a running server. The installer name for the server is `omSupply_Desktop_[version].exe`
- **Standalone**: combines the above two; runs a server as a windows service and has a windows application which will connect to it. The installer name for the server is `omSupply_Standalone_[version].exe`
- **Demo**: A pre-configured server installation which does not require a central server to run. The installer name for the server is `omSupply_Demo_[version].exe`

### Android

The android version is distributed as an `.apk` file which you can install. This file has the name `open-msupply-[version]-release.apk`

### MacOS

For the mac desktop version, we provide a `.dmg` file, which has the name `omSupply_[version].dmg`.

## What does it do?

In short, Open mSupply manages your inventory, recording every receipt and issue of goods, and thereby providing a running balance of your stock on hand of each item.

Open mSupply does much more than that. Features include:

- Inventory management
  - Easily see per-batch stock on hand
  - Manage shelf locations for your store/warehouse
  - Assign locations to incoming stock, or change locations as you rearrange stock in your warehouse
  - Perform stocktakes, and assign reasons for inventory adjustments
- Receive and fulfil orders from customers (facilities you supply)
- Place orders with your supplying store
  - Quantify amounts required based on simple or complex formulas
  - Track order status as your supplying store fulfils and ships the order!
  - Receive goods into stock when the order arrives
- Be alerted to low stock levels from the dashboard

## What makes mSupply special?

There are a lot of systems that manage inventory. Open mSupply has unique features that make it ideal to use for health supply chains in low resource settings:

- **Offline first**: mSupply is designed from the ground up to work without internet. We know from 20 years of experience that even the most reliable internet connections sometimes fail or get overloaded. mSupply allows you to work without having to worry about second-by-second internet quality. Of course, when you need to place orders or receive updates from other facilities, you need internet for a few minutes then.
- **Scalable**: We've designed Open mSupply to handle billions of transactions a year, but to also work on an Android tablet! You can implement mSupply in one facility, knowing that if you later decide to deploy thousands of sites, mSupply will still be the right tool.

To get some insight into the full breadth of mSupply's functionality, have a look at the legacy mSupply software documentations at [https://www.msupply.org.nz](https://www.msupply.org.nz) - it's almost 1000 pages if you print it all (so maybe don't ☺️)

### Terminology

The following table outlines some of the common terms used in mSupply, and also guides users of legacy mSupply regarding terminology improvements we have made.

| Open mSupply Term |  Legacy mSupply term  | Definition                                                            |
| :---------------: | :-------------------: | :-------------------------------------------------------------------- |
| Outbound Shipment |   Customer Invoice    | The creation of a supply of goods to a particular customer (facility) |
| Inbound Shipment  |   Supplier Invoice    | The receiving of a supply of goods from a particular supplier         |
|    Requisition    | Customer Requisitions | An order for supply of goods made by a particular customer (facility) |
|  Internal Orders  | Supplier Requisitions | A request for stock made for a particular supplier (facility)         |

## Getting Started

If you are running the server for the very first time, you may see this screen:

![Initialisation](/docs/introduction/images/initialisation.png)

Don't panic! This simply means that the server needs to know how to connect to the central mSupply server. If you don't know what to enter, contact support and they can help.
