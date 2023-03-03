# How to install the humanitarian icons in QGIS 3.10 and above
<img src="https://github.com/mapaction/ocha-humanitarian-icons-for-gis/blob/humanitarian-icons-v2/documentation/images/qgis-logo.jpg" alt="QGIS Logo" width="150" align="right" >These instructions take you through installing the icons to use in QGIS 3.28 and above (though they should also work for earlier versions).

There are two options available, font and SVG, You can install one set, or both sets in parallel - each style has a label indicating whether it is uses a font or an SVG marker. Whichever you install, you can also have the font or SVG markers available for use in your maps, as long as you install the font and download the SVG files (or reference them in the MapAction CMF).

## You will need
For the font method
* The humanitarian icons font
* The .xml URL/file

For the SVG method
* The SVG files
* The .xml URL/file

## Installation for the font method
1. If it's not already installed, download the .ttf font - [Humanitarian-Icons.ttf](https://github.com/mapaction/ocha-humanitarian-icons-for-gis/raw/humanitarian-icons-v2/humanitarian-icons-v2-1-font/Humanitarian-Icons.ttf)
2. Double click on the font (do this before opening QGIS)
3. Click *Install font* and let it install to the default location
4. Open QGIS
5. Go to *Settings > Style Manager*, and look for any existing *humanitarian icons* tags in the *Tags* pane
6. If there are any, click on the tag name to show the icons, *Ctrl-A* to select them all, then click the *Delete* key to delete them
7. Go to *Settings > Style Manager > Import/ Export > Import Items(s)*
8. Set *Import from* to *URL*
9. Paste the URL for the style XML for fonts from this repository into the URL field: https://github.com/mapaction/ocha-humanitarian-icons-for-gis/blob/master/humanitarian-icons-v2-1-qgis/humanitarian-icons-v2-1-qgis-ttf.xml
10. If this doesn't work, download the repository and use *Import from File*, then navigate to the file referenced above
11. On doing so the icons will appear in the dialogue box
12. Click *Select All*, or click on the individual icons you want - in either case the icons will be highlighted
13. If required, add tags in *Additional Tag(s)* - but note that all symbols already have specific tags as well as the tag *humanitarian icons - font*
14. When ready click *Import*
15. Click *Yes* to overwrite any existing symbols with the same name.
16. They will be loaded (it may take a few minutes) - check that they have correctly loaded in the Style Manager dialogue

## Installation for the SVG method
1. Check that the SVG files are the MapAction CMF at GIS\3_Mapping\31_Resources\311_Symbolsets\ocha-humanitarian-icons-for-gis\humanitarian-icons-v2-1-svg
2. If they are not, download the .svg files - [SVG files](https://github.com/mapaction/ocha-humanitarian-icons-for-gis/raw/humanitarian-icons-v2/humanitarian-icons-v2-1-svg/humanitarian-icons-v2-1-svg.zip), unblock the zip if necessary (*right-click > Properties > General*) and unzip to a suitable location
3. In QGIS, go to  *Settings > Options > System > SVG paths*, and add the humanitarian-icons-v2-1-svg folder to the list of paths
4.Go to *Settings > Style Manager > Import/ Export > Import Items(s)*
8. Set *Import from* to *URL*
9. Paste the URL for the style XML for SVG from this repository into the URL field: https://github.com/mapaction/ocha-humanitarian-icons-for-gis/blob/master/humanitarian-icons-v2-1-qgis/humanitarian-icons-v2-1-qgis-svg.xml
7. If this doesn't work, download the repository and use *Import from File*, then navigate to the file referenced above
8. On doing so the icons will appear in the diaglogue box.
9. Click *Select All*, or click on the individual icons you want - in either case the icons will be highlighted
13. If required, add tags in *Additional Tag(s)* - but note that all symbols already have specific tags as well as the tag *humanitarian icons - font*
14. When ready click *Import*
15. Click *Yes* to overwrite any existing symbols with the same name.
16. They will be loaded (it may take a few minutes) - check that they have correctly loaded in the Style Manager dialogue


<img src="https://github.com/mapaction/ocha-humanitarian-icons-for-gis/blob/humanitarian-icons-v2/documentation/images/qgis-style-manager.jpg" alt="QGIS Style Manager" width="95%" align="centre" >

## Further guidance
* [QGIS - The Style Manager Help](https://docs.qgis.org/3.22/en/docs/user_manual/style_library/style_manager.html).
