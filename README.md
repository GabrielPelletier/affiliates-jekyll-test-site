# Open Science Office Hours Website
Notes for developers

Built/Adapted from Affiliates - Free Jekyll Theme
[Live Demo](https://wowthemesnet.github.io/affiliates-jekyll-theme/) | [Docs & Download](https://bootstrapstarter.com/template-affiliates-bootstrap-jekyll/) |  [Buy me a coffee](https://www.wowthemes.net/donate/)

## Notes
* 3 types of content/pages

### Featured "posts" - actually Pages
* Displayed under the main hero block
* These are the Pages for the main Components of what OSOH does (Resources repository, One-on-One Support, ...)
* In the backend, located in _posts
* File name needs to start with a date (yyyy-mm-dd-) or it won't be displayed. The rest of the title is for you. 
* File Header:
  * Title: "The title that will be displayed"
  * Image: "The image that will be displayed"
  * Layout: pages
  * Featured: yes
  * Categories: (not needed)
  * Author: (not needed)
* Should be limited to 3 total with the current sizing of things

### Regular Posts - News and Events
* Displayed after the 'featured posts'
* These are more frequently added for Events, Theme of the Months, Other news...
* In the backend, located in _posts
  * Everything contained in _posts that is not a "Featured: yes" post will end up here. If you want to remove posts, you may move them in _posts/archive
* File name needs to start with a date (yyyy-mm-dd-) or it won't be displayed. The rest of the title is for you. 
* File Header:
  * Title: "The title that will be displayed"
  * Image: "The image that will be displayed"
  * Layout: pages
  * Featured: no
  * Categories: [caterogy1 caterory2] (Categories are important because you can browse posts by categories)
  * Author: 

### Pages listed in the top/right navigation menu
* These are links at the top-right of all pages, and may be use for general stuff; About, Get in Touch, Contribute, ...
* In the backend, located in pages (but not everything in Pages has to end up in the nav menu)
* What goes into the Nav Menu is configured in _data/menus.yml

