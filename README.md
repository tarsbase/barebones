# README

# Dark Portfolio Template For Jekyll

[**Click here for demo site**](https://shenchingtou.github.io/barebones-dark-portfolio-jekyll/)

A starter single-page site respository using the Jekyll static site generator for Github Pages.

This uses:
- W3CSS Dark Portfolio Template: [Demo](https://www.w3schools.com/w3css/tryw3css_templates_dark_portfolio.htm) / [Sandbox](https://www.w3schools.com/w3css/tryit.asp?filename=tryw3css_templates_dark_portfolio&stacked=h)
- [Barebones Jekyll](https://github.com/msiebert/barebones-jekyll)
- An updated Gemlock from [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/)
- It also takes inspiration from [Dark Portfolio Template for 11ty](https://github.com/jmschrack/Dark-Portfolio-Template-11ty/blob/dev/README.md)


## Features
- [Jekyll-SEO-tags](https://github.com/jekyll/jekyll-seo-tag/blob/master/docs/usage.md)

Unlike the original 11ty Blog, this is **not** a full-featured blog. This is a single-page site.

**Missing features** from the Eleventy blog template:
- Posts
- Archive
- Feed
- Map social icons to config file



## Getting Started

### 1. Clone this Repository

```
git clone https://github.com/shenchingtou/dark-portfolio-template-jekyll.git your-site-name
```


### 2. Navigate to the directory

```
cd your-site-name
```

### 3. Install dependencies

```
gem install jekyll
```

### 4. Test run the site

```
jekyll serve 
```
To debug if there's a deploy error
```
jekyll serve --trace
```

### 5. Edit `config.yml`

```
Title: "This becomes your main title"
Tagline: "This is the subtitle"
```

```
Logo: Your favicon
```

### 6. Update your content in `index.html`
All of it is hardcoded in. You will find sections flagged by:

`<!-- In these arrows --> `

Images are found in the folder `assets/w3images`.


`_layouts/main.html` is the layout generating the index page
`_includes/head.html` is formatting, SEO, and styling
`_includes/nav.html` is the navigation bar

---

## Improvements to create a blog

The [11ty version of the Dark Portfolio theme](https://github.com/jmschrack/Dark-Portfolio-Template-11ty/blob/dev/README.md) was based off of the [Eleventy Base Blog](https://github.com/11ty/eleventy-base-blog), which means that the index page added those components into the layout.

The index sections such as the "About" and "Gallery" could be created as pages or posts and slotted in. If you have time to make these improvements, please feel free to do so and make a pull request.


You can take a look at the Eleventy blog for some inspiration on how to set up the blog and archive features. However, it is probably just as quick to take another Jekyll theme and build out the features using that.
