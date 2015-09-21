# Gist
<a href="images/gist/gist.png" data-lightbox="gist-document" data-title="Gist Editor" style="display: block; float:right;">
  ![alt text](./gist/gist.png "Gist")
</a>

This tool is used port and publish back GitHub gist to and from Vida system. 
It helps developer of any level experiment any gist and see the changes in action. 
The edit view is designed to have similar user experience with a d3 document one. 

**Notes:**

* This is incompatible with Vida d3 document format. 
* This doesn't include most features supported for a d3 document. To fully utilize these feature, consider porting a gist to a Vida-d3 document format.

## Import New

To import a gist, go to **Home / Gist**, select **Import Gist (Block)** from the document list top left menu.
Once successfully imported, the gist edit view will show up with top menu bar, '#canvas-svg' div on the left, the settings and editors on the right.

## Save and Publish to GitHub

When a gist has any changes, the re-rendering will trigger once the document is saved (using 'Save' button or 'Ctrl+Return' shortcut).
This action only saves the document within Vida internal system. To replicate these changes on GitHub, developers need to publish them back.
To publish, follow the following steps:

* Select **Connect to GitHub** button in **Settings** tab, and allow GitHub authentication.
* When connected, click **Select a Gist** dropdown menu option, and select the target gist.
* Click **Push** to complete publishing.