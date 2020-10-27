# Online-Offline-Budget-Trackers

For this assignment I was given the front end code and the back end code for a budget tracker to work online. I was tasked with adding the back end code to allow the application to work offline as well and sync with the database once it returns to online status.

## Description

The budget tracker allows the user to enter transactions by adding a name, an amount, and whether the transaction is a deposit or withdrawl. In online mode this is then sent to a MongoDB database and displayed on a chart at the bottom of the page. When in offline mode, the application shows a cached version of the page and allows the user to continue to enter transactions which are stored in an IndexedDB storage. When the application reconnects, the IndexedDB stored transactions are posted to the MongoDB database and the user can continue.

## Link

https://online-offline-budget-tracker3.herokuapp.com/

![Image of Application](\public\assets\img\Budget-Tracker-Demo.png)