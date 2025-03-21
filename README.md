# ogfimg
 OGF Image/tile downloader and stitcher

 This is a simple tool I made with ChatGPT for downloading tiles on [OGF](https://opengeofiction.net) then stitching them to one pretty map.

 ## Setup

  First install the following dependencies with:
  pip install flask requests pillow

  After that you should be able to just run the app.py then on port 5000 of the machine you put it on it should show the site ready to use.

 ## Usage
  Its really quite simple where you either enter your zoom, start lat and lon, and end lat and lon, or just use the box tool and enter your zoom level. After that seclect "Start Download" where a progress bar will show how many tiles it has downloaded, once complete seclect "Stitch Map" and after some time it will let you download your image. If you happen to refresh the page before download you can find it under /download/map_X.png (replace X with its real number).
 
  Sometimes the download never completes because some tiles are mising and if that happens just click stitch map and once you download the map refresh the main page.

  ### Once Done
  Once you are done with downloading an image always refresh the main page (just in case there are errors)

  If you are done with making images it can stay on or you can just stop it by closing the command prompt.
