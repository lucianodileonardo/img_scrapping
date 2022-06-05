# img_scrapping
This application, once configured, can download FB posts with attachments from a specific page.

## Step 1
Download and installa JDK 1.8
https://www.oracle.com/it/java/technologies/javase/javase8-archive-downloads.html
Select the proper version based on your OS.
This application is compiled with Jdk 1.8 but works with earlier versions.

## Step 2
Go to [Meta](https://developers.facebook.com/), access with a "Developer account" or create one.

## Step 3
Activate a new app and enable all required permissions as below
![image](https://user-images.githubusercontent.com/4057318/172057360-605aaa11-2ba6-4f69-9ec8-25f31a5730ba.png)

## Step 4
Click on "Generate Access Token"

### Please Note
!You must be "administrator" or owner of the page your are downloading from!

# Step 5
Edit "application.properties" file adding:
- pageid
- applicationKey
- AccessToken
Please note: you can find these 3 parameters in https://developers.facebook.com/tools/explorer/

# Launch application
in MS Windows Environment, please execute file "launch.bat".
