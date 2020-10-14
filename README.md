Mini youtube app.

 1 . show a list of items - a list of videos.  
    A video must contain a property for lenght ( float) , a property for upload date (date) , a property for review.
    A review must have an array of comments. 
    A comment must have a property for description ( string ) , a property for user. 
    A user must have display name , email, password. 
 
2. add or edit item.
    A user can upload a video . 
    A user can deelte a video .
    A user can leave comments to a video.
3.authenticate user.
    For a user to upload a video he must log in.
    For a user to delete a video he must log in.
    For a user to comment he must log in.
    For a user to view a video he can either log in or view it without login in.
    
4.provide offline support - persist data on the local storage.
    If a user start a video it will be fetched in local storage until the video is fully finished.

5.provide online support - synchronize data to/from a remote location
    Videos are cloud/ server synced. 
    
6.use external services - e.g. show map coordinates on google maps, or send an email using gmail.

    For sign up a user must verify his email and phone number( if I can find a free service for phone verification).
 
7.use local services - e.g. camera, sensors.
    While viewing the video camera , sensors are active tracking the users eyes so the screen doesn't turn off.
 
8.use animations
    Fun and silly animation for video Feed ( when refreshing or swiping ) .
    

