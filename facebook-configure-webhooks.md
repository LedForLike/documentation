
## Configure Facebook App

1. Make app public in *App Review* page of the app
1. Go to *WebHooks* and click on *Subscribe* next to *feed* 

## Setup Graph API

1. Go to https://developers.facebook.com/tools/explorer
1. Right top corner pick a relevant app
   * ![](/images/facebook-graph-1.png)
1. On right side of *Access Token* select a relevant page
   * ![](/images/facebook-graph-2.png)
1. Get page ID (you will need it later) from *About* section of page
   * ![](/images/facebook-graph-3.png)
1. In the endpoint field switch to *POST* method and in URL fill `[YOUR PAGE ID]/subscribed_apps`
   * ![](/images/facebook-graph-4.png)
1. Click submit
   * ![](/images/facebook-graph-5.png)
   
