## Tourtellini

Professional development is a lot about setting goals and finding your way to your destination. Whether it is first day of classes in a new building on a part of campus you have never been to, or a job interview, making it there, and being early, are part of the preparation and expectations we set for ourselves, and each other. Being late or getting lost is a poor way of making a first impression, and not a habit that anyone wants to be associated with. **Never get lost on campus, or in life, again.**

## What it does

In explore mode, Tourtellini pinpoints your current location in real-time while interfacing with the Tourtellini backend to receive information about places around you (name, reviews, ratings, description), and then performs efficient computations to display information about them on your camera feed, letting you explore in augmented reality. In tour mode, Tourtellini leverages explore mode features while also allowing you to socialize with others by exploring places others go and recommend. 

## How we built it

Hard work and dedication. We used Discord and G Suite to collaborate, Figma for sketch and storyboards, and Adobe XD for mockups. Android studios, Java, Python, Flask, React, Radar.io, Google Cloud, Magnetometer, Accelerometer, Yelp API. 

## Challenges we ran into

These are the challenges we faced and how we got around or through them:
- Coursework and occupations: this isn’t original or personal to us alone, but by communicating we were able to use the time we had efficiently. 
- Different time zones: we were split between PST, CST, & MST
- Weird results at first for what the user was "looking" at that were caused by a bad assumption about the default coordinate system of the device leading to a "wrong" extrinsic matrix for the camera.
- (Re)Learning Google APIs on different platforms, web, android, backend.
- Tradeoffs between a larger building cache radius (causing slow client computations) vs. a smaller one (causing many backend requests which had somewhat high overhead, a problem for speedwalkers) -- this was solved by pre-optimizing client computations with a spatial index implemented with an RTree.

## Accomplishments that we're proud of

- Team cohesion
- Collaboration
- Commitment
- A fantastic working viable product

## What we learned

- Google APIs (Maps and Cloud)
- Multiple use cases
- Using the Magnetometer and Accelerometer

## What's next for Tourtellini

- Calendar integration
- Navigation arrow/paths
- Further develop website integrations
- Business Model

[Download APK](https://github.com/jamessnguyenn/Tourtellini-Public/releases/download/v.01/app-release.apk)
