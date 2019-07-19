# DataGatheringApp

An Android application to gather touch data while drawing a pattern.

This app has been tested on LG-G4 and Samsung Galaxy S7.

This app requires WRITE_EXTERNAL_STORAGE permission, as data is saved in the sdcard inside a smartphone.  
## How to use:  

1. Make a directory(folder) 'touch_data' under the path '*internal storage*/Android/data' in a smartphone.
2. Download and install the attached 'Gathering_pattern_data.apk'. 'Google Play Protect' might have to be disabled depending on the device.    
3. Open the app GatheringPatternData and click 'Gather Touch Data'. 
4. Draw a pattern.
5. Data is sequentially saved under '*internal storage*/Android/data/touch_data' as csv format.
Data format is :  
file number,touched coordinate X1, touched coordinate Y1, touch pressure 1  
...   
file number,touched coordinate Xn, touched coordinate Yn, touch pressure n  
6. One complete pattern consists of one file. ex) 1.txt  

  Thank you!  
