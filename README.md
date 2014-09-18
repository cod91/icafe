ICAFE
=====

ICAFE is a Java library for reading, writing, converting and managing images.

Reading format support:
----------------------
- Windows BITMAP
- CompuServe GIF
- ZSoft's PCX
- Truevision TGA
- Portable Network Graphics - PNG

Writing format support:
-----------------------
- Windows BITMAP
- CompuServe GIF
- JPEG
- Adobe TIFF
- Portable Network Graphics - PNG

Image convertion and management support:
----------------------------------------
- Image conversion to any of the supported format
- Multipage TIFF support
  * Create multiple page TIFF from a series of BufferedImages
  * Split multiple TIFF image to individual images in TIFF format without decompression
  * Insert and remove pages to and from multiple page TIFF etc.
- Animated GIF support
  * Create animated GIF from a series of BufferedImages
  * split animated GIF to individual images in any of the supported writing formats - keeping transparency etc.
- JPEG and TIFF thumbnail support
   * Insert thumbnails into JPEG image
   * Remove thumbnails from JPEG image
   * Extract thumbnails from JPEG (the extracted thumbnail is either in JPEG or TIFF format depending on whether or not it is in JPEG or Raw format and the inserted thumbnail could be completely different from the original image)
- JPEG EXIF data manipulation
   * Inserte EXIF data into JPEG
   * Extract EXIF data from JPEG
   * Remove EXIF data and other an significant APPn segments from JPEG
- JPEG ICC Profile support
   * Inserte ICC profile to JPEG
   * Extract ICC profile from JPEG

Go to the [wiki] page to see this library in action!

[wiki]:https://github.com/dragon66/icafe/wiki