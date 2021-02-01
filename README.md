# Google Maps widget for HABpanel (Openhab)
By making a donation, no matter how small, you are saying thanks and drawing a smile on my face because I will know, somebody thought my project was useful and worth paying for 🤩. [![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=QARL4KXHHZSK8)

| WARNING: be careful to not overuse the Google API or you will be charged! Use this code at your own risk! |
| --- |

## Description
Google Maps widget with traffic layer for HABpanel (Openhab).

Get your Goolge Maps API key [here](https://developers.google.com/maps/documentation/javascript/get-api-key).

## Installation
- Import the downloaded widget to your HABpanel.
- Place the map.html file within your /conf/html folder structure.
- In the settings of the widget:
  - Set ServerPath to the location of your map.html (/conf/html/ = /static/).
  - Set to your preferred zoom level.
  - Set to your position in latitude and longitude.
  - Set your desired height, the width is auto filling from wodget frame.
  - If you would like travel time calculation, Enable Travel time check.
  - For travel time, set origin.
  - For travel time, set destination.
  - Set your Google Maps API key.

## Help
If you need any help, use this [topic](https://community.openhab.org/t/google-maps-widget-with-traffic-layer/40285) on the Openhab community forum.

For issues and feature requests, please use the [Issues module](https://github.com/BasvanH/habpanel-widget-googlemaps/issues) on Github.
