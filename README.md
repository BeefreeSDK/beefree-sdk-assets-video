
# bee-video-icons

This repository includes all the icon sets available in the Video module of BEE Plugin.

  

## light and dark icons

The BEE Plugin page JSON contains the full path to the video icon within the module's `descriptor` inside of the `iconSrc` param.

    {
      "video": {
        "src": "",
        "thumbSrc": "",
        "thumbRatio": "16-9",
        "iconSrc": "https://qa-bee-app-rsrc.s3.amazonaws.com/public/resources/components/widgetBar/video-content-icon-sets/dark/type-03.png",
      }
    }
      
    
The sending app may replace the hosted icon images with custom URLs during post-processing, or directly in the JSON. 

## spacers

The `thumbRatio` param of the video module's `descriptor` determines which spacer image will be inserted into the HTML. The sending app may replace the hosted spacer images with custom URLs during post-processing.
