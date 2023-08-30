
# beefree-sdk-assets-video

This repository includes all the icon sets available in the video content block of the Beefree SDK builder.

  

## light and dark icons

The Beefree SDK JSON contains the full path to the video icon within the module's `descriptor` inside of the `iconSrc` param.

    {
      "video": {
        "src": "",
        "thumbSrc": "",
        "thumbRatio": "16-9",
        "iconSrc": "{root}/public/resources/components/widgetBar/video-content-icon-sets/dark/type-03.png",
      }
    }
      
    
The sending app may replace the hosted icon images with custom URLs during post-processing or directly in the JSON. 

Current `{root}`:
`https://app-rsrc.getbee.io`

Full sample URL:
`https://app-rsrc.getbee.io/public/resources/components/widgetBar/video-content-icon-sets/dark/type-04.png`

## spacers

The `thumbRatio` param of the video module's `descriptor` determines which spacer image will be inserted into the HTML. The sending app may replace the hosted spacer images with custom URLs during post-processing.

Current `{root}`:
`https://app-rsrc.getbee.io`

Full sample URL:
`https://app-rsrc.getbee.io/public/resources/multiparser/video_block/video_ratio_16-9.gif`

