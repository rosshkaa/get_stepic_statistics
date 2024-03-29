# course-statistics

### run 
```
python3.7 course_statistics.py --id COURSE_ID --key KEY_FILE_PATH --sheet GOOGLE_SHEET_URL_KEY --list GOOGLE_SHEET_LIST_NAME
```

Users to find in Stepik should be listed in the `users` file, separated by blank space.  
Google API key should be located in `google_api_key.json  `


### GOOGLE_SHEET_URL_KEY != URL

Example:  
if sheet url is https://docs.google.com/spreadsheets/d/1x-VvGqxo8dYAUvw5LPwKx2sFJgD1kOV8hM_cTcVu6Lk/edit  
then url key if 1x-VvGqxo8dYAUvw5LPwKx2sFJgD1kOV8hM_cTcVu6Lk

### Google API key

* Go to the [Google APIs Console](https://console.developers.google.com/)
* Create a new project.
* Click Enable API. Search for and enable the Google Drive API.
* Create credentials for a Web Server to access Application Data.
* Name the service account and grant it a Project Role of Editor.
* Download the JSON file.
* Copy the JSON file to your code directory and rename it to client_secret.json
