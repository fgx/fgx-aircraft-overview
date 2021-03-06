![FGx Logo]( http://fgx.github.io/images/fgx-cap-40x30.png) FGx Aircraft Overview Read Me
=========================================================================================

[FGx Aircraft Overview (latest)]( http://fgx.github.io/fgx-aircraft-overview/latest/index.html )

Cropped `iframe` view of the FGx Aircraft Loader app:
<iframe src="latest/index.html" width=100% height=300px>
There is an `iframe` here. It is not visible when viewed on github.com/fgx. To view, please go to fgx.github.io.
</iframe>

## Concept

### Mission
FGx Aircraft Overview is an on-line browser-viewer for [FGX Aircraft]( fgx.github.io/fgx-aircraft/ ). 
It allows you to view and manipulate 3D models interactively in real-time.

### Vision
FGx Aircraft Overview is an on-line portal to the current and historical 'menagerie' man-made flying machines.
You can have a very close look at the aircraft and click through the many curated links so as become quite familiar with an aircraft in a short amount of time.

In the long term, it is hoped that future revisions of the models and their display technology will be of sufficient quality and appropriately licensed so as to be included in the Wikipedia entry for each aircraft  

## Road Map

* Permalink capability
	* select aircraft
	* toggle bounding box and image display
	* set color and background etc
* Allow you to select aircraft by categories such as year built, country, manufacturer, type etc
* For each aircraft
	* Link to appropriate Wikipedia entry
	* Link to manufacturer's web page for the aircraft and/or other significant links
	* Link to Google image search for the aircraft. Example [Avro Vulcan B2 images]( https://www.google.com/search?q=vulcan+b2&client=firefox-a&hs=Za6&rls=org.mozilla:en-US:official&channel=fflb&source=lnms&tbm=isch&sa=X&ei=KiKyUo65OPPO2QXf-4CoBA&ved=0CAkQ_AUoAQ&biw=1846&bih=929&dpr=1 )
* Add 'Which plane is this?' game

* Add slide-show replay capability
* Add pre-loading of next file
* Camera movement starts if no interaction for 20 seconds.
* Start adding limited piloting capabilities  
* Add skybox and globe or landscape	
* Add zoom to fit extents


## Copyright and License
copyright &copy; 2015 FGx authors ~ All work herein is under the [GPL 2.0 License](https://github.com/fgx/fgx-aircraft/blob/gh-pages/license.md)

## Change Log

2015-02-21 ~ Theo

* R10
* Add xmlhttprequests callbacks
* Update menus to be more mobile friendly/more compact
* Code clean-up
* Bounding box display toggle as you click


2015-01-13 ~ Theo

* R8.1
* Left menu many updates
* Left menu shows details when file is loaded from disk
* Right menu: current selection is highlighted. Previous selection is de-highlighted
>> * Highlight currently selected aircraft with a color background

2015-01-12 ~ Theo

* Add R8
* Add compute vertex normals
* Code clean-up
* Fix display of read me files 
* Add About notice
* Simplify file loading process

2015-01-11 ~ Theo

* Add up/down cursor key events to enable scrolling through the files << Page Up  / Page Down
* Split menus into two separate ribbons
* Better handling of title bar, moving, iconifying
* Add scroll to randomly selected item at app opening
* some code clean-up

2015-01-10 ~ Theo

* Add added first pass at multiple ribbons menu idea
	* both menus have title mars that allow for moving the menu
	* both menus have independent smallifiers

* Added view Readme where file is available
* Added toggle display of images  
* Add notification of which aircraft is being viewed << added a while ago


2015-01-07 ~ Theo

* Force MeshNormalMaterial
* Tighten spacing in menu
* Change data file to aircraft.csv

2015-01-06 ~ Theo

* Update readme
* A near full re-write, but still a WIP
* Merges duplicate vertices and displays before and after numbers
* Allows you to save and open files in the new Three.js JSON 4+ format
* Displays bounding box - which can be toggled
* Display bounding box dimensions

2015-01-05 ~ Theo

* Added axis indicator
* simplified lights
* added reload link to title
* code cleanup
* Update copyrights
* Add latest folder and file



2013-12-18 ~ Theo

* Expanded read me

2013-12-06 ~ Theo

* Added Aircraft Overview R4
* Displays thumbnails
* Adds access to splash images

2013-12-05 ~ Theo

* Moved to new repo and renamed: FGx Aircraft Overview