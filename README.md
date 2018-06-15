# Collector (Aurora) Testing - Build 2282

# Testing areas for consideration
- Offline areas - Adhoc/Preplanned
- General attachments (video/photo/audio)
- Related tables
- Feature service editing capabilities 
- Compass mode
- Labeling
- Unit display settings
- High accuracy GPS workflows - including Z values 
- Feature search
- Security
- Custom basemaps (vector/raster/image) - including Sideloading basemaps
- App Integration
- QR/Barcode scanning- See [this document](https://esri.box.com/s/0h9ux1hu612z6muv4fwl5mwfqklh7l2q) for test samples of various codes. If you'd like to generate your own, you can use the following websites.
   - http://www.barcode-generator.org/
   - https://barcode.tec-it.com/

# Steps for sideloading basemaps using iTunes
The following steps apply to the current version of iTunes 12.7.5

1. Connect your iOS device to a PC running iTunes
2. In iTunes, choose the connected device > Select File Sharing
3. Choose the Collector app.
4. Choose 'Add File...' button
5. Browse to the location of the TPK/VTPK
6. Click 'Open' to add the file to the Collector Documents directory. It should now be accessible in the Basemap gallery in Collector. 

# Steps for sideloading grid-based transformation files using iTunes
The following steps apply to the current version of iTunes 12.7.5

Before starting the workflow, ensure you have installed the ArcGIS Coordinate System Data, for Pro or ArcMap. 

1. Connect your iOS device to a PC running iTunes
2. In iTunes, choose the connected device > Select File Sharing
3. Choose the Collector app.
4. Choose 'Add File...' button
5. Browse to the pedata folder inside the coordinate systems folder
6. From that 'Add File...' dialog, drag the pedata folder into 'Collector Documents'. Nothing happens at this point
7. Click 'Cancel' on the 'Add File...' dialog box. You should now see the pedata folder copying onto the device. 

Please see the following video - https://esri.box.com/s/0vh84fg7lduydrox00ijxlpkg7cffcrd

The steps above will copy the entire pedata folder onto your device, which is approximately 1.5 gb. 

If you only need/want particular grid files, please follow these steps:
1. Create a new folder in a different directory called pedata
2. Create a subfolder for the type of grid files you want, for example a folder called ntv2
3. Create another subfolder under that for the area you want, for example uk
4. Then copy the actual grid files from that same uk folder that was installed with the coordinate systems data into that new subfolder. basically all you're doing is creating folders to mirror the same structure as the original, but with only the files you need. 
5. Then follow the steps above through iTunes to add that folder onto the device. 
