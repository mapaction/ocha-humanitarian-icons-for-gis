# How to install the humanitarian icons in QGIS 3.10 and above
<img src="https://github.com/mapaction/ocha-humanitarian-icons-for-gis/blob/humanitarian-icons-v2/documentation/images/qgis-logo.jpg" alt="QGIS Logo" width="150" align="right" >The following instructions will take you through installing the icons to use in QGIS 3.10 and above (though they should also work for earlier versions).

There are two options available. The font method is more flexible - you can change the colour for example, but users and end users will be required to install the font (unless the font has been embedded in the map). The SVG version will overcome those issue but the colours cannot be adjusted.

You can only use one of the options at one time (unless you manually change the name of each symbol) - i.e. installing the SVG symbols will overwrite the font symbols. However even if you only use the font symbols, you can still download the SVG images and use them in your maps.

## You will need
For the Font method
* The humanitarian icons font
* The .xml file

For the SVG method
* The SVG files
* The .xml file

## Installation for the font method
### Download
1. Download the .ttf font - [Humanitarian-Icons.ttf](https://github.com/mapaction/ocha-humanitarian-icons-for-gis/raw/humanitarian-icons-v2/humanitarian-icons-v2-1-font/Humanitarian-Icons.ttf).
2. Download the .xml style file - [QGIS humanitarian-icons-v2-1-qgis-ttf.xml file](https://github.com/mapaction/ocha-humanitarian-icons-for-gis/raw/humanitarian-icons-v2/humanitarian-icons-v2-1-qgis/humanitarian-icons-v2-1-qgis-ttf.xml).

### Install the font
3. Double click on the font to open the font (do this before opening QGIS).
4. Click install font and let it install to the default location.

### Install the .xml file
5. Open QGIS.
6. Go to Settings > Style Manager > Import/ Export > Import Items(s)
7. Navigate to the .xml file and click OK. 
8. On doing so the icons will appear in the dialogue box.
9. Click Select All, or click on the individual icons you want. In either case the icons will be highlighted.
10. If required, add tags in 'Additional Tag(s)' - but note that all symbols already have specific tags as well as the tag 'humanitarian icons'.
11. When ready click Import.
12. Click 'yes' to overwrite any existing symbols with the same name.
13. They will be loaded, and you can then check that they have correctly loaded in the Style Manager dialogue box.

## Installation for the SVG method
1. Download the .svg files - [SVG files](https://github.com/mapaction/ocha-humanitarian-icons-for-gis/raw/humanitarian-icons-v2/humanitarian-icons-v2-1-svg/humanitarian-icons-v2-1-svg.zip).
2. Download the .xml style file - [QGIS humanitarian-icons-v2-1-qgis-svg.xml file](https://github.com/mapaction/ocha-humanitarian-icons-for-gis/raw/humanitarian-icons-v2/humanitarian-icons-v2-1-qgis/humanitarian-icons-v2-1-qgis-svg.xml).

### Save the SVG files
3. Copy the folder into an SVG folder which is referenced in Settings > Options > System > SVG paths. In Windows, this will normally be C:\Users\[user_name]\AppData\Roaming\QGIS\QGIS3\profiles\default\svg - you may have to create the folder. Keep the folder name as is, as it's referenced in the style file.

### Install the .xml file
4. Open QGIS.
5. Go to Settings > Style Manager > Import/ Export > Import Items(s)
6. Navigate to the .xml file and click OK. 
7. On doing so the icons will appear in the diaglogu box.
8. Click Select All, or click on the individual icons you want. In either case the icons will be highlighted.
9. If required, add tags in 'Additional Tag(s)' - but note that all symbols already have specific tags as well as the tag 'humanitarian icons'.
10. When ready click Import.
11. Click 'yes' to overwrite any existing symbols with the same name.
12. They will be loaded in and you can then check that they have correctly loaded in the Style Manager dialogue box.

<img src="https://github.com/mapaction/ocha-humanitarian-icons-for-gis/blob/humanitarian-icons-v2/documentation/images/qgis-style-manager.jpg" alt="QGIS Style Manager" width="95%" align="centre" >

## Note
The icons have been created and tested in QGIS 3.10 (the current LTR) but should work in earlier versions of QGIS too.

## Further guidance
* [QGIS - The Style Manager Help](https://docs.qgis.org/3.10/en/docs/user_manual/style_library/style_manager.html).
