+++
title = "Devices"
description = "Configure devices attached to the system"
date = 2022-05-17T16:20:00+00:00
updated = 2022-05-17T16:20:00+00:00
draft = false
weight = 60
sort_by = "weight"
template = "docs/page.html"

[extra]
toc = true
top = false
+++

The devices settings section allows you to configure devices that you may have connected to the Open mSupply system.

## Viewing the display settings

To view the display settings, go to `Admin` in the lower section of the navigation panel: 

![Admin: nav](/docs/administration/images/admin_nav.png)

You will see the list of admin sections:

![Admin: collapsed](/docs/administration/images/admin_collapsed.png)

click on the `Devices` section to begin.

## Label Printing

The label printing functionality is in an experimental state currently. You can configure a single, network-enabled, label printer which supports the ZPL printer language.

![Label Printing](/docs/administration/images/devices_label_printing.png)

Enter the IP address and other details of the printer. To test your configuration, you can click the `Test` button. This will attempt to connect to the printer and fetch configuration details from it.

If you are happy with the settings, click `Save` to save the details.

## Barcode Scanners

This section allows you to configure a USB barcode scanner for use with Open mSupply desktop.
We support serial-mode and keyboard-mode scanners. The preference is serial scanners which we have found to be more reliable. The Zebra DS-22 is the recommended model.

On opening the barcode scanners section you may see the message `Not connected`:

![Barcode scanner](/docs/administration/images/devices_scanner_not_connected.png)

even though you have a scanner plugged in. The system needs to be instructed that a scanner is available - here's how this is done:

Click the `Detect` button. A barcode will be shown:

![Barcode scanner](/docs/administration/images/devices_scanner_barcode.png)

Scan the barcode with your barcode scanner (this may take a few attempts!). You will see the following notification when successful:

![Barcode scanner](/docs/administration/images/devices_scanner_found.png)

and then the message is changed to the following:

![Barcode scanner](/docs/administration/images/devices_scanner_connected.png)

You are now able to use the barcode scanner!