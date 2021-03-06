# Soda SolarizedLight Theme

Solarized Light custom UI theme for Sublime Text 2 and Sublime Text 3.

Project site: [https://github.com/zcox/soda-solarized-light-theme](https://github.com/zcox/soda-solarized-light-theme)

Created by applying [solarized light](http://ethanschoonover.com/solarized) colors to [https://github.com/electricgraffitti/soda-solarized-dark-theme](https://github.com/electricgraffitti/soda-solarized-dark-theme).

## Design

![Soda SolarizedLight Theme](img/screenshot2.png)

## Installation

Soda SolarizedLight theme is designed to work with the latest development builds of Sublime Text, including [Sublime Text 2](http://www.sublimetext.com/dev) and [Sublime Text 3](http://www.sublimetext.com/3dev).

### Using Sublime Package Control

NOTE - this is not working yet!!!!!!!!!! Use Git instructions below!!!!!!!!!!!!!!!!1

If you are using Will Bond's excellent [Sublime Package Control](http://wbond.net/sublime_packages/package_control), you can easily install Soda SolarizedLight Theme via the `Package Control: Install Package` menu item. The Soda Theme package is listed as `Theme - Soda SolarizedLight` in the packages list.

### Using Git

Alternatively, if you are a git user, you can install the theme and keep up to date by cloning the repo directly into your `Packages` directory in the Sublime Text application settings area.

You can locate your Sublime Text `Packages` directory by using the menu item `Preferences -> Browse Packages...`.

While inside the `Packages` directory, clone the theme repository using the command below:

    git clone https://github.com/zcox/soda-solarized-light-theme "Theme - Soda SolarizedLight"


## Activating the theme

* Open your User Settings Preferences file `Sublime Text -> Preferences -> Settings - User`
* Add (or update) your theme entry to be  `"theme": "Soda SolarizedLight.sublime-theme"`

**Example Sublime Text 2/3 User Settings**

    {
        "theme": "Soda SolarizedLight.sublime-theme",
        "color_scheme": "Packages/Solarized Color Scheme/Solarized (light).tmTheme",
    }

## Additional Features

### Alternate Tab Styles

Soda SolarizedLight Theme ships with flat tabs only at this time.

### Syntax Highlighting Colour Schemes

* The color scheme used in Solarized(Light)

### Code Font

The code font shown in the screenshot is [Hack](http://sourcefoundry.org/hack/).

## Thanks

Thanks to Ian Hill for his excellent Soda Theme to build from, and electricgraffitti for his excellent port to Solarized Dark.

## License

Soda Theme is licensed under the [Creative Commons Attribution-ShareAlike 3.0 License](http://creativecommons.org/licenses/by-sa/3.0/). You are free to share and remix the theme, however please abide by the license terms when doing so.

The following details apply to the Creative Commons license "author specified" components:

* Attribution example: Based on Soda Theme by Ian Hill (http://buymeasoda.com/)

* Naming guidelines: If you create and distribute a derivative theme, please give your theme a unique and original name that does not directly include "Soda Theme" (or a close variant) in the main project title, repo name or Package Control name.
