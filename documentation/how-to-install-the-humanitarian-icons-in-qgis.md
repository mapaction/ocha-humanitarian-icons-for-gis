# How to install the humanitrian icons in QGIS 3.4.4 and above
The following instructions will take you through installing the icons to use in QGIS 3.4.4 and above.

There are two options available. The font method is more flexible - you can change the colour for example, but users and end users will be required to install the font (unless the font has been embedded in the map). The SVG version will overcome those issue but the colours cannot be adjusted.

## You will need
For the Font method
* The humanitarian font
* The .xml file

For the SVG method
* The SVG files
* The .xml file

## Installation for the font method
### Download
1. Download the .ttf font - [Humanitarian-Icons.ttf](https://github.com/mapaction/ocha-humanitarian-icons-for-gis/raw/humanitarian-icons-v2/humanitarian-icons-v2-1-font/Humanitarian-Icons.ttf).
2. Download the .style file - [QGIS .ttf file](https://github.com/mapaction/ocha-humanitarian-icons-for-gis/raw/humanitarian-icons-v2/humanitarian-icons-v2-1-qgis/humanitarian-icons-v2-1-qgis-ttf.xml).

### Install the font
3. Double click on the font to open the font.
4. Click install font and let it install to the default location.

### Install the .xml file
5. Open QGIS.
6. Go to Settings > Style Manager > Import/ Export > Import Items(s)
7. Navigate to the .xml file and click OK. 
8. On doing so the icons will appear in the diaglogu box.
9. Click Select All, or click on the individual icons you want. In either case the icons will be highlighted.
10. Check the final tag settings.
11. When ready click Import.
12. They will be loaded in and you can then check that they have correctly loaded in the Style Manager dialogue box.


## Installation for the SVG method
1. Download the .svg files - [SVG files](https://github.com/mapaction/ocha-humanitarian-icons-for-gis/raw/humanitarian-icons-v2/humanitarian-icons-v2-1-svg/humanitarian-icons-v2-1-svg.zip).
2. Download the .style file - [QGIS .svg file](https://github.com/mapaction/ocha-humanitarian-icons-for-gis/raw/humanitarian-icons-v2/humanitarian-icons-v2-1-qgis/humanitarian-icons-v2-1-qgis-svg.xml).

### Save the SVG files
3. Copy the folder into an SVG folder which is referenced in Settings > Options > System > SVG paths. In Windows, this will normally be C:\Users\[user_name]\AppData\Roaming\QGIS\QGIS3\profiles\default\svg - you may have to create the folder.

### Install the .xml file
4. Open QGIS.
5. Go to Settings > Style Manager > Import/ Export > Import Items(s)
6. Navigate to the .xml file and click OK. 
7. On doing so the icons will appear in the diaglogu box.
8. Click Select All, or click on the individual icons you want. In either case the icons will be highlighted.
9. Check the final tag settings.
10. When ready click Import.
11. They will be loaded in and you can then check that they have correctly loaded in the Style Manager dialogue box.

## Note
The icons have been cfeated and tested in QGIS 3.4.4 but should work in earlier versions of QGIS too.

## Further guidance
* [QGIS - The Style Manager Help](https://docs.qgis.org/3.4/en/docs/user_manual/working_with_vector/style_library.html#the-style-manager).
