# Collector (Aurora) Testing - Build 2437

# Testing areas for consideration
- Copy existing feature geometry and attributes (read-only layers, 'Update Attributes Only' layers)
- Auto-Sync
- Sync in-map
- Sync panel details for edited/deleted feaures and sync failures
- Grid-based transformations - downloading from AGOL
- Coordinate search
- Offline areas - Adhoc/Preplanned
- Arcade expressions - read-only popups
- General attachments (video/photo/audio)
- Related tables
- Feature service editing capabilities 
- Compass mode
- Labeling
- Unit display settings
- High accuracy GPS workflows - including Z values, support for RTK/RTX w/ Trimble receivers
- Feature search
- Security
- Custom basemaps (vector/raster/image) - including Sideloading basemaps
- App Integration
- QR/Barcode scanning- See [this document](https://esri.box.com/s/0h9ux1hu612z6muv4fwl5mwfqklh7l2q) for test samples of various codes. If you'd like to generate your own, you can use the following websites.
   - http://www.barcode-generator.org/
   - https://barcode.tec-it.com/

# Steps for sideloading basemaps using iTunes
The following steps apply to the current version of iTunes 12.8

1. Connect your iOS device to a PC running iTunes
2. In iTunes, choose the connected device > Select File Sharing
3. Choose the Collector app.
4. Choose 'Add File...' button
5. Browse to the location of the TPK/VTPK
6. Click 'Open' to add the file to the Collector Documents directory. It should now be accessible in the Basemap gallery in Collector. 

# Steps for sideloading grid-based transformation files

If you are interested in the process for sideloading grid-based transformation files instead of downloading from ArcGIS Online the following video will describe steps for doing so through iTunes.

[Video](https://esri.box.com/s/akm158yxhl7tqthddz4866gr30ezuuyr)
