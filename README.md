# Collector (Aurora) on Android - Version 19.1.0 Build 2576

# Testing areas for consideration

Android devices include both phones and tablets.

GNSS
- Integrated receivers
- External Bluetooth receivers - including Trimble 
- Streaming
- Metadata fields
- Location Profiles
- Storage of Z values

Offline
- Preplanned offline areas
- On-demand offline areas
- Sideloaded basemap switching - includes internal device storage and external SD cards. (`See notes below for instructions`)
- Sync - includes using the sync panel inside the map for viewing pending edits

General
- Related tables
- Copying features
- Using 'Collect Here'

# Steps for sideloading basemaps (internal storage & external SD card)
1. Connect the Android device to a PC/Mac
2. At the root of the devices internal storage or SD card, create a folder called `ArcGIS`.
3. Inside the `ArcGIS` folder create a folder called `basemaps`.
4. Copy tile packages into the `basemaps` folder. 
