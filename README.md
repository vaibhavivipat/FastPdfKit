# FastPdfKit

This repository contains the FastPdfKit iOS library with some sample projects. This library allows you to add some of the features of the FastPdf application to your own app, allowing it to support pdf documents. For more information, see the [FastPdfKit website](http://fastpdfkit.com) and the [Support website](http://support.fastpdfkit.com).

### Update 3.0 (November 4th, 2011)* Internal changes of the view hierarchy to provide more flexibility and overlay transitions.* Revamped `ReaderViewController` user interface.* Better thumbnail scroll view and generation.* Added support to video overlay control parameters in the uri.* Search now works for terms of unitary length.* Added a method to retrieve annotations from the document and provide them as overlays.* Slightly changes to `MFDocumentViewControllerDelegate` callbacks.
* New activation method with key *FPKLicenseKey* from *Info.plist*: no need to pull to get the activated version.

### Update 2.1.3 (September 27th, 2011)

Disabled the 2.1.1 font cache due to an implementation oversight. Will be re-introduced as soon as it will behave as expected.

### Update 2.1.2 (September 21th, 2011)
* Cleaned up text search and extraction a little bit. More fixes incoming.

### Update 2.1.1 (September 15th, 2011)
* Added a font cache system for text extraction and search, which should give sensible improvement in search speed especially on documents with a large amount of different fonts.

### Update 2.1.0 (September 14th, 2011)
* Added Overflow page mode to previous Single and Double. Basically, the pdf page will now fill the screen along its width, overflowing under the bottom of the screen if necessary.
* Added autoMode property. It will tell the MFDocumentViewController to what mode switch when in landscape if automodeOnRotation is YES. Default is MFAutoModeDouble, other option are MFAutoModeSingle and MFAutoModeOverflow.

### Update 2.0.3 (August 10th, 2011)
* Fixed a bug in the transformation returned on double page mode for page with an angle not equal to 0.
* Added guard to iOS 4.x only methods.

### Update 2.0.2 (August 09th, 2011)
* Added support to link annotation with Remote Go-To actions.
* Updated manual with latest methods.
* Added methods to convert points and rect to and from different coordinate systems. Take a look at the MFDocumentViewController for details.
* Documented the method to get the cropbox and rotation angle for each document page.
* Finally fixed the bad behavior of the detail (tiled) view on retina device.
* Fixed a bug involving rendering of the preview pages at low res on retina display introduced a few updates ago.
* The -didGoToPage callback is now called once when a page is changed on user scroll input.

### Update 2.0.1 (July 21th, 2011)
* Bleeding of the pdf cover images fixed.
* The embedded UIWebView is now embedded a bit better.

### Update 2.0.0-devel (July 12th, 2011)
* Multimedia support
* Reorganized project
* Many other improvements

If you have any other question please post it in the [Support Site](http://support.fastpdfkit.com)

