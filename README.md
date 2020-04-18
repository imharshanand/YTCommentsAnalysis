# YTCommentsAnalysis
Python Script - Scraping YouTube comments and analyzing using "Vader Lexicon" package

import time
import httplib2
import os
import sys
import csv
import io
import vaderSentiment
import matplotlib
update/import oauth2client

Download youtube-v3-discoverydocument.json file
From https://www.googleapis.com/discovery/v1/apis/youtube/v3/rest

Goto https://console.developers.google.com/
Enable YouTube Data API V3
Create OAuth 2.0 Client IDs 
Download client_secrets.json

<div align="center">
<table>
  <tr>
    <td>Script</td>
     <td>Generated Pie Chart</td>
  </tr>
  <tr>
    <td><img src="Screenshots/Script Running CMD.png" height=480></td>
    <td><img src="Screenshots/Generated Pie Chart.png" height=480></td>
  </tr>
 </table>
 </div>