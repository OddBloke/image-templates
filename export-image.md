---
copyright:
  years: 2014, 2018
lastupdated: "2018-03-13"
---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# Exporting an image

From the Image Templates page you can export an image template to an Object Storage account. 
{:shortdesc}

The image export process takes a preexisting, private standard image template and coverts the image into an 
image file that is stored in a specified location on an Object Storage account. Use the following steps to export an image template.

1. From the **Devices** menu in the [{{site.data.keyword.slportal_full}} ![External link icon](../../icons/launch-glyph.svg "External link icon")](https://control.softlayer.com/), select **Manage > Images**.
2. Click **Actions** for the image template that you want to export and select **Export Image**. If an image template with the configuration that you want is not yet 
available, see [Creating a Standard Image](create-standard-image.html).
3. On the Export Image page, enter the file name for the image in the **File Name** field.
5. From the **Account** drop-down list, select an **Object Storage Account**.
6. From the **Cluster** drop-down list, select an **Object Storage Cluster**.
7. From the **Container** drop-down list, select an **Object Storage Container**.
8. Click **Export Image** to export the image to the specified location in the Object Storage Account. Click **Close** to cancel 
the action.

## Next Steps

After you export an image, the image remains in the list of image templates, but it is also available as a file in the Object Storage 
location that was specified during the export process. For more information about viewing a file that was
exported to an Object Storage Account, see [Viewing and Editing Object Storage File Details](/docs/infrastructure/objectstorage-swift/view-and-edit-object-storage-file-details.html). Because each image is a different size and has different characteristics, the export process might 
take several minutes before it completes. The average export speed is 2 GB / minute. If several minutes lapse and the image is still not 
available on the Object Storage Account, [Contact Support](/docs/get-support/howtogetsupport.html).

