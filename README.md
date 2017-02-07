# Microsoft Teams Tab Themes
This sample demonstrates how to build a custom tab for Microsoft Teams that retrieves the active theme for the user and listen for theme changes. Use the following steps to run the sample:

1. Clone the repo
2. (optional) if you don't have gulp run the following command
```
npm install -g gulp
```
2. Open command prompt to root and run the following
```
npm install
gulp serve-static
```
3. Log into Microsoft Teams and select the "View Team" option in the contextual menu of a team
4. Go to the Developer tab in Team settings
5. Upload the TabPackage.zip to the Tabs in Development list
6. Go back to the Team and add the new tab to a channel and test

Note: you might need to open a browser to https://localhost:8443 to allow the untrusted https cert