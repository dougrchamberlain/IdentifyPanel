IdentifyPanel
=============

A Widget to be used with the Configurable Map Viewer




A widget created as an addition to [David Spriggs Configurable Map Viewer](https://github.com/DavidSpriggs/ConfigurableViewerJSAPI), aka CMV. Designed for use in his project using the file structure indicated there. 

Please see this projects [how-to Wiki] (https://github.com/friendde/ArcGIS_JS_NavigationTools/wiki/How-to-add-widget-to-CMV) for details on how to configure CMV to load this widget.

## NavToolbar

![navtoolsscreenshot](https://cloud.githubusercontent.com/assets/7818309/4076966/d57254fe-2ebe-11e4-9590-2988bf24bd38.JPG)

## Adding to CMV
```javascript
widgets: {

			identifyPanel: {
				include: true,
				id: 'identifyPanel',
				type: 'titlePane',
				path: 'gis/dijit/IdentifyPanel',
				title: 'Identify Stuff',
				open: true,
				position: 6,
				options: {
					map: true			
				}
			},			
```

