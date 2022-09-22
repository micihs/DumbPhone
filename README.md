# DumbPhone - Philosophy
Dumbphone is intended to faciliate a larger desire of the Digital Wellbeing movement. 
[digitalcapability](https://digitalcapability.jisc.ac.uk/what-is-digital-capability/digital-wellbeing/)

Specifically the desire to disconnect from the larger theatre of media and consumer applications which have been built on the capability to capture a users attention and data. DumbPhone is intended to facilitate the conversion of a smartphone into a dumbphone (dumber phone) by blocking apps of a users choice, Rather than having to convert to an actual FlipPhone or dumbphone to achieve a simliar level of digital wellbeing.

This blocking is facilitated by the self-imposition of a "tax" or sur-charge for opening an application and persisting beyond the web proxy blokcing app sepcific data and content. Theoretically allowing a user to impose a financial price on the detriments of an app on their lifestyle.

# This Front-End
This is only the front-end of the larger project, the backend of the software suite is currently still in development and may take significantly longer than first estimated, as the author incorrectly predicted the frugality of time required to properly construct a backend with the Android/IOS firmwares. The initial backend was intended to facilitate the blocking of applications at a firmware level, this is largely bad practice as most Smartphone manufacturers Utillize either IOS or a specific Android ROM which does not allow this level of adminstrative control to Applications. Instead the backend design has taken on a more non-intuitive development path, specifically utillizing a Local VPN and Cover screen for blocking apps and their proccesses without having to access lower level code or engage in code anti-patterns.

This Application utilizes Firebase as a Login/Authentication and data store for the front end. As the application is not particularly data intensive firebase should be more than sufficient for scaling an app beyond several tens of thousands of active users. 

# Work In Progress 
---- This code has is currently a work in progress and should be finished within the next two week.
---- Construction and integration of a Backend API is currently being tested in a seperate repository.
