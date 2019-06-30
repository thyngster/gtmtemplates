# Yandex Metrica
This is an **unofficial** tag template for Yandex Metrica.

# Author
David Vallejo (https://www.thyngster.com/).

# Release notes
| Date | Notes |
|------|-------|
| 3 June 2019  | First version of the tag released. |
| 14 June 2019 | Updates, new features, bug fixes, check changelog. |
| 30 June 2019 | Fixed, new features, bug fixes, check changelog. |

# Details
See [this article](https://www.thyngster.com/google-tag-manager-custom-template-yandex-metrica/) for details about how the template works. 

# Currently Supported Tracking Features
- Pageviews
- Goals
- Outbound Links
- File Downloads
- Session Parameters
- User Parameters
- User ID
- Not Bounces
- Ecommerce Tracking ( based on a dataLayer )

# Settings supported
- Enable/Disable Click Maps
- Enable/Disable Webvisor
- Enable/Disable Accurate Bounce Rate Tracking
- Enable/Disable Links Tracking
- Enable/Disable Sending Pages to Yandex Index
- Enable/Disable Hashes Tracking
- Enable/Disable Library Loading from CDN 
- Enable/Disable Pageview defer ( not send a pageview on Init, for SPA sites )
- Enable/Disable Debugging Feature
- Enable triggerEvent on Yandex Metrica Ready
- Set Callbacks for hit, extLink,file, notBounce and reachGoal Methods

# Using the Callbacks
You need to create a new Custom JavaScript Variable: 
function(){
    return function(){ 
       [YOUR CALLBACK CODE]
    };
}

Then just use this variable within the "Hit Callback" textbox.

# ChangeLog 30 June 2019
- Fix: Goal Currency not being set properly.
- Fix: Goal Order_Price not being set properly.
- Fix: Hit URL not being set properly.
- Update: Tag Logo updated ( thanks to Artem Subbotin (https://github.com/subbbotin) ).
- Added Full Callbacks Support for hit, extLink,file, notBounce and - reachGoal Methods. ( they need to be set via a
- custom JS variable: function(){ return function(){ YOUR CALLBACK CODE}; }
- Added triggerEvent support. Metrica will fire an event named: "yacounter" + countID + "inited" when it's ready.

# ChangeLog 14 June 2019
- Fixed Ecommerce Setup . It was not being initilized.
- Minor UI Reorganization
- Added Session Parameters Tracking
- Added User Parameters Tracking
- Added userID Tracking
- Added not-Bounce Tracking
- Fixed Debug being reset on after init methods
