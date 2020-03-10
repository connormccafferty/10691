# Ticket 10691

This example demonstrates setting up two seperate channels for multiple children app clients. Child apps send a heartbeat back to the main app every 2 seconds and also upon firing the 'bounds-changing' event will send the new bounds data to the main app.

### How to use this:

- Clone this repository: `git clone https://github.com/connormccafferty/10691`
- Install the dependencies: `cd 10691` & `npm install`
- Start the live-server and launch the application on it's current version: `npm start`
