# youtube-playlist-tools

Requisite:

- Youtube DATA API access : https://console.developers.google.com/projectselector/apis/api/youtube.googleapis.com/overview
    - get credentials to access User Data

Resources:

- http://google-auth-oauthlib.readthedocs.io/en/latest/reference/google_auth_oauthlib.flow.html
- https://developers.google.com/youtube/v3/docs/
- https://developers.google.com/youtube/v3/guides/implementation/videos
- https://developers.google.com/apis-explorer/
- https://developers.google.com/identity/protocols/OAuth2UserAgent
- https://github.com/youtube/api-samples

javascript:

- https://developers.google.com/youtube/v3/docs/
- https://developers.google.com/api-client-library/javascript/samples/samples#authorizing-and-making-authorized-requests
- https://developers.google.com/api-client-library/javascript/samples/samples#putting-it-all-together  
- https://github.com/google/google-api-javascript-client/issues/318  
- https://google-developers.appspot.com/api-client-library/javascript/features/promises


python:

- https://developers.google.com/youtube/v3/quickstart/python
- https://developers.google.com/api-client-library/python/guide/aaa_oauth
- https://developers.google.com/api-client-library/python/start/installation
- https://developers.google.com/api-client-library/python/guide/aaa_client_secrets

node:

- https://github.com/IonicaBizau/youtube-api

## Watch Later

Watch Later list is under Channels.
 
- https://developers.google.com/youtube/v3/guides/implementation/channels 
 
In the v3 API, you need to retrieve the channel resource to obtain playlist IDs that identify a channel's uploaded videos, 
favorite videos, liked videos, watch history, and watch later lists. (To fetch this information when calling the channels.list 
method, make sure the part parameter value includes the contentDetails resource part. 
 
https://stackoverflow.com/questions/44777670/how-to-list-watch-later-list-in-apiv3

...watch later playlist IDs cannot be retrieved via the API. 
 
## Notes:

    sudo -E pip3 install --upgrade google-api-python-client
    
