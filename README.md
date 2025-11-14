# Brand Names - When icons are not enough

**✨ A stunning, manually crafted collection of 192 brand logos ✨**


* [What do you get?](#what-do-you-get)
* [Why Brand Names?](#why-brand-names)
* [Format guideline](#svg-format-guideline)
* [Installation](#installation)
* [Usage](#usage)
* [Legal & Disclaimer](#legal--disclaimer)
* [Support](#support)  

## What do you get?

A curated collection of high-quality SVG brand logos, optimized and ready to use in your projects. Each logo is carefully crafted and compressed for optimal performance while maintaining visual quality.

## Why Brand Names?

**Brand icons alone are often not enough.** While a simple icon might work in some contexts, using the full brand name provides:

- **Better Recognition**: Full brand names are instantly recognizable, even at smaller sizes
- **Professional Appearance**: Complete logos convey professionalism and attention to detail
- **Brand Guidelines Compliance**: Many brands require their full wordmark to be displayed
- **Accessibility**: Screen readers can better interpret text-based brand names
- **SEO Benefits**: Full brand names improve searchability and SEO

When you need to represent a brand authentically and professionally, brand names are the way to go.

## SVG format guideline

All `.svg` files follow this guideline (based on [Inkscape](https://inkscape.org/)):

1. Resize Page to brand/selection.
2. Transform size to 250px width.
3. Scale Page with the factor 1.2.
4. Align brand/selection to center.
5. Compress svg file (with any tool you prefer, e.g. [SVGOMG](https://jakearchibald.github.io/svgomg/))

## Installation

> No CDN usage available at the moment!

### Download

1. Download the latest release .zip-file.
2. Unzip the files.
3. Paste wherever you need the folder to be.
4. Migrate in your project/app.

### Git Submodule (Recommended)

#### Init

```Shell

$ cd YOUR/PROJECT/ROOT
$ git submodule add https://github.com/kreativ-anders/brand-names.git assets/brand-names
$ git submodule update --init --recursive
$ git commit -am "Add .svg brand names collection"

```

#### Update

Run these commands to update the repository (and all other submodules):

> **main** not "master"!

```Shell

$ cd YOUR/PROJECT/ROOT
$ git submodule foreach git checkout main
$ git submodule foreach git pull
$ git commit -am "Update submodules"
$ git submodule update --init --recursive

```

## Usage

Add to your CSS like ...

```CSS
div[brand*=BRAND-NAME] {
 background-image: url("//assets/brand-names/BRAND-NAME.svg");
}

```

Or directly in HTML:

```HTML
<img src="path/to/brand-names/google.svg" alt="Google">
```

## Legal & Disclaimer

### ⚠️ Important Legal Notice

**This repository is provided for decoration and educational purposes only.**

- **No Affiliation**: The creator and maintainers of this repository are **not affiliated, associated, authorized, endorsed by, or in any way officially connected** with any of the brands represented in this collection.
- **Trademark Rights**: All brand names, logos, and trademarks are the property of their respective owners. Use of these logos does not imply any endorsement or partnership.
- **Use at Your Own Risk**: Before using any logo in a commercial project, ensure you have the legal right to do so and comply with the brand's usage guidelines and trademark policies.
- **No Warranty**: This collection is provided "as is" without any warranty or guarantee of accuracy, completeness, or fitness for a particular purpose.

### Responsible Usage

- Always check the official brand guidelines before using any logo
- Respect trademark laws and intellectual property rights
- Use these logos responsibly and ethically
- Do not use them in ways that could be misleading or cause confusion about affiliation

### Update/Removal of Brands

If you are an authorized representative of a brand and wish to request an update or removal of your brand's logo, please contact: **brand-names at kreativ-anders dot de** with:
- Your affiliation with the company
- The specific brand/logo in question
- Your request and reasons

We will respond promptly to all legitimate requests.

## Notes

This repository is just for decoration purposes. Brand names may have different licenses. Use with caution.

## Support

In case this repository saved you some time and energy consider supporting kreativ-anders by donating via [PayPal](https://paypal.me/kreativanders), or becoming a **GitHub Sponsor**.
