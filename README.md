# R4All website

The deployed website is served from branch `master`. The code for it is on the `sources` branch. At present its a bit of a pain to coordinate this, hence the master branch content may not be fully up to date with the code in the `sources` branch. So if you want to look a the latest version of the website, don't look at this https://r4all.github.io/website/welcome/ or the contents of the `master` branch. Instead, sync your local repo to github, and use `hugo serve` locally. This page describes how to streamline things a bit: https://proquestionasker.github.io/blog/Making_Site/ (not yet implemented).

If the site is built in RStudio with bookdown, then the Rmd files will be compiled properly. If built with hugo in the terminal, they won't.

(The site can be built by `hugo` from the terminal or from within RStudio with blogdown. However, the website index page will work or not, depending on which is used. Specifically, the `layouts/index.html` file specifies site `index.html` file, and at the moment redirect to the `welcome/index.html` page. To work when deployed to https://r4all.github.io/website the redirect must be to `/website/welcome/`. This redirect path doesn't work when the site is served in RStudio preview. You will see "Not found: ./website/welcome/". To preview with RStudio, in the Viewer window, click the button "Show in new window" and change the address from "http://127.0.0.1:4321/website/welcome/" to "http://127.0.0.1:4321/welcome/")



