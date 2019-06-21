# Yandex Metrica
This is an **unofficial** tag template for Yandex Metrica.

# Author
David Vallejo (https://www.thyngster.com/).

# Release notes
| Date | Notes |
|------|-------|
| 3 June 2019  | First version of the tag released. |
| 14 June 2019 | Updates, new features, bug fixes, check changelog. |

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

# ChangeLog 14 June 2019
- Fixed Ecommerce Setup . It was not being initilized.
- Minor UI Reorganization
- Added Session Parameters Tracking
- Added User Parameters Tracking
- Added userID Tracking
- Added not-Bounce Tracking
- Fixed Debug being reset on after init methods
