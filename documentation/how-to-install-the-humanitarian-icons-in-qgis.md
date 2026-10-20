# How to install the humanitarian icons in QGIS 3.10 and above
<img src="https://github.com/mapaction/ocha-humanitarian-icons-for-gis/blob/humanitarian-icons-v3/documentation/images/qgis-logo.jpg" alt="QGIS Logo" width="150" align="right" >The following instructions will take you through installing the icons to use in QGIS 3.10 and above.

The symbols use the font, so you can change the colour and size, but everyone who opens your project needs the font installed (unless the font has been embedded in the map). The SVG files are provided if you want the icons as pictures; there is no SVG based style file in this version.

## You will need
* The humanitarian icons font
* The .xml file

## Installation
### Download
1. Download the .ttf font - [Humanitarian-Icons.ttf](https://github.com/mapaction/ocha-humanitarian-icons-for-gis/raw/humanitarian-icons-v3/humanitarian-icons-v3-font/Humanitarian-Icons.ttf).
2. Download the .xml style file - [humanitarian-icons-v3-qgis-ttf.xml](https://github.com/mapaction/ocha-humanitarian-icons-for-gis/raw/humanitarian-icons-v3/humanitarian-icons-v3-qgis/humanitarian-icons-v3-qgis-ttf.xml).

### Install the font
3. Right-click the font and choose Install for all users (do this before opening QGIS).

### Install the .xml file
4. Open QGIS.
5. Go to Settings > Style Manager > Import/ Export > Import Items(s)
6. Navigate to the .xml file and click OK.
7. The icons will appear in the dialogue box.
8. Click Select All, or click on the individual icons you want.
9. If required, add tags in 'Additional Tag(s)' - but note that all symbols already have a tag for their category as well as the tag 'humanitarian icons'.
10. When ready click Import.
11. Click 'yes' to overwrite any existing symbols with the same name.
12. They will be loaded, and you can check them in the Style Manager dialogue box.

<img src="https://github.com/mapaction/ocha-humanitarian-icons-for-gis/blob/humanitarian-icons-v3/documentation/images/qgis-style-manager.jpg" alt="QGIS Style Manager" width="95%" align="centre" >

## The symbols
Each symbol is a font marker, 15 pt and black, with an outer glow layer effect as the halo: white, 50 per cent opacity, spread 0.5 pt.

## Further guidance
* [QGIS - Style Manager](https://docs.qgis.org/latest/en/docs/user_manual/style_library/style_manager.html).
