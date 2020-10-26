# Budget-Tracker

This is an example Progressive Web Application with detailed steps to make it fully functional. 

## Test your application
Start the server: node server.js
Visit http://localhost:3000 and confirm that the application works correctly.
In Robo 3T, confirm that after adding an entry to your budget, that you now see a budget database and a transactions collection.
Robo 3T

### Offline Storage with IndexedDB
Test that the app works offline by setting your Network tab to Offline and adding a transaction. You should see the http call fail, but the transaction still appears on the screen.
Offline Failed http Call

Additionally, you should see your transaction stored in the IndexedDB under Application -> Storage -> IndexedDB -> budget - http://localhost:3000 -> pending

### Confirm your application is reading your service worker by visiting the Application tab and clicking Service Workers.
Refresh the page twice. Now, you should see both your static-cache and your data-cache in the Cache Storage section.

### Static Cache Data Cache
Confirm you are able to access your application offline by selecting Service Workers, and checking the "Offline" checkbox.