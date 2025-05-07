# nanoleaf-webui
Single HTML nanoleaf webinterface for demo usage with the v1 api

## Optional improvements
- Build a function to help with getting the authorization token.

## Features
- View all data from the controller
- Turn On/Off
- Set Brightness

## Get authorization token - [Reference](https://forum.nanoleaf.me/forum/community-support/how-to-access-to-nano-leaf-panels-through-http)

"The first thing you need to do is generate an authorization token (section 6 of the Open API documentation) by holding the on-off button for 5-7 seconds, and then sending a POST request like this (substituting the IP address for your Aurora controller):
<br><br>
http:192.188.x.x/api/vi/new 
<br><br>
The result returned will be an 32-character authorization token that you will use in all of your subsequent calls. For example, to retrieve the panel layout, you'd send a HTTP GET request like this (inserting your authorization token):

http:192.188.x.x/api/v1/<auth_token>/panelLayout/layout 
<br><br>
I hope this helps you get started."

## Installation
Download the .html and start using it, you don't even need to run a webserver. Just open the .html in you're browser.

## Feedback

If you have any feedback, please reach out at info@ianvanvliet.nl

## Lessons Learned

This code is so old for me, I don't know, hope it still works.

## License
Just use it if you want.
