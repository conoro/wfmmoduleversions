# wfmmoduleversions
Find what WFM/Raincatcher module versions were shipped with each version of RHMAP

See http://feedhenry.org/

It grabs all of the tags from https://api.github.com/repos/feedhenry-raincatcher/raincatcher-demo-cloud/tags

Then it retrives the package.json for the tag you select in the dropdown for each of:

* https://github.com/feedhenry-raincatcher/raincatcher-demo-cloud
* https://github.com/feedhenry-raincatcher/raincatcher-demo-mobile
* https://github.com/feedhenry-raincatcher/raincatcher-demo-portal
* https://github.com/feedhenry-raincatcher/raincatcher-demo-auth

And shows the versions.
