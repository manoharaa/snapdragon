# ChangeLog

The following are lists of the notable changes included with each release.
This is inteded to help keep people informed about notable changes between
versions as well as provide a rough history.

#### Next Release

#### v0.1.5

* Jasmine runner now hosts files in CWD under `/:path` ([\#12](http://github.com/reachlocal/snapdragon/issues/12))

#### v0.1.4

* Resolved some path expansion issues

#### v0.1.3

* Made Capybara wait for test output to finish before killing session

#### v0.1.2

* Reworked styled and colored output to work with Jasmine v1.3.1
* Switch to include latest stable Jasmine v1.3.1

#### v0.1.1

* Added jasmine-core to gemspec to resolve epic failure when running
  `snapdragon` or `snapdragon_server`

#### v0.1.0

* Provided initial README.md for documentation
  ([\#2](http://github.com/reachlocal/snapdragon/issues/2))
* Added styled and colored output matching RSpec style output.
* Added latest master branch of Jasmine as the included test framework
* Added support for spec.js file arguements to `snapdragon` &
  `snapdragon_server`
* Added support for spec directory arguements to `snapdragon` &
  `snapdragon_server`
* Added support for spec.js:line_number arguements to `snapdragon` &
  `snapdragon_server`
* Added `// require_relative()` directive to load required dependencies
* Added the basic `snapdragon` command line tool
* Added the basic `snapdragon_server` command line tool
