# Flare Create V1

Key properties:

  * Made with V1 in mind - MVP for employees and select prototype testers
  * High limit for text length
  * 1 picture per flare
  * No other media allowed

## Definitions

  * Create Button
    * Circular asset that opens create module when pressed
  * Friend Row
    * Scrollable row with icons of user's friends who have posted a flare in the last 24 hours


## UI

  * Create Button stays as the first button (left-most position) in the Friend Row
  * As the user scrolls through friend icons, Create Button should persist on top. Friend icons should flow underneath the Create Button
  * If we cannot fill the Friend Row, Create Button should still stay on the left most position
  * Tapping on Create Button will bring up the Create Box and iOS keyboard. Friend Row will be hidden behind the keyboard
 

## Create Box

Elements of Create Box:
  * Text Box
  * Icon for photo uploads
  * Public / Private toggle
  * Icon selector

Element Properties:
  * Text Box:
    * 700 character limit (Can be flexible in the future, but it'll be good to see if this is enough for most use cases. 5x twitter's limit)
    * Hint text: "What's happening?"
  * Photo:
    * Camera icon placed to the right of Text Box
    * One photo upload limit
    * Standard iOS photo selection / camera UI
    * After selection, photo thumbnail appears above text box. Size should be stretched to best fit width of Create Box. 
    * Thumbnail will have 'x' in top right corner for users to remove photo. If photo is removed, camera icon reappears
    * Flares with photo may be posted without text
  * Public / Private toggle
    * 


