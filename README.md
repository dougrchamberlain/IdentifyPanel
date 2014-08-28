IdentifyPanel
=============

A Widget to be used with the Configurable Map Viewer




A widget created as an addition to [David Spriggs Configurable Map Viewer](https://github.com/DavidSpriggs/ConfigurableViewerJSAPI), aka CMV. Designed for use in his project using the file structure indicated there. 

Please see this projects //TODO:ADD LINK// for details on how to configure CMV to load this widget.

![Screenshot](https://raw.githubusercontent.com/dougrchamberlain/IdentifyPanel/master/screenshot.png)

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

