# PROJECT PLANNING
## Overview
Alright, let's try this again. Rather than make a digital comic book platform (for now), the goal has been shifted to create a React Native mobile app that will, essentially, allow users to store their own, and other's, business cards, as well as pass their's along to anyone they desire. No more fuss about carrying physical business cards, or whether or not you have any on you at any given point in time. Ideally, this app will run mostly(if not entirely) off of the local storage of the device with no access to the internet required (outside of the initial download). Also, users of this app should be able to broadcast their business cards to anyone with a device regardless of whether or not they have an app. Also, the user with the app should be able to organize business cards into arbitrary categories or designations (possibly with tagging)

## Primary Technologies
* **React Native:** The primary library for creating this mobile app.
* **React:** Possible use for prototyping outside of mobile environment.
* **Some QR Module:** Not sure what it is yet, but I'm pretty sure that some QR node module exists out there.

## Component Tree
![alt text](./assets/img/component_tree.jpg)

### Component Breakdown
* **APP:** Single common parent/ancestor for the entire application. Will hold state or Redux store and handle routing.
* **USER:** Container for User info and card(s).
* **CONTACTS:** Container for contact info and card(s)
* **CARDS:** Lists all cards belonging to user or contacts.
* **SCAN CARDS:** Adds new contact card to local storage and Contacts/Cards component list.
* **NEW CARD:** Add new user card to local storage and User/Cards component list.
* **CARD:** Displays complete info for individual contact or user card.
* **EDIT CARD:** Allows the user to edit card info or delete existing cards.
* **QR CODE:** Allows user card to be scanned by other devices. 


## Resources
* **Chart Making:** https://www.draw.io/
* **React Native Crash Course:** https://www.youtube.com/watch?v=qSRrxpdMpVc
* **react-native-qrcode(node package):** https://www.npmjs.com/package/react-native-qrcode
* **react-native-qrcode-svg(node package):** https://www.npmjs.com/package/react-native-qrcode-svg
