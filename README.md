# solar pelican theme

Solar is a pelican theme designed for <https://solar.lowtechmagazine.com>. It is an attempt to radically reduce the energy use the associated with accessing our content. 

The theme is designed to be extremely light and give visitors insight into the material conditions of the hardware the website runs on.

To this end we've developed a [few custom pelican plugins](https://github.com/lowtechmag/solar-plugins) and [additional scripts](https://github.com/lowtechmag/materialserver).

## Installation of dependencies

This theme is based on Pelican and a few custom plugins.

To generate the website you will need to install some basic utilities. Instructions are for machines based on Debian stretch.

`sudo apt update && sudo apt install git python3-dev python3-setuptools python3-pip zlib1g-dev libjpeg-dev jq`

Installing pelican:

`sudo pip3 install wheel pelican markdown typogrify`

Installing dependencies for the plugins:
`sudo pip3 install Pillow bs4 git+https://www.github.com/hbldh/hitherdither webassets libsass cssmin`


