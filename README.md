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

**GOOGLE_CUSTOM_SEARCH:**

```python
GOOGLE_CUSTOM_SEARCH = "your google custom search Id"
```

**SITEAUTHORS:**

```python
SITEAUTHORS = {
  'the author name': {
    'image': 'the author image',
    'description': 'the author profile'
  }
}
```

**SITECATEGORIES:**

```python
SITECATEGORIES =
  'the category name': {
    'image': 'the category image',
  }
}
```

**SITEFAVICON:**

```python
SITEFAVICON = 'your favicon.ico path'
```

**SITECOVER:**

```python
SITECOVER = 'your cover image path'
```

**THEME_MENUITEMS:**

```python
THEME_MENUITEMS = (
  ('Home', '#', 'fas fa-home')
)
```

**THEME_SOCIAL:**

```python
THEME_SOCIAL = (
    ('Github', 'https://github.com/hansliu', 'fab fa-github-square fa-2x')
)
```

**INTERNAL_LINKS:**

```python
INTERNAL_LINKS = (
    ('Terms', 'pages/tos.html'),
    ('Privacy', 'pages/privacy.html')
)
```

### Theme-specific Article Variables

**cover:**

Cover use for display article in various places.

```
:cover: https://hansliu.com/theme/images/cover.png
```

```
Cover: https://hansliu.com/theme/images/cover.png
```

## Contributing

All kinds of contributions (enhancements, features, documentation & code improvements, bugs reporting) are welcome.

## License

pelican-temp is released under the terms of the [GNU General Public License v3.0](https://github.com/hansliu/pelican-stirring/blob/master/LICENSE)
