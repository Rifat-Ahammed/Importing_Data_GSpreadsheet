
# Hot to import Data from GSpreadsheet using python Pandas

A brief description of what this project does and who it's for.

Here, I am going to explain the process step by step:
 
## API Reference & steps

### https://console.cloud.google.com

1. #### Use this API to create your project 
```http
  https://console.cloud.google.com/welcome?project=lustrous-bus-405109
```
2. #### Go to Enable APIs & Services using below URL

```http
https://console.cloud.google.com/apis/dashboard?project=lustrous-bus-405109
  
```
3. ### Go to select project option create a new project and then give a project name then (create)

```http
  https://console.cloud.google.com/projectcreate?previousPage=%2Fapis%2Fdashboard%3Fproject%3Dlustrous-bus-405109&organizationId=0
```
4. ### After creating the project then get into the project to enable 2 option.
  -> Enable (Google Drive API)\
  -> Enable (Google Sheets API)

```http
Drive API: https://console.cloud.google.com/marketplace/product/google/drive.googleapis.com?q=search&referrer=search&project=test2-405110 
Sheets API: https://console.cloud.google.com/marketplace/product/google/sheets.googleapis.com?q=search&referrer=search&project=test2-405110
```

5. ### After Enable those 2 API need to go "Credentials" option to create Credentials

```http
https://console.cloud.google.com/apis/credentials?project=test2-405110
```
6. ### Among all the option in "Credentials" you have to choose "Service Account" and click the option then name your service account and don't forget to copy the email adress. create and continue and finally done. 

1 then go to "Manage service accounts"\
2 Action\
3 will be there lots of optin in "Action" just choose "Manage keys"\
4 "Add Key" -> "Create new key" -> "Json" -> "create". 

Finally you will get a pdf file in your Download option and Keep it.

## Create ShpreadSheet

### Open your Gspread Online editor and create a Gspread file.

- Go to "share" and in the search bar paste that "email adress" you coppied from your project.
- Then after pasting the email adress you will see "editor" option in the right side of search bar just change "editor" to "viewer" then send. 

So, finally the whole process is done here but how to complete the task you can follow my python code. 

## Deployment

To deploy this project run you need to install

```bash
  pip install pandas
  pip install gspread
```

## Author

- [@Rifat-Ahammed](https://github.com/Rifat-Ahammed)