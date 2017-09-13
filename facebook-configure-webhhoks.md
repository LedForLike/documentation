
## Configure Facebook App

1. Setup privacy policy
  1. Go to *Settings=>Basic*
  1. Fill *Privacy Policy URL* with `https://ledforlike.github.io/privacy`
  1. Click on *Save Changes*
1. Setup App Icon
  1. Go to *Settings=>Basic*
  1. Click on *App Icon*
  1. User the following image to upload [following logo](https://ledforlike.github.io/logo.png)
  1. Click on *Save Changes*
1. Configure Platform
  1. Go to *Settings=>Basic* 
  1. Click on *Add Platform*
  1. Select *Website*
  1. In *Site URL* enter `https://ledforlike.github.io/`
  1. Click on *Save Changes*
1. Make app public in *App Review* page of the app
1. Submit page for approval
  1. In *App Review* start submission
  1. Chose `publish_pages` and `manage_pages` permissions
  1. Click on *Add 2 Items*
1. Fill notes for each Items
  1. Click on notes under `publish_pages` and `manage_pages`
  1. Select *Other* and fill `Receiving webhooks when someone likes the page`
  1. Select *Web* platform and in steps fill:
     ```
     1. Click like button of page
     2. Webhook sent to Web API
     ```
  1. In *Upload screencast* user the following [file](http://www.sample-videos.com/video/mp4/720/big_buck_bunny_720p_1mb.mp4) 
  1. Click *Save*
1. Submit the app for review by clicking on *Submit For Review*
1. Go to *WebHooks* and click on *Subscribe* next to *feed* 

## Setup Graph API

1. Go to https://developers.facebook.com/tools/explorer
1. Right top corner pick a relevant app
1. On right side of *Access Token* select a relevant page
1. In the endpoint field switch to *POST* method and in URL fill `[YOUR PAGE ID]/subscribed_apps`. You can fin page id either in URL of the page or in *About* section of page
1. Click submit