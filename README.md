# PROJECT PLANNING
## Overview
Alright, let's try this again. Rather than make a digital comic book platform (for now), the goal has been shifted to create a React Native mobile app that will, essentially, allow users to store their own, and other's, business cards, as well as pass their's along to anyone they desire. No more fuss about carrying physical business cards, or whether or not you have any on you at any given point in time. Ideally, this app will run mostly(if not entirely) off of the local storage of the device with no access to the internet required (outside of the initial download). Also, users of this app should be able to broadcast their business cards to anyone with a device regardless of whether or not they have an app. Also, the user with the app should be able to organize business cards into arbitrary categories or designations (possibly with tagging)

## Primary Technologies
* **React Native:** The primary library for creating this mobile app.
* **Some QR Module:** Not sure what it is yet, but I'm pretty sure that some QR node module exists out there.

## Component Tree
![alt text](./assets/img/component_tree.jpg)

### Component Breakdown
* **App:** Single common parent/ancestor for the entire application. Will hold state or Redux store and handle routing.
* **Public:** Contains all public-facing comics and data for viewing and use without user login or specific user privileges.
* **User:** Contains all user-oriented comics and data for viewing only by specified user.
* **Comic List:** Contains all data/comics for reading
* **Comic Preview:** A card previewing the comic's cover and relevant information (name, issue, etc.)
* **Comic:** The rendered images/pages of the comic for viewing.

## Resources
* **Chart Making:** https://www.draw.io/
* **A-Frame:** https://aframe.io/
* **React 360:** https://medium.com/better-programming/exploring-react-360-vr-library-7260d51dc776
* **React/PostgreSQL Tutorial:** https://www.youtube.com/watch?v=2oAS7MtMwqA
* **Comic Book Archive file type (.cbr, .cbz):** https://en.wikipedia.org/wiki/Comic_book_archive
* **Connecting Ruby to React:** https://medium.com/quick-code/simple-rails-crud-app-with-react-frontend-using-react-rails-gem-b708b89a9419
