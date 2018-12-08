# Progressive-Web-App-weather
Progressive Web Apps are experiences that combine the best of the web and the best of apps.
https://codelabs.developers.google.com/codelabs/your-first-pwapp/index.html?index=..%2F..nodejs-interactive#0

1. Introduction
Progressive Web Apps are experiences that combine the best of the web and the best of apps. They are useful to users from the very first visit in a browser tab, no install required. As the user progressively builds a relationship with the app over time, it becomes more and more powerful. It loads quickly, even on flaky networks, sends relevant push notifications, has an icon on the home screen, and loads as a top-level, full screen experience.

What is a Progressive Web App?
A Progressive Web App is:

Progressive - Works for every user, regardless of browser choice because it's built with progressive enhancement as a core tenet.
Responsive - Fits any form factor: desktop, mobile, tablet, or whatever is next.
Connectivity independent - Enhanced with service workers to work offline or on low-quality networks.
App-like - Feels like an app, because the app shell model separates the application functionality from application content.
Fresh - Always up-to-date thanks to the service worker update process.
Safe - Served via HTTPS to prevent snooping and to ensure content hasn't been tampered with.
Discoverable - Is identifiable as an "application" thanks to W3C manifest and service worker registration scope, allowing search engines to find it.
Re-engageable - Makes re-engagement easy through features like push notifications.
Installable - Allows users to add apps they find most useful to their home screen without the hassle of an app store.
Linkable - Easily share the application via URL, does not require complex installation.
This codelab will walk you through creating your own Progressive Web App, including the design considerations, as well as implementation details, to ensure that your app meets the above key principles of a Progressive Web App.

Looking for more? Check out the talks from the 2016 Progressive Web App Summit.

What you will build
In this codelab, you're going to build a Weather web app using Progressive Web App techniques. Your app will:

Utilize and demonstrate the above principles of Progressive Web Apps.
Use live weather data.
Provide app-like interactions to allow the user to add cities.


What you'll learn
How to design and construct an app using the "app shell" method
How to make your app work offline
How to store data for later offline use
What you'll need
A recent version of Chrome. Note, this works in other browsers as well, but we'll be using a few features of the Chrome DevTools to better understand what's happening at the browser level.
Web Server for Chrome, or your own web server of choice
The sample code
A text editor
Basic knowledge of HTML, CSS, JavaScript, and Chrome DevTools
This codelab is focused on Progressive Web Apps. Non-relevant concepts and code blocks are glossed over and are provided for you to simply copy and paste.
