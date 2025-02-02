# Version History


## v5.6.2

- Updated the Google Analytics code. #189
- Added line-height properties to the headings. #190
- Fixed the page layout issue for the news blocks component. #201
- Fixed the page layout issue for the course list page (updated courses.scss). #202
- Removed a broken link on the Layouts landing page. #200
- Fixed a broken link to the Events page on the Layouts landing page. #203
- Removed an old carousel section from General Landing page. #204
- Fixed header stacking order bug in mobile. #209


## v5.6.1

- Icon updates: fixed badminton typo, added delete (trash can) icon.
- Added back-to-top button component.
- Fixed .btn-hover rounded corners on hover.
- Enclosed breadcrumbs in nav element and added aria-label="you are here".
- Removed outdated IE 10 SVG hack that throws CSS error.
- Restored panes component (it's now using pure CSS).
- Fixed the negative border radius value for cards.


## v5.6.0
        
Framework and components updates:
- Removed jQuery dependency and jQuery plugins.
- Updated Bootstrap to v5.1.3.
- Removed some jQuery dependent components such as: owl-carousels and slideshows (replaced with the native Bootstrap carousel), service tiles, and panes.
- Converted the following jQuery components to Vanilla JS: accordion, accordion list, fixed header, navigation, number counter, parallax, search, site settings, and tabs.
- Updated Bootstrap's collapse/expand data toggle attributes in collapse buttons and modals throughout the site. (For example, changed data-toggle="collapse" to data-bs-toggle="collapse", changed data-toggle="modal" to data-bs-toggle="modal".)
- Completely changed the accordion structure and code. It is now using the California Design System's accordion script.
- Updated side navigation structure to work with the new accordion component.
- Removed jQuery owl-carousels and slideshows and replaced them with the native Bootstrap carousel. 

Layout and structure updates:
- Added featured search header and icon-less navigation layout to every sample page. (Old v5.5 header and navigation layout are still in the navigation samples.)
- Updated badge classes to reflect new Bootstrap 5 markup (changed "label" class to "badge").
- Replaced outdated grid classes with the native Bootstrap grid classes. (For example, changed "group" class to "row", or "quarter" to "col-md-3".)
- Updated main banner height property (removed jQuery calculation and replaced it with pure CSS properties).
- Updated header position to sticky instead of fixed. The fixed-header.js script is now hiding utility header on scroll instead of adding compact class to header.

Font updates:
- Added Google font files to the local /fonts/ folder to limit http requests.
- Updated the icon font (added a GitHub icon and updated the pdf-text icon).
- Added responsive font size calculation functionality. Body text and heading font sizes and their top and bottom margins are automatically calculated into appropriate values based on the dimensions of the browser viewport.