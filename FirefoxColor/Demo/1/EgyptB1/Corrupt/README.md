
***

# This theme is not corrupt

I have been meaning to get to this for a while, but the extension was just poorly documented. [My issue raised enough concern over at Mozilla for better documentation to be added for inexperienced extension developers/average computer users](https://github.com/mozilla/FirefoxColor/issues/971)

Firefox may tell you that the theme is corrupt upon loading. Here is how to load it (temporarily, as I have not signed it with [addons.mozilla.org](https://addons.mozilla.org) yet.

1. Go to `about:debugging` this is a URL, copy and paste it into your browser, or write it manually (it isn't that much to write)

2. Go to `[This Firefox]`

3. Click/tap on `[Load temporary add-on]`

4. Locate the theme

The theme should now be applied. It will work on your current browser session. You can change it and add it back at any time.

<!--

# This theme is corrupt

Please access the theme via the link given in the main `README.md` file. This corrupt theme is used as a demo to demonstrate that Firefox color is currently broken.

## Issue

[See my issue here](https://github.com/mozilla/FirefoxColor/issues/971) nobody has made enough of a fuss about it yet.

There has been an issue with Firefox color across Firefox 57 to 89 that not enough people have noted on the GitHub repository, which is that when you export a theme, you are given corrupted files that don't work, and don't contain your theme.

## Context

My issue:

```markdown

***

# Cannot export theme

This has been a common issue I have noted by looking at reviews from the past 7 months. I went to install this extension today, and I found that every time I exported the file, it said that it couldn't install the extension, as the extension was corrupt. I can confirm it is, as there is a <600 byte blank SVG file, and a normal JSON file. I am surprised that this isn't being reported as much as it should. I looked through issues before reporting, but couldn't find any recent ones mentioning this, so I will say it here. This may be a duplicate, as this apparently has been an issue for 7 months or more.

I tried to include a screenshot, but the error message goes away before my system can get a screenshot (using F10: PRT SC/Print Screen)

## Device specs

Browser version: Firefox Browser 87.0 for Ubuntu Linux 20.04.1
Operating system: Ubuntu Linux 20.04.1
DE: GNOME 3.36.1

***

```

!-->

***
