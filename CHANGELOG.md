# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

### Changed

### Removed

## [0.77.0] - 2022-01-27

### Added

- dashboard sidebar with files by team
- dashboard files view by team
- edit file functionality

## [0.76.0] - 2022-01-18

### Added

- settings sidebar
- teams view
- create team
- add members to team
- delete team member
- update team member
- limit user actions with permissions 

## [0.75.0] - 2022-01-15

### Changed

- New architecture for home page
- Mobile styles for home page

## [0.74.1] - 2021-01-14

### Added

- file preview to table view
- file query key to corresponding queries
- files query invalidate at preview update

### Changed 

- preview image styles in grid view
- set interval into hook


## [0.74.0] - 2022-01-14

### Added

- `parse-test` route now saves the link in a search param for easier share of files.

### Changed

- Rename prepare node to preprocess
- Rename parse node to process
- Move decamelize keys logic to postprocess pass

## [0.72.0] - 2022-01-13

### Added

- clearbit script

## [0.71.0] - 2021-12-22

### Added

- mj-text, mj-button: line height automatically adjusted (and info message)
- Link removed on underlined text

## [0.70.0] - 2021-12-20

### Added

- mj-section, mj-wrapper - Background image

## [0.69.0] - 2021-12-17

### Added

- logic for preview images update

## [0.68.0] - 2021-12-15

### Removed

- mj-raw - Default padding

### Fixed

- mj-text - Last character duplicated

## [0.67.0] - 2021-12-14

### Added

- Error message about auto layout
- Error message about missing text on mj-button

### Fixed

- Full clickable mj-button

## [0.66.1] - 2021-12-10

### Changed

- Breakpoint changed in media query (MJML output code)

## [0.66.0] - 2021-12-08

### Changed

- figma link node for specific frame node

## [0.65.0] - 2021-12-08

### Added

- Padding on mj-column

### Fixed

- Mobile CSS class for mj-section with hero image

## [0.64.1] - 2021-12-08

### Fixed

- Default value in sort dropdown not appearing

## [0.64.0] - 2021-12-08

### Fixed

- Bug adjusting column width

## [0.63.0] - 2021-12-07

### Changed

- mj-text - Padding left/right = 0
- Padding based on tag name

## [0.62.0] - 2021-12-06

### Changed

- Card styles to match design system

## [0.61.0] - 2021-12-03

### Added

- View selection funcitonality
- FilesTable component

## [0.60.1] - 2021-12-03

### Changed

- Update SEO preview image

## [0.60.0] - 2021-12-03

### Added

- File sorting functionality in dashboard

## [0.59.0] - 2021-12-02

### Added

- Main warning and error messages added

## [0.58.0] - 2021-12-01

### Added

- New route /process/fileId

### Changed

- Regenerate file now uses the refresh API
- After creating a file not you are redirected to the process file route

## [0.57.2] - 2021-11-29

### Added

- mj-wrapper - Border

### Change

- Swap create file tutorial image for html elements

## [0.57.1] - 2021-11-26

### Changed

- mj-button - Padding default
- mj-button - Background color default

## [0.57.0] - 2021-11-25

### Added

- Support for mj-group

### Changed

- Column width as percentage

### Fixed

- Issue with text on mj-button

## [0.56.0] - 2021-11-25

### Added

- Messages system to figma parser
- parse-test route to quickly test the parsing logic

## [0.55.0] - 2021-11-24

### Added

- Support for mj-spacer
- Support for Emailify components

### Changed

- Horizontal spacing using a mj-column/mj-spacer
- Left and right padding on mobile for "Hero images"
- Button size on mobile

### Fixed

- Spacing between social icons

## [0.54.0] - 2021-11-22

### Added

- Social SEO tags

### Changed

- New site title and description

## [0.53.1] - 2021-11-19

### Changed

- Refactor on function for alignment

## Fixed

- Padding on containers (mj-wrapper, mj-section)

## [0.53.0] - 2021-11-19

### Added

- Vertical spacing between sections

## [0.52.0] - 2021-11-19

### Changed

- Allow more than one node to be returned form a parser node

## [0.51.0] - 2021-11-18

### Changed

- Grab the file preview from the backend

## [0.50.0] - 2021-11-19

### Changed

- Basic CSS classes for mobile

## [0.49.3] - 2021-11-18

### Changed

- Refactor parsing logic

## [0.49.2] - 2021-11-17

### Changed

- Swap community file link

### Fixed

- External link button not working

## [0.49.1] - 2021-11-16

### Added

- Validation for safe fonts `['arial', 'courier', 'verdana', 'helvetica', 'times new roman', 'georgia', 'tahoma', 'lucida', 'trebuchet']`
- Validation for fonts where the user implements image slices method

## [0.49.0] - 2021-11-13

### Changed

- Padding between mj-columns
- Padding between content elements (mj-image, mj-text, mj-button, etc)
- Padding on containers (mj-section and mj-wrapper)

## [0.48.0] - 2021-11-11

### Added

- Refresh file button on file dropdown

### Fixed

- Scroll on frame selection overflow

### Removed

- Compare slider

## [0.47.0] - 2021-11-05

### Changed

- mj-social-element as image

### Fixed

- Component names from Figma (Pattern: text-text%)

## [0.46.0] - 2021-11-03

### Added

- Image preview max-width

## [0.45.0] - 2021-11-03

### Added

- Alignment on mj-images
- Dictionaries for MJML component names (to prevent error typing)
- Error message (when not possible to convert)

### Fixed

- Order of MJML components

## [0.44.3] - 2021-11-03

### Fixed

- Change `Delete DB` to `Delete {name of file}` dialog title

## [0.44.2] - 2021-11-01

### Fixed

- Safari issues with trailing slash

## [0.44.1] - 2021-10-29

### Added

- Inner padding 0 by default in mj-button

## [0.44.0] - 2021-10-27

### Added

- Add user info to heap analytics

## [0.43.2] - 2021-10-28

### Fixed

- Inverted columns
- Break lines in text

## [0.43.1] - 2021-10-27

### Changed

- Google Analytics tracking code

## [0.43.0] - 2021-10-27

### Added

- Artboard as mj-body

### Fixed

- Text transform

## [0.42.0] - 2021-10-26

### Added

- Support for complex objects from figma as images

## [0.41.1] - 2021-10-26

### Added

- Documentation link on user menu

### Changed

- Comunity file url to login page button
- Comunity file new URL and set as env variable
- Cannoli white logo on public page
- Scalero logo on public page

## [0.41.0] - 2021-10-26

### Added

- Google Analytics to production and dev environments

## [0.40.1] - 2021-10-25

### Changed

- Update all forno components to follow new org name
- Update eslint config to follor new org name

## [0.40.0] - 2021-10-22

### Added

- User avatar container
- User avatar form
- User intragrations form
- <hr/> styles
- File upload component

### Changed

- Profile page
- Header private avatar
- Replaced button group for forno button group

## [0.39.0] - 2021-10-21

### Added

- Support for mj-social component

### Fixed

- Google font name with spaces (Google font link)

## [0.38.0] - 2021-10-20

### Added

- Different text styles in the same paragraph (mj-text)

## [0.37.1] - 2021-10-19

### Fixed

- Default format string date crashing

## [0.37.0] - 2021-10-19

### Added

- Save indicator on editor header

### Removed

- Save button on editor header

## [0.36] - 2021-10-19

### Added

- Alt on mj-images
- Basic css classes for mobile
- White background color by default on mj-button
- Validation for mj-text and mj-images when the component name is not specified

### Changed

- Width and height rounded to the nearest integer (mjml components)

## [0.35.0] - 2021-10-18

### Added

- Download option for HTML/MJML

## [0.34.0] - 2021-10-15

### Added

- Resize columns functionallity on editor
- Full page loading component
- Devices buttons on editor header
- Preview size observer on editor header

### Changed

- Replace editor loading spinner for full page loading
- Replace create file form loading button for full page loading
- Button groups on the editor header are no longer Radio buttons
- Preview column no longer has restricted width
- Changed text from New File from figma -> New project from Figma file on dashboard
- Changed Icon on create file form from CodeIcon -> Plus circle Icon

## [0.33.1] - 2021-10-14

### Fixed

- When parsing fail add `<mj-body/>` to the basic MJML template

## [0.33.0] - 2021-10-14

### Added

- Editor menu with actions for

  - Copy HTML to clipboard
  - Copy MJML to clipboard
  - Open Origial Figma File

- Editor header with
  - File name
  - Export and save buttons
  - Back button

### Changed

- Renamaed button group title to Layout
- Beautify HTML using MJML tools (Need to change as it's marqued as deprecated)

## [0.32.0] - 2021-10-13

### Added

- New tutorial image on create file screen

## [0.31.0] - 2021-10-13

### Added

- New button group component
- New code toggle options
- New view radio button options

### Changed

- Now files are saved their MJML on creation
- New editor screen architecture that allows for more complex behaviour and reduces iFrame flashing
- Parsing unsuported files now returns a basic MJML template

## [0.30.3] - 2021-10-13

### Added

- Border in mj-section, mj-columns and mj-button
- href attribute in mj-image
- width attribute in mj-columns
- Padding bottom (space between elements inside a column: mj-divider, mj-image, mj-text and mj-button)
- Default padding=0 from mj-attributes

### Changed

- Default breakpoint

### Fixed

- Alignment on mj-button

### Removed

- Border radius in mj-divider (the component does not support that style)

## [0.30.2] - 2021-10-11

### Fixed

- Fix Heap configuration per environment. NODE_ENV being override

## [0.30.1] - 2021-10-10

### Fixed

- Heap configuration per environment

## [0.30.0] - 2021-10-01

### Added

- Errors on initial mjml parsing to code editor
- Name to create file form

### Changed

- Replaced comparison slider
- Add doc to editor context

### Error

- Remove node outliner, preview and inspector
- Remove Error footer

## [0.29.2] - 2021-10-01

### Fixed

- Home page style size issues

## [0.29.1] - 2021-09-29

### Added

- Border radius in mj-button

## [0.29.0] - 2021-09-29

### Added

- Wait for image fetching before redirecting to editor

## [0.28.6] - 2021-09-29

### Added

- Styles for mj-button

## [0.28.5] - 2021-09-29

### Changed

- Replaced cannoli dropdown for forno dropdown
- Update forno dependencies with dark theme support

## [0.28.4] - 2021-09-28

### Changed

- Home page and Login page Footer to be consistent
- Demo screenshot to video

### Fixed

- Code editor delay/jumping cursor issues

## [0.28.3] - 2021-09-28

### Fixed

- Ids showing in the mjml editor

## [0.28.2] - 2021-09-28

### Fixed

- New API endpoints

## [0.28.1] - 2021-09-27

### Fixed

- Font weight order in Google font link

## [0.28.0] - 2021-09-26

### Added

- Heap analytics

## [0.27.1] - 2021-09-27

### Fixed

- Minor Home page and overall style issues

## [0.27.0] - 2021-09-24

### Added

- New editor logic for storing changes in the backend

### Changed

- File cards now link to new editor route
- On create file redirect to new editor route

## [0.26.3] - 2021-09-24

### Fixed

- Refresh token logic fixes

## [0.26.2] - 2021-09-24

### Added

- Support for custom query key on figma queries

### Changed

- Stop reruning editor queries on windows focus

## [0.26.1] - 2021-09-24

### Fixed

- Google font API URL fixes

## [0.26.0] - 2021-09-23

### Added

- User profile page
- User hooks
- User form

### Fixed

- Token expiricy new logic

## [0.25.0] - 2021-09-23

### Added

- Support for refresh tokens
- Support for catch-all route

### Changed

- New styles for file cards

## [0.24.0] - 2021-09-22

### Added

- New code editor based on ace-editor

### Changed

- Node header component without nested button
- New file card styles
- File cards now get their image from figma

### Fixed

- Only preview mode not being centered
- Styling issues on editor screen

## [0.23.3] - 2021-09-22

### Fixed

- Downgrade code-mirror to 5.62.3

## [0.23.2] - 2021-09-22

### Fixed

- Fix auth destructuring

## [0.23.1] - 2021-09-22

### Added

- App version to title and log

### Fixed

- Code editor forward ref

## [0.23.0] - 2021-09-22

### Added

- New file create page
- New frame select input
- New page select input

### Changed

- Replaced input component for forno input component
- Replaced spinner for forno spinner component
- Node/File/Image queries now use the proxy end point
- Add header to editor screen
- Onboarding page layout based on new design

### Removed

- Frame select page

## [0.22.2] - 2021-09-22

### Fixed

- Home page, images and subscription form styles

## [0.22.1] - 2021-09-22

### Changed

- Update forno button to support dark theme

## [0.22.0] - 2021-09-19

### Added

- Home page, images and font
- UserMenu component
- Reach UI Menu components
- App name to meta tags

### Changed

- Migrated to Forno DS Buttons instead of wrapper
- HeaderPrivate logic and components

### Removed

- Button component/wrapper

## [0.21.1] - 2021-09-17

### Fixed

- Auth callback via request

## [0.21.0] - 2021-09-15

### Added

- Use Forno button
- Use Forno Spinner
- Use Forno design tokens

## [0.20.0] - 2021-09-10

### Added

- Login page (provisional style)
- Backend proxy for Figma login

### Changed

- Locked mjml-browser version to avoid patching issues

## [0.19.1] - 2021-09-09

### Added

- Scalero lint rules and npm config
- New readme instructions

## [0.19.0] - 2021-09-08

### Added

- Forno design tokens

### Removed

- Emotion

## [0.18.0] - 2021-09-06

### Added

- Mjml editing support
- just-debounce-it library

## [0.17.0] - 2021-09-01

### Added

- Add data ids to mjml and output html
- Add nodes, clean html and render html to the editor initializer method

### Removed

- Unnecessary mjml (server) library

## [0.16.0] - 2021-07-26

### Changed

- Add padding 0 as default to all mj-components
- Add width to mj-body
- Remove height from mj-image

## [0.15.0] - 2021-07-25

### Added

- Image loading for mjml code
- Padding logic for mjml components
- Alignment logic for mjml components
- Preview mode
- Allow only the preview to be visible
- Image preview mode

### Changed

- Improve hero mj component

## [0.14.1] - 2021-07-19

### Changed

- Update dependencies

## [0.14.0] - 2021-07-19

### Added

- Support for mjml-text color
- Support for mjml-divider width, style and color

### Changed

- Moved parsing logic to a new module `lib/figma-to-mjml`
- Moved logic for parsing figma files in to individual components similar to how react works
- Refactor color and text parsing modules

## [0.13.0] - 2021-07-18

### Added

- Text align style
- Font family from google fonts
- Font weight style

## [0.12.0] - 2021-07-12

### Added

- Fallback for unsuported figma files
- View the figma JSON from the UI
- Inspector nodes now have a sperate button for collapsing
- Removed the checkbox

## [0.10.0] - 2021-07-04

### Changed

- Swaped mjml parsing engine

## [0.10.0] - 2021-06-27

### Added

- Added mjml base code generation

## [0.9.1] - 2021-06-06

### Fixed

- Handle auto layout when it's distribution is space bewtween

## [0.9.0] - 2021-06-30

### Added

- Layout inspector
- Auto layout inspector
- Icon options
- Icon grid options

## [0.8.0] - 2021-06-23

### Added

- Stroke properties
- Text inspector
  - Font Family
  - Font weight
  - Font size
  - Line height
  - Letter spacing
  - Align horizontally
  - Align Vertically
  - Paragrpah Spacing
  - Text characters
- Blend mode names to titlecase

## [0.7.0] - 2021-06-17

### Added

- Inspector for bounding box
- Inspector for fill colors
  - Solid color
  - Linear Gradient Color
  - Radial Gradient Color
  - Partial Support for image fills
- Inspector for stroke colors

## [0.6.0] - 2021-06-04

### Added

- Editor page loading the file and frame selected
- Editor Outliner
- Editor Node
- Editor Inspector
- Editor context
- Outliner component
- Node component

### Changed

- Renamed Frame preview to Node preview

## [0.5.0] - 2021-05-31

### Added

- Frame selection screen
- Onboarding layout
- Node hooks
- Images hooks
- Import File form
- Select Frame form

### Changed

- New login page
- New file selection page

## [0.4.0] - 2021-05-31

### Added

- Input custom component
- Radio Button Group custom component

### Changed

- Dashboard input to use custom component

## [0.3.0] - 2021-05-21

### Added

- Login with figma
- Fetch file info

## [0.2.0] - 2021-05-21

### Added

- Design system colors, fonts and spacing variables
- Design system initial components: Button, Dropdown, Checkbox, Alert and Modal

## [0.0.1] - 2021-05-11

- Initial setup
