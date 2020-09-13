# Stirring

Stirring is a theme for Pelican, it's inspired by the Pelican's theme [Fresh](https://github.com/jsliang/pelican-fresh), Hexo's theme [Tranquilpeak](https://github.com/LouisBarranqueiro/hexo-theme-tranquilpeak), and [Medium](https://medium.com/).

Check out live demo for the Stirring theme [here](https://hansliu.com/pelican-stirring-demo).

## Summary

- [Features](#features)
- [Settings](#settings)
- [Contributing](#contributing)
- [License](#license)

## Features

**General features:**

- Fully responsive
- Customizable favicon icon 
- Customizable background image
- Navigation menu
- Customizable menu icon
- Customizable category image
- Customizable social icon
- Image lightbox gallery
- Image lazyload
- Pagination

**Integrated services:**

- Google Analytics
- Google Custom Search Engine
- Disqus 

**Integrated plugins:**

- [Related Posts](https://github.com/pelican-plugins/related-posts)

**Depended libraries:**

- [Bootstrap 4.5](https://getbootstrap.com/)
- [Font Awesome 5](https://fontawesome.com/)
- [jQuery 3.5.1](https://github.com/jquery/jquery)
- [Magnific Popup](https://github.com/dimsemenov/Magnific-Popup)
- [Lazy Load](https://github.com/tuupola/lazyload)

## Settings

### Built-in Global Variables

- DISQUS_SITENAME
- GOOGLE_ANALYTICS

### Theme-specific Global Variables

**GOOGLE_CUSTOM_SEARCH: **

```python
GOOGLE_CUSTOM_SEARCH = "your google custom search Id"
```

**SITEAUTHORS:**

```python
SITEAUTHORS = {
  'author name': {
    'image': 'your image',
    'description': 'your profile'
  }
}
```

- SITECATEGORIES
- SITEFAVICON
- SITECOVER
- THEME_MENUITEMS
- THEME_SOCIAL
- INTERNAL_LINKS

### Theme-specific Article Variables

- cover

## Contributing

All kinds of contributions (enhancements, features, documentation & code improvements, bugs reporting) are welcome.

## License

pelican-temp is released under the terms of the [GNU General Public License v3.0](https://github.com/hansliu/pelican-stirring/blob/master/LICENSE)
