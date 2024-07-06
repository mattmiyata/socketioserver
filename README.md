
# Chatter
This is the server code for the simple chat app using socket.io and react

Note: the vite compiled code for front end is located in the 'public' folder

![Screenshot here]([http://full/path/to/img.jpg](https://private-user-images.githubusercontent.com/29637795/346292951-8713d3c3-fd49-4ad2-9360-2f32675e3f20.PNG?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjAyOTIyODMsIm5iZiI6MTcyMDI5MTk4MywicGF0aCI6Ii8yOTYzNzc5NS8zNDYyOTI5NTEtODcxM2QzYzMtZmQ0OS00YWQyLTkzNjAtMmYzMjY3NWUzZjIwLlBORz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MDYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzA2VDE4NTMwM1omWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWJmNjdjNTcwYjgwZDJmMjFjY2MyNmY2ODZlYmQxMjVkNmVhMjcwZDcxM2Q5ZWQxNjFlMGE5MTBkNTk0YjE5MzQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.HDWJRd8maorwerteKO3jrfTxhhZYKuXlZoDfQJyyGKY) "Screenshot")


Server side is used to ingest socket requests. 
Session information is kept to client side.  

## Demo

https://socketiochatserver-6ad190f163f6.herokuapp.com/

```
https://github.com/mattmiyata/socketioserver
```
## Installation

Clone this repository using the following command:
```
git clone https://github.com/mattmiyata/socketioserver.git
```
Navigate to the project directory:
```
cd socketio
```
Run the app and view in your browser:
```
npm start
```
## Code Description
[app.js](https://github.com/mattmiyata/YoutubeVideoDownloader/blob/main/app.js) - This is the "main" file for the application.  

[404.ejs](https://github.com/mattmiyata/YoutubeVideoDownloader/blob/main/views/404.ejs) - 404 page with link to homepage

[index.ejs](https://github.com/mattmiyata/YoutubeVideoDownloader/blob/main/views/index.ejs) - Homepage of application.  User will input desired url in input box.  Submiting form will create a 'post' request to /download and pass necessary info as res.

[download.ejs](https://github.com/mattmiyata/YoutubeVideoDownloader/blob/main/views/download.ejs) - Page displayed after user submits valid youtube url.  Code will populate page with links for each video format returned from ytld-core.


## Usage
  1. Copy and paste a link to the youtube video you wish to download in the input field and press 'Convert'
  2. Click on the button corresponding to your desired video/audio quality
