lib-neat
===

This is a replica of [Thoughtbot's Sass Neat library](https://github.com/thoughtbot/neat) but provided in a format that can be used as a submodule for other git projects to avoid having to add Neat files to source control.

Usage
---

### Adding as a submodule

To add this library as a submodule, execute the following commands inside of your project. This will add this library as a submodule and checkout the current 1.7.x version into a folder called "neat."

	git submodule add -b v1_7 https://github.com/Sujevo/lib-neat neat
	git submodule update --remote

You may replace `v1_7` with `v1_6` or `v1_5` if you would like to use an older Neat version. This repository will always use the most up to date version for the respective branch.

### Current Hosted Versions

| Version | Branch | Release Date  |
| ------- | ------ | ------------- |
| 1.7.1   | v1_7   | January 2014  |
| 1.6.0   | v1_6   | March 2014    |
| 1.5.1   | v1_5   | April 2014    |

## Credits

[![thoughtbot](http://images.thoughtbot.com/bourbon/thoughtbot-logo.svg)](http://thoughtbot.com)

Neat is maintained and funded by [thoughtbot, inc](http://thoughtbot.com). Tweet your questions or suggestions to [@bourbonsass](https://twitter.com/bourbonsass) and while you’re at it follow us too.

## License

Copyright © 2011–2014 [thoughtbot, inc](http://thoughtbot.com). Neat is free software, and may be redistributed under the terms specified in the [license](https://github.com/thoughtbot/neat/blob/master/LICENSE.md).
