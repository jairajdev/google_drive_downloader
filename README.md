# Google Drive Downloader && Web Server for Downloaded Files

<p>
<img width="100%" height="100%" src="https://github.com/jairajdev/google_drive_downloader/blob/master/screenshot/1.png" alt="">
</p>

<p>
<img width="100%" height="100%" src="https://github.com/jairajdev/google_drive_downloader/blob/master/screenshot/2.png" alt="">
</p>

`The downloader app doesn't need Google Drive API, but instead use Google Apps Script for getting the file list.`

### Deploy web app in google apps script

1. Use code from `google_apps_script.gs` file.
2. Deploy as web app.
3. Copy the web app url and paste that link as value of variable `script-url` of `downloader.js` in the repo.

### Usage of Downloader

1. Enter the google drive folder links in urls.txt file line by line
1. Run commnad
   ```shell
   node downloader.js
   ```

### Usage of Web Server

1. For HTTP, Run command
   ```shell
   node httpServer.js
   ```
1. For HTTPS, Run command
   ```shell
   node httpsServer.js
   ```
