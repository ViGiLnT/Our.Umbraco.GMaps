﻿
 ██████╗ ██╗   ██╗██████╗    ██╗   ██╗███╗   ███╗██████╗ ██████╗  █████╗  ██████╗ ██████╗     ██████╗ ███╗   ███╗ █████╗ ██████╗ ███████╗
██╔═══██╗██║   ██║██╔══██╗   ██║   ██║████╗ ████║██╔══██╗██╔══██╗██╔══██╗██╔════╝██╔═══██╗   ██╔════╝ ████╗ ████║██╔══██╗██╔══██╗██╔════╝
██║   ██║██║   ██║██████╔╝   ██║   ██║██╔████╔██║██████╔╝██████╔╝███████║██║     ██║   ██║   ██║  ███╗██╔████╔██║███████║██████╔╝███████╗
██║   ██║██║   ██║██╔══██╗   ██║   ██║██║╚██╔╝██║██╔══██╗██╔══██╗██╔══██║██║     ██║   ██║   ██║   ██║██║╚██╔╝██║██╔══██║██╔═══╝ ╚════██║
╚██████╔╝╚██████╔╝██║  ██║██╗╚██████╔╝██║ ╚═╝ ██║██████╔╝██║  ██║██║  ██║╚██████╗╚██████╔╝██╗╚██████╔╝██║ ╚═╝ ██║██║  ██║██║     ███████║
 ╚═════╝  ╚═════╝ ╚═╝  ╚═╝╚═╝ ╚═════╝ ╚═╝     ╚═╝╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝ ╚═════╝ ╚═╝ ╚═════╝ ╚═╝     ╚═╝╚═╝  ╚═╝╚═╝     ╚══════╝

--------------------------------------------------------------------------

# Our.Umbraco.GMaps - Google Maps for Umbraco 9
Basic Google Maps with autocomplete property editor for Umbraco 8 including property value converter.

# Features
- Search for address using autocomplete and place marker
- Enter coordinatesan place marker
- Click on exact location on map to place marker
- Drag marker around
- Set default location & zoomlevel on Data Type settings
- Zoomlevel is saved on the proprety to use the same zoomlevel on your website
- Centerpoint is saved on the proprety to use the same centerpoint on your website different than the marker.
- MapType is saved on the proprety to use the same maptype on your website
- User your SnazzyMaps API key to set mapstyles

# Enable Google Maps API

- Enable the following Google Maps API on https://console.cloud.google.com/home/dashboard
  - Maps Javascript API
  - Geocoding API
  - Place API

# Manual Install

- Place Our.Umbraco.GMaps directory in \App_Plugins
- In Umbraco backoffice in the Settings section create a new datatype of type "Google Maps Single Marker".
  - The API key, default location and default zoom can be entered on the Data Type settings.

# Special thanks
Special thanks to [ronaldbarendse](https://github.com/ronaldbarendse) for contributing to this project #h5yr!
Special thanks to [prjseal](https://github.com/prjseal) for the Visual Studio project setup and included demo-site #h5yr!