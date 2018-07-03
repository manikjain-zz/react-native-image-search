# react-native-image-search

## Note

`CLIENT_ID` and `CLIENT_SECRET` (from Shutterstock) need to be provided to the `auth: { username: CLIENT_ID, password: CLIENT_SECRET }` part of axios GET request in `images.js`.

While it is not recommended to store like this on the front-end, I did it here just to keep it simple. In real world, such creds should never be exposed on the client side.

## Screens

* Type a keyword(s) and tap 'Search Images'.

![screenshot at jul 03 09-52-49](https://user-images.githubusercontent.com/21245503/42198789-e0abf36a-7ea7-11e8-8ad0-b3a4d540415b.png)

* A new screen with the search results will appear to load.

![screenshot at jul 03 09-53-21](https://user-images.githubusercontent.com/21245503/42198797-e90955f2-7ea7-11e8-898e-8a8f99f0ceab.png)

* Results for the keyword used.

![screenshot at jul 03 09-53-38](https://user-images.githubusercontent.com/21245503/42198801-ec60c794-7ea7-11e8-9bb4-ba0493d32f3f.png)

* Scroll infinitely for all entries. A loading icon appears as it fetches new entries.

![screenshot at jul 03 09-54-23](https://user-images.githubusercontent.com/21245503/42198804-f3062dfa-7ea7-11e8-8251-2d18138c14a2.png)
