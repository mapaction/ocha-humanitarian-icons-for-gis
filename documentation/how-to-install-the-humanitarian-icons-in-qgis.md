# How to install the humanitarian icons in QGIS 3.10 and above
<img src="https://github.com/mapaction/ocha-humanitarian-icons-for-gis/blob/humanitarian-icons-v2/documentation/images/qgis-logo.jpg" alt="QGIS Logo" width="150" align="right" >The following instructions will take you through installing the icons to use in QGIS 3.10 and above (though they should also work for earlier versions).

There are two options available, font and SVG, You can install one set, or both sets in parallel - each style has a label indicating whehter it is uses a font or an SVG marker. Whichever you install, you can also have the font or SVG markers available for use in your maps, as long as you install the font and download the SVG files.

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
13. They will be loaded (it may take a few minutes), and you can then check that they have correctly loaded in the Style Manager dialogue box.

## Installation for the SVG method
1. Download the .svg files - [SVG files](https://github.com/mapaction/ocha-humanitarian-icons-for-gis/raw/humanitarian-icons-v2/humanitarian-icons-v2-1-svg/humanitarian-icons-v2-1-svg.zip), unblock the zip if necessary (right-click > Properties > General) and unzip.
2. Download the .xml style file - [QGIS humanitarian-icons-v2-1-qgis-svg.xml file](https://github.com/mapaction/ocha-humanitarian-icons-for-gis/raw/humanitarian-icons-v2/humanitarian-icons-v2-1-qgis/humanitarian-icons-v2-1-qgis-svg.xml) - it doesn't matter where this file is.

### Save the SVG files
3. Copy the humanitarian-icons-v2-1-svg folder into a suitable location on your drive.
4. In QGIS, got to  Settings > Options > System > SVG paths, and add the humanitarian-icons-v2-1-svg folder to the list of paths.

### Install the .xml file
4. Open QGIS.
5. Go to Settings > Style Manager > Import/ Export > Import Items(s)
6. Navigate to the .xml file and click OK. 
7. On doing so the icons will appear in the diaglogue box.
8. Click Select All, or click on the individual icons you want. In either case the icons will be highlighted.
9. If required, add tags in 'Additional Tag(s)' - but note that all symbols already have specific tags as well as the tag 'humanitarian icons'.
10. When ready click Import.
11. Click 'yes' to overwrite any existing symbols with the same name.
12. They will be loaded in and you can then check that they have correctly loaded in the Style Manager dialogue box.

<img src="https://github.com/mapaction/ocha-humanitarian-icons-for-gis/blob/humanitarian-icons-v2/documentation/images/qgis-style-manager.jpg" alt="QGIS Style Manager" width="95%" align="centre" >

## Further guidance
* [QGIS - The Style Manager Help](https://docs.qgis.org/3.22/en/docs/user_manual/style_library/style_manager.html).
