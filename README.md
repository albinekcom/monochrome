## About
Monochrome is a minimal, responsive, ready to use Jekyll theme for blogging. [Demo](https://dyutibarma.github.io/monochrome/)
(Built on top of Emerald Jekyll theme)

## Features

- Completely responsive and mobile first
- Clean SEO friendly URLs, auto-generated from post title (no messy dates in the url)
- SEO title/description integration
- Sitemap ready
- Pagination support
- Mobile friendly navigation menu
- Easy customization for header, footer, navigation links, colors, favicon etc
- Default Monochrome Color Palette - black, white, greys
- About page
- 404 page
- ..and a lot more

## Install/Setup Jekyll

(Skip if you already have Jekyll 2.2)

1. Make sure Ruby 2.2 is installed 
```
sudo apt-get install ruby2.2
sudo apt-get install ruby2.2-dev
```
2. Install bundle: `sudo gem install bundler`
3. Install jekyll: `sudo gem install jekyll`

### Resources

- We found the jekyll tutorials on youtube very quick and useful to get started
- [Jekyll documentation](http://jekyllrb.com)   


## Install Monochrome dependencies

```
sudo gem install jekyll-paginate
sudo gem install jekyll-sitemap
```

## Get Started with Monochrome

### Option 1 

- Fork this repository
- (Optional) Change the 'baseurl' value in the 'config.yml' file, from '/blog' to your preferred directory/project name (example '/xyz' or '/' to install in root)
- Clone the forked repository to your local machine to make changes
- Run 'jekyll serve' and open browser to 'localhost:4000/blog/' to see your changes
- (Optional) Host with github pages

Note: If you fork the repository, your version of the repository will not be searchable. If you want searchability, we suggest you use the next option.


### Option 2

- Simply download the .zip folder from the repository github page
- Extract the contents from the .zip folder into your local folder
- cd into monochrome/
- Run 'jekyll serve' and open browser to 'localhost:4000/blog/' to see your changes
- Create a repository in github and push the files
- (Optional) Host with github pages

## Write a Post

- cd into  ``_posts/``
- create new file with format yyyy-mm-dd-title-of-post.md
- add title/description (refer any of the test posts)
- add markdown and save


## Customization Options

You can customize this layout using instructions below. 

### Header/Footer/Navigation

Set a custom header tag by setting the related option in the ``_config.yml`` file to "true". Then insert your custom code into the ``header-custom.html`` file.
In the same way, you can customize the footer of the navigation menu, by setting to "true" the related option and put your code into the ``nav-footer-custom.html`` file.
Moreover select a reverse option that allows to move the navigation menu to the left side, by setting it to "true".

### Colors

The basic colors are set into the ``base.scss`` file:
- $background-color: used for background and links in the navigation menu
- $text-color: used for text and title in posts and pages 
- $text-light-color: used for text lighter than text-color
- $text-dark-color: used for text darker than text-color

To customize the colors, just set the values in HEX, RGB (or RGBa) or any other format accepted by CSS.

### Navigation menu

The links inside the navigation menu are autogenerated from pages having the layout set to ``page``.
You can set custom links, by putting in the ``<a>`` tag into the ``link.html`` file.

### Branch
There are two branches: 
- ``master``: is for development.
- ``gh-pages``: is only for demo site.  

### Baseurl

You can change the 'baseurl' value in the 'config.yml' file, from '/monochrome' to your preferred directory/project name (example '/xyz' or '/' to install in root)

### Typography

To maintain the vertical rhythm, it has been applied a **Typographic scale** as a modular scale, with a baseline set to 24px. To maintain this rhythm you need to insert elements like image, video or other contents with a 24px (or multiple) height as refer.

## Resources

- We found the jekyll tutorials on youtube very quick and useful to get started
- [Jekyll documentation](http://jekyllrb.com)   

## Todo

- Google Analytics integration
- Footer to stick to bottom even when content is less

## Author

### TheReviewIndex

- Dyuti Barma
- Web site: [Review Aggregation and Summary Site for India - TheReviewIndex.com](https://thereviewindex.com)

## License
Released under [MIT License](license.md).
