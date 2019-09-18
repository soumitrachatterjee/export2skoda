# export2skoda
   _Nifty utility to export existing media to folder structure supported by
   Skoda vehicles_

After much pain, I discovered that Skoda vehicles have stringent requirements
regarding media folders on the SD card.

If playing music from the SD card slot of the vehicle, the SD card contents
must adhere to the following constraints:

   - A maximum of 6500 media files in total
   - A maximum of 1024 directories
   - Each directory can have a maximum of 1024 files/directories

This utility will take a media directory (or several) and export the media
files to a directory conforming to the above constraints.

## Usage
   
   export2skoda target-dir media-dir [media-dir]...

