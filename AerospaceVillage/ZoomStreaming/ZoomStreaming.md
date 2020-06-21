# Streaming to Twitch and YouTube with Zoom

This guide will help you setup Zoom to stream to Twitch or YouTube

## Getting streaming info from Twitch

You can stream to Twitch in Zoom but it is not natively supported. Fortunately, you can setup a custom streaming destination. To do this you'll need to collect some information from Twitch first.

### Info needed by Zoom

There are three pieces of info that Zoom wants to setup a custome streaming destination

- Streaming URL
- Streaming key
- Live streaming page URL

#### Streaming URL

The streaming URL for Twitch is:

rtmp://live.twitch.tv/app

This should be the same value everytime you setup streaming for Zoom. 

#### Streaming Key

The find the streaming key you need to login to your Twitch account. You can follow these steps:
 
- Login to your Twitch account
- Click on you account icon/avatar (upper right)
- Click on “Setting” in drop down menu
- Click on “Channel and Videos” tab 
- Find the entry for  “Primary Stream Key” (should be right at the top)
- Click “Copy”

You now have your Primary Stream Key in your clipboard. This key shouldn't change unless you regenerate it. Keep it safe. It is a secret. If someone gets your streaming key they could stream to your Twitch account without your permission. You can paste it into a temporaty document for now. We'll need it later on.

#### Live Streaming URL
This is the url to your twitch account channel. It will be:

https://www.twitch.tv/<username> 

You can goto your Twitch channel webpage and copy it from there if needed.

## Enabling Zoom streaming

Streaming in Zoom is not enabled by default. You'll need to enable it. You can follow these steps:

- Login to your Zoom account on the web page
- Goto Settings
- Select the “Meeting” Tab
- Scroll all the way down (about ¾ down the page) to “Allow live streaming”
- Click “Custom Live Streaming” to enable live streaming to a custom destination

You can also click “Facebook”, “Workplace by Facebook” or “YouTube” if you intend to stream to those destinations.



----


Streaming Key: <streaming key>
Live Streaming URL: https://www.twitch.tv/aerospacevillage

Info needed from Twitch:

Stream URL is the same for any stream to twitch which is 
rtmp://live.twitch.tv/app

Streaming Key is obtained from your twitch account



Configure Twitch to record streams:
While in the  “Channel and Videos” tab scroll down to “Store past broadcasts” and enable that. For free accounts it will keep past streams for 14 days.

Setting up Zoom to enable Twitch streaming
To stream with Zoom you must have a paid account

Login to your Zoom account on the web page
Goto Settings
Select the “Meeting” Tab
Scroll all the way down (about ¾ down the page) to “Allow live streaming”
Click “Custom Live Streaming” to enable live streaming to a custom destination
You can also click “Facebook”, “Workplace by Facebook” or “YouTube” if you intend to stream to those destinations.
