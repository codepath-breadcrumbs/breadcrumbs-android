# Breadcrumbs

A journaling tool for expats on the move

## What we're about

Breadcrumbs is a tool designed around your offline, off-the-grid life, helping you to record memorable moments while you're away from home. Users can login in with the touch of a finger or a quick swipe pattern to see a list of their past check-ins. To check into a new location just click the (+) button and take a picture to remember where you've been. 

## User Stories

1. User can log in
    1. User can log in with a password
    2. After loging in user should see the main activity
    
2. Main activity shows a chronological list of previous check-ins
    1. Check-ins should show:
        * the date of the check-in
        * an image if an image exists
        * a map if there's a GPS coordinate
        * city or coordinate text if there is no internet signal
        * a list of journal entries
    2. An edit button is visible if the last check-in date is the current date
        * Upon clicking the button the edit activity is launched
        * All previous data for the date should be loaded and visible
    3. A create button is visible if there is no check-in for the current date
        * Upon clicking the button the create activity is launched

3. Add/Edit screen you can add and edit existing content
    1. Existing content
        * an image if an image exists
        * a map if there's a GPS coordinate
        * city or coordinate text if there is no internet signal
        * a list of journal entries
    2. There is a bottom action bar with Camera, Gallery, Text buttons
        1. Tapping camera pulls up the user's camera
        2. Tapping gallery pulls up user's camera roll to select a photo
        3. If a photo for the check-in currently exists it will be replace by the new addition
        4. Tapping text button adds a new block of editable text
    3. Clicking on an existing block of text allows you to edit it
    4. On create of the activity GPS location should be grabbed if in create mode
        * If editing an existing check-in don't take a new GPS location
    5. Long press on any element, map, photo, text to delete a block
    6. Tappign on an image brings up the photo activity
    
4. Photo activity shows the photo for a day in full screen
    1. There should be a back button to take user back to the edit/view for the given check-in
    
## Wireframes
### Login Activity
![login activity](https://github.com/codepath-breadcrumbs/breadcrumbs-android/blob/master/assets/LoginActivity.png?raw=true)

### Main Activity
![main activity](https://github.com/codepath-breadcrumbs/breadcrumbs-android/blob/master/assets/MainActivity.png?raw=true)

### Edit Activity
![edit activity](https://github.com/codepath-breadcrumbs/breadcrumbs-android/blob/master/assets/EditActivity.png?raw=true)

### Empty Edit Activity
![empty edit activity](https://github.com/codepath-breadcrumbs/breadcrumbs-android/blob/master/assets/EmptyEditActivity.png?raw=true)

### Photo Activity
![photo activity](https://github.com/codepath-breadcrumbs/breadcrumbs-android/blob/master/assets/PhotoActivity.png?raw=true)
