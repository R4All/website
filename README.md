# R4All website

The website is served from branch `master`. The code for it is on the `sources` branch. At present its a bit of a pain to coordinate this, hence the master branch content may not be fully up to date with the code in the `sources` branch. So if you want to look a the latest version of the website, don't look at this https://r4all.github.io/website/welcome/ or the contents of the `master` branch. Instead, sync your local repo to github, and use `hugo serve` locally.

At present, the site is configured to work properly when built in the terminal with `hugo`. It doesn't work if one builds from RStudio using blogdown. Needs fixing, obviously.

This page describes how to streamline things a bit: https://proquestionasker.github.io/blog/Making_Site/