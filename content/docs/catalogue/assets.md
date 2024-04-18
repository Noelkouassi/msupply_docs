+++
title = "Assets"
description = "Viewing assets."
date = 2022-03-19T18:20:00+00:00
updated = 2022-03-19T18:20:00+00:00
draft = false
weight = 52
sort_by = "weight"
template = "docs/page.html"

[extra]
lead = "Managing your assets"
toc = true
top = false
+++

Assets in Open mSupply is a digital register to manage the creation and maintenance of assets. It allows health departments to keep track of, manage and maintain their assets.

From the **Assets** menu, you can view all of the assets currently in your store.

### Viewing Asset List

In the navigation panel, tap on 'Catalogue' > 'Assets' to show the asset list:

![Assets nav](/docs/catalogue/images/assets.png)

You can see all the assets which are available in your store:

The asset list is divided into 6 columns:

| Column            | Description                                                |
| :---------------- | :--------------------------------------------------------- |
| **Sub catalogue** | The catalogue this asset belongs to                        |
| **Code**          | The code of the catalogue item which this asset belongs to |
| **Type**          | The type of asset                                          |
| **Manufacturer**  | The manufacturer of your asset                             |
| **Model**         | The model number of the asset                              |
| **Class**         | The class of asset. ie: `Cold chain equipment`             |
| **Category**      | The subcategory of the asset                               |

![Assets page](/docs/catalogue/images/assets_page.png)

The list can display a fixed number of patients per page. On the bottom left corner, you can see how many assets are currently displayed on your screen.

![Page](/docs/distribution/images/os_list_showing.png)

If you have more assets than the current limit, you can navigate to the other pages by tapping on the page number or using the right of left arrows (bottom right corner).

![Page](/docs/distribution/images/os_list_pagenumbers.png)

You can also select a different number of rows to show per page using the option at the bottom right of the page.

![Rows per page](/docs/introduction/images/rows-per-page-select.png)

To add a filter to the page, choose the required filter from the drop down. Multiple filters can be combined.

Assets can be selected and deleted using the toolbar action:

<p align="center">
    <img src="/docs/catalogue/images/assets_delete.png" width="425" height="400">
</p>

### Importing And Exporting

#### Import

Assets can be imported from a csv file using the 'Import' button

![Assets nav](/docs/catalogue/images/assets_import.png)

This will open an import modal.

<p align="center">
    <img src="/docs/catalogue/images/assets_import_modal.png" width="750" height="420">
</p>

An example template comma-separated-value (csv) is available for download here:

<p align="center">
    <img src="/docs/catalogue/images/asset_import_template.png" width="750" height="420">
</p>

Data will need to be converted into the format of the csv template provided in order for Open mSupply to be able to process and upload this data.

A csv file can be uploaded once it has been created in the example format.

#### Export

Asset can be exported as a csv using the 'Export' button

![Assets nav](/docs/catalogue/images/asset_export_button.png)

### Managing status log reasons

Status log reasons can be managed using this button

![Assets nav](/docs/catalogue/images/manage_reasons_button.png)

Status log reasons can be added and deleted for a particular status here. These reasons can be added to a status log for additional context for why there is a new functional status.

![Log Reasons page](/docs/catalogue/images/manage_log_reasons.png)

#### Managing log reasons

On this page you can:

- Create new log reasons through the 'Create log reason' button

<p align="center">
    <img src="/docs/catalogue/images/reasons_create_button.png" width="400" height="300">
</p>

This will open a create new reason modal

<p align="center">
    <img src="/docs/catalogue/images/reasons_create_modal.png" width="500" height="350">
</p>

- Select and delete existing reasons with the 'Actions' dropdown

<p align="center">
    <img src="/docs/catalogue/images/reasons_delete.png" width="400" height="350">
</p>

- Filter existing reasons by status using the filter dropdown

<p align="center">
    <img src="/docs/catalogue/images/reasons_filter.png" width="550" height="300">
</p>
