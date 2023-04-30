# Resources: Documentation

## What is a PWA ?

<br>

> A progressive web app (PWA) is a website that looks and behaves as if it is a mobile app. 

> PWAs are built to take advantage of native mobile device features, without requiring the end user to visit an app store, make a purchase and download software locally. 

> Instead, a PWA can be located with a search engine query and accessed immediately through a browser.

> Definition above is from [tech contributor to WhatIs.com](https://www.techtarget.com/whatis/definition/progressive-web-app-PWA#:~:text=A%20progressive%20web%20app%20\(PWA,it%20is%20a%20mobile%20app.)

<br>

## Benefits and drawbacks

<br>

`Benefits`

1. They eliminate the need for e-commerce merchants to develop native apps for multiple mobile operating systems.

2. They use standards-based technologies and run in a container that is secure and accessible to anyone on the web.

3. They can send web push notifications, work offline and be accessible from the home screen

4. They are easier to share, no need for installation of anything. 

5. TTR and loading times are instant

6. Fast, reliable and respond quickly to user interactions

<br>


`Drawbacks`

1. They have little to no access to native devices' hardware capabilities

<br>

### Components of a PWA


- `manifest.json`: json file that must contain everything about aesthetic. <br>
Icons, background colour, name among other properties

eg.

```json
{
    "name": "Weather",
    "short_name": "Weather",
    "icons": [
        {
            "src": "/images/icons/icon-128x128.png",
            "sizes": "128x128",
            "type": "image/png"
        },
        {
            "src": "/images/icons/icon-144x144.png",
            "sizes": "144x144",
            "type": "image/png"
        },
    ],
    "start_url": "/index.html",
    "display": "standalone",
    "background_color": "#3E4EB8",
    "theme_color": "#2F3BA2"
}
```

- `service-worker.js`: js file that operates alongside the browser to create a layer between your application and the network. <br>
Allowing notifications, fast loading, caching and background sync.

<br>

# Resources

- [PWA vs native app](https://www.magestore.com/blog/pwa-vs-native-app-and-how-to-choose-between-them/#:~:text=While%20native%20apps%20are%20written,HTML%2C%20CSS%2C%20and%20JavaScript)

- [How to convert next.js app to mobile application](https://plazagonzalo.medium.com/how-to-convert-your-next-js-application-to-android-and-ios-in-5-clicks-bd8d5fac690c)

- [What are PWAs](https://www.youtube.com/watch?v=3cIee4VfD9s&ab_channel=ABTube)

- [PWA vs native vs cross platform | best mobile app development approach?](https://www.youtube.com/watch?v=R_bBXHk33rk&ab_channel=CopperMobile)

- [Progressive web apps (PWA) vs native apps](https://www.youtube.com/watch?v=0EYGkXswYYM&ab_channel=GoingHeadlesswithJohn)

- []()