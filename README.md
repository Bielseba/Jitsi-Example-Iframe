# Jitsi-Example-Iframe
Example using jitsi on iframe

## Installation
1. Clone **index.html**
2. Change **meet.aproxtime.com** to your Jitsi server

## How to use 
This code use parameter to store **Room Name** and **User Name** using format like this
> name=Faris&room=Ruangan1

Don't forget to encode using **Base64** so when in address 

> https://your-server.domain/index.html?ENCODED_STRING

When user not provide encoded code or the code failed to parse, **Wrong Code** will be displayed in html tag #**info**
