# Change Log
Any improvements made to this project will be documented here

## [0.6.0] - 2015-1-10
### Fixed
- index.js was wrapped in a closure which was quietly breaking everything
- Parsing now works correctly. Inline nunjucks tags should be handled correctly.

### Added
- A new test to ensure inline parsing works
- This changelog! 

## [0.6.1] - 2015-1-11
### Added
- New templates for tests

### Changed
- Cleaned up tests
- Updated readme to reflect latest changes

## [0.7.0] - 2015-1-11
### Added
- Can now provide a template to the markdown tag. i.e. ```{% markdown "post.md" %}```
- new tests
