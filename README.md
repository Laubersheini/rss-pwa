# about
This was inspired by a video from Luke Smith [https://www.youtube.com/watch?v=hpZBYcD3ysY](https://www.youtube.com/watch?v=hpZBYcD3ysY)

# using 
Simply copy this code to your website. Make sure it is on its own subpage (eg example.com/reader) and that nothing else is in that subpage. This will cache everything that starts with example.com/reader meaning that example.com/reader/index.html for example will never be updated again!. Your rss-feed must also be in a different directory. Also make sure that the rss-feed you want to load is on the same domain as this app.

This currently does not cache the rss feed for offline reading

# customizing
You will need to change some names with your custom names and links:

In index.html replace "Your cool name" with whaterver heading you want.  
In urls.json edit the link so it points to your rss feed.  
In rss.webmanifest edit the name, short_name and description
In config.css you can change the colors
For a custom icon use [https://www.pwabuilder.com/imagegenerator](https://www.pwabuilder.com/imagegenerator) to generate the different resolutions that are needed. Dowload them and replace the icons folder with your icons.


# rss parser from
https://github.com/rpsthecoder/js-rss-reader  
