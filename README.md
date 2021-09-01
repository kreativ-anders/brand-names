# brand-names

* [What do you get?](#what-do-you-get)
* [Installation](#installation)
* [Notes](#notes)
* [Support](#support)  

## What do you get?
Sometimes brand icons are not enough. So brand names sometimes feel better.

## FORMAT GUIDLINE
All svg files follow this guidline:

1. Resize Page to brand/selection
2. Transform size to 250px width
3. Scale Page with the factor 1.2
4. Align brand/selection to center
5. Compress svg file

## INSTALLATION

### Download

1. Download the latest release .zip-file.
2. Unzip the files.
3. Paste wherever you need the folder to be.
4. Migrate in your project/app


### Git Submodule (Recommended)
You can add the repository as a git submodule as well:

#### Init

```Shell

$ cd YOUR/PROJECT/ROOT
$ git submodule add https://github.com/kreativ-anders/brand-names.git assets/brand-names
$ git submodule update --init --recursive
$ git commit -am "Add .svg brand names collection"

```

#### Update

Run these commands to update the repository (and all other submodules):

> main not "master"!

$ cd YOUR/PROJECT/ROOT
$ git submodule foreach git checkout main
$ git submodule foreach git pull
$ git commit -am "Update submodules"
$ git submodule update --init --recursive

## Notes:
This repository is just for decoration purposes. brand names may have a different license.


## Disclaimer

The source code is provided "as is" with no guarantee. Use it at your own risk and always test it yourself before using it in a production environment. If you find any issues, please create a new issue.

## Support

In case this Plug-In saved you some time and energy consider supporting kreativ-anders by donating via [PayPal](https://paypal.me/kreativanders), or becoming a **GitHub Sponsor**.