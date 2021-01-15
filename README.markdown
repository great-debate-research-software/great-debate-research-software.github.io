# EGU GDB Research Software

## Image candidates

https://www.flickr.com/photos/chap_d/16362223225/
https://pixabay.com/illustrations/binary-code-globe-africa-1695476/
https://pixabay.com/illustrations/binary-code-globe-africa-asia-1695475/

https://www.pexels.com/search/earth/
https://www.pexels.com/photo/planet-earth-close-up-photo-45208/


Site based on [Event Jekyll Theme](https://event-jekyll-theme.github.io).

## Installation

1. For first time user, you have to install Ruby and NodeJS. You may follow my installation guide in my [Jekyll tutorial](http://melvinchng.github.io/jekyll/installation.html#ruby-and-nodejs-installation) or [Ruby on Rails Tutorial](http://melvinchng.github.io/jekyll/RubyOnRailsInstallation.html) for Windows, Linux, and MacOS (installation videos are included).
2. Install Jekyll by using the command `gem install jekyll`.
3. Then, install Jekyll Sitemap and Jekyll SEO gems by using the command `gem install jekyll-sitemap` and `gem install jekyll-seo-tag`.
4. Start your localhost server by using the command `jekyll serve`. Make sure that you are at the root directory of your folder before using this command.
5. Your site should be accessible at `localhost:4000`.
6. For additional information about Jekyll, refer to the [official website](http://jekyllrb.com/). 

## Files Structure

- The main stylesheet is stored `/css/`.
- In `/css/img` you will find where the pictures are stored at, e.g. speakers.
- `__pages` is the folder for subpages.
- `_2016_data` and `_2017_data` are the folders that store each sections in home page. Those sections are can be removed by removing or commenting out the `include` code in  `_layout/home.html`.
- `_data/gdb_21/` contains `data` files for agenda, faqs, home about section data, speakers, and team members information. The data file is in the format of `.yml`. Folder names start with letters because otherwise there are liquid syntax errors.
- In order to view PDF correctly, sharing setting in Google Drive must set to "Public on the web".
