---
layout: default
title: Changing metadata styles
nav_order: 2
parent: Metadata in Practice
---

In this section we will go over how to change the style of metadata being used for your data in ArcGIS Pro.

## Metadata styles in ArcGIS Pro

ArcGIS Pro provides some additional options for the style of metadata used for your items. These styles can correspond to more common and robust geographic metadata standards such as FGDC and ISO 19115/19139, and aligning your metadata descriptions with a metadata standard can improve its interoperability and discoverability outside ArcGIS Pro.

In the example used so far, our metadata is formatted in the default Item Description metadata style. We can change this style to conform to a more common metadata standard.

There are several common metadata standards available to choose from in ArcGIS Pro, and each one is different. Choosing the right one is an important consideration, however for general discoverability and interoperability purposes, as well as considering data preservation and long-term usability issues, we recommend using **ISO 19139 Implementation Specification**.

Keep in mind that metadata standards allow us to "cross-walk" from one standard to another, making conversions between standards relatively common.
{: .note}

## Change your metadata style

You can change your metadata styles in ArcGIS Pro in your project options:

_1_{: .circle .circle-red} Click on the **Project** tab, then **Options**

_2_{: .circle .circle-red} In the window that pops up, select **Metadata** from the menu on the left.

_3_{: .circle .circle-red} Here you can choose a new metadata style. In this example we'll choose **ISO 19139 Metadata Implementation Specification**

_4_{: .circle .circle-red} Click **OK** and go back to your Catalog window.

## Review the fields in your new metadata style

Now that your project is using a new metadata style, let's look at the new fields it contains.

_1_{: .circle .circle-blue} In your Catalog pane, **right-click** on an item and select **Edit Metadata**. This will open a window showing the _Item Description_ metadata block of ISO 19139.

_2_{: .circle .circle-blue} The Contents pane now shows all of the other metadata blocks for this metadata style. Click on **Citation** to see the resource citation metadata block.

_3_{: .circle .circle-blue} Review some of the other metadata blocks to become familiar with what's there.

ArcGIS Pro displays mandatory metadata fields missing values with a **red X** in the Contents pane. Mandatory fields will change depending on which metadata standard you choose.
{: .warning}

When adding metadata to your items, it's important to keep in mind that not all fields will apply, and metadata standards do not require all fields to be used. So, don't avoid creating metadata because there are so many fields In some cases there are very few required fields. Your task as the steward for your own data is to add values to fields which.
