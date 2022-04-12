+++
title = "Items"
description = "Viewing items."
date = 2022-03-19T18:20:00+00:00
updated = 2022-03-19T18:20:00+00:00
draft = false
weight = 2
sort_by = "weight"
template = "docs/page.html"

[extra]
lead = "Managing your catalogue"
toc = true
top = false
+++

In the **Items** menu, you can all the items that are currently visible to your store. 

## Viewing items list

In the navigation panel, tap on `Catalogue` > `Items` to show the items list: 

![](/docs/catalogue/cat_gotoitems.png)

You can see all the items used by your store: 

![](/docs/catalogue/cat_itemslist.png)

## Viewing an item's details 

To view the details of an item, simply tap on one. A new window opens: 

![](/docs/catalogue/cat_itemdetail.png)

On top of the screen, you can the following information:
* **Stock on Hand**: how much stock currently available in your store for this store. 
* **AMC**: Average Monthly Consumption. This is how much stock your store uses each month on average (based on a configurable number of months, defaults to 3 months). 
* **Months of Stock**: number of months of consumption left with current stock. This is calculated as: `Stock on Hand / AMC`

<div class="imagetitle">
In below example, we have 1542 units of Amoxicillin available in our store. The average consumption is 53.3  units per month which means that there is the equivalent of 28.9 months of stock in the inventory. 
</div>

![](/docs/catalogue/cat_itemdetailsheaders.png)

In the bottom part, item details are divided into several sections:

### Details

* **Name**: this is the name by which mSupply will refer to the item.
* **Code**: this is the code assigned to this item in mSupply. 
* **Unit**: the unit you use for this item. It is useful to distinguish items you issue by pack (eg. eye drops) from items you issue by volume (eg. oral liquids)
* **Strength**: for a medicine, the concentration of its active ingredients (eg. for Amoxillin 250mg, the strength is 250mg)
* **Defined Daily Dose**: The assumed  average maintenance dose per day for a medicine used for its main indication in adults.  
* **Doses**: for vaccines, the number of dose per vial. 
* **Vaccine** (check box): if this is checked, this item is a vaccine and a number of dose can be assigned.

### Categories

* **ATC Category**: ATC stands for Anatomical, Therapeutic, Chemical and is a method of classifying entities, and identifying them by category. 
* **Universal Name**: 
* **Universal Code**:  

### Packaging

* **Default pack size**: This is the default pack size that will be assigned to incoming stock as it is received. 
* **Outer pack size**: The number of units in a carton (outer pack). Not the number of preferred pack size packs in a carton (outer pack).
* **Volume per pack**: The default volume per preferred pack size pack. This is the volume that will be used by default when receiving goods. We recommend you divide a carton volume by the number of preferred pack size packs in a carton to get this figure. mSupply always stores volumes in m3 (cubic metres), but you can enter a volume as millilitres (ml) or litres (l) by entering the appropriate abbreviation after the number representing the volume. e.g. enter “0.5l” to enter a volume of 0.5 litres (= 0.0005m3).
* **Volume per outer pack**: The default volume of an Outer pack size pack of this item.
* **Weight**: The weight of a preferred pack size pack in kg.

### Pricing

* **Margin**: This is the default margin that will be applied to this item on Inbound Shipments to calculate the selling price. 