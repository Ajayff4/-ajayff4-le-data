# CHANGELOG

See commit history on Github for change history
https://github.com/Ajayff4/-ajayff4-le-data

## v1.0.8
### New
  - Added ๐ color module with rgb, hsl, and many more color spaces
  - Added ๐ id module with nanoid & uuid
  - Updated ๐ข number module with float, oct & hex
  - Playground updated with color, id, number module as well
### Docs
  - Badges & module examples has been updated in README
  - Project description has been moved to the top of README

## v1.0.7
### New
  - Added ๐ฒ game module โฃ๏ธ for dice roll, toss & cards
  - Playground updated with game module as well
### Docs
  - README got new badges for CI pipeline build & live code coverage
  - Playground example is updated
### Build
  - Github action has been added for build
  - Integrated Codecov app to Github to get code coverage
  - Added tsconfig.json & CHANGELOG.md to production build

## v1.0.6
### Playground
  - added Stackblitz to have some fun experiments ๐งช
### Docs
  - Stackblitz link has been added to README
### New
  - added customArray(), otp() methods in utils module
  - added options for seed() method in utils module

## v1.0.5-patch2
### Build
  - patched broken build again

## v1.0.5-patch1
### Build
  - patched broken build

## v1.0.5
### Docs
  - added **Credits Section** and **Logo** in README
  - added validations & unit tests for person module
### Fix
  - patched **sex** option in person module for typescript users, now it will simply give options of either **male**, **female** or undefined (in case of if we don't want to pass the sex option)

## v1.0.4
### Build
  - added zod for validation and error handling
  - added jest for unit testing
### Docs
  - README.md have new badge for version

## v1.0.3
### Build
  - Exposed types
### Fix
  - Added **sex** option on person.fullName() and fixed others **sex** flags
  - Rearranged person collections
  - Updated README.md
  - Added CODE_OF_CONDUCT.md

## v1.0.2
### Build
  - Build size is reduced.
### Fix
  - Updated README.md

## v1.0.1
### API
  - Added person module and utils module for data generation
### Fix
  - Added support for both ESM & CJS along with typings with/without typescript
### Dependencies
  - Integrated [tsup](https://www.npmjs.com/package/tsup) package bundler

## v1.0.0
  - Initial commit
