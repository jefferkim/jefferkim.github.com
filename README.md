<<<<<<< HEAD
# Jekyll-Bootstrap

The quickest way to start and publish your Jekyll powered blog. 100% compatible with GitHub pages

## Usage

For all usage and documentation please see: <http://jekyllbootstrap.com>

## Version

0.3.0 - stable and versioned using [semantic versioning](http://semver.org/).

**NOTE:** 0.3.0 introduces a new theme which is not backwards compatible in the sense it won't _look_ like the old version.
However, the actual API has not changed at all.
You might want to run 0.3.0 in a branch to make sure you are ok with the theme design changes.

## Contributing 

This repository tracks 2 projects:

- **Jekyll-Bootstrap Framework.**  
  The framework for which users should clone and build their blog on top of is available in the master branch.
  
  To contribute to the framework please make sure to checkout your branch based on `jb-development`!!
  This is very important as it allows me to accept your pull request without having to publish a public version release.
  
  Small, atomic Features, bugs, etc.   
  Use the `jb-development` branch but note it will likely change fast as pull requests are accepted.   
  Please rebase as often as possible when working.   
  Work on small, atomic features/bugs to avoid upstream commits affecting/breaking your development work.
  
  For Big Features or major API extensions/edits:   
  This is the one case where I'll accept pull-requests based off the master branch.
  This allows you to work in isolation but it means I'll have to manually merge your work into the next public release.
  Translation : it might take a bit longer so please be patient! (but sincerely thank you).
 
- **Jekyll-Bootstrap Documentation Website.**    
  The documentation website at <http://jekyllbootstrap.com> is maintained in the gh-pages branch.
  Please fork and contribute documentation additions to this branch only.

The master and gh-pages branch do not share the same ancestry. Please treat them as completely separate git repositories!


## License

[MIT](http://opensource.org/licenses/MIT)
=======
This is a fully responsive theme for Jekyll + Jekyll-Bootstrap. It is built on top of [Twitter Bootstrap](http://twitter.github.com/bootstrap/).

![Screenshot](https://raw.github.com/dhulihan/hooligan/master/screenshot.png)

## Installation

	rake theme:install git="https://github.com/dhulihan/hooligan.git" 

## Preview

You can preview this theme at the [Jekyll-Bootstrap Theme Gallery](http://themes.jekyllbootstrap.com/preview/hooligan/).

## Extra Stuff
 
This theme has some optional configuration support for social buttons. Just add your provider and username to `_config.yml`, like so:

	author :
	  name : John Doe
	  email : blah@email.test 
	  github : johndoe
	  twitter : dhulihan
	  feedburner : johndoe
	  googleplus: johndoe
	  # Whatever you specify for the linkedin option will be placed after `www.linkedin.com/in/`
	  linkedin: johndoe

Icons with links to your profiles will then appear on the navbar. Your stalkers will *love* you for making things so easy!
>>>>>>> 4443358a5415e7dbd9173321a8bff1f7f4fbc27e
