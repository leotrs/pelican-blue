# Pelican-Blue

Responsive theme for [Pelican](http://blog.getpelican.com/) Static Site
Generator.

## Demo

You can see the theme in action at https://leotorr.es

## Features

* Responsive (Mobile Friendly Test on
  [Google](https://www.google.com/webmasters/tools/mobile-friendly/?url=https%3A%2F%2Fparbhatpuri.com%2F))
* Fast (Load time tested on
  [Pingdom](http://tools.pingdom.com/fpt/#!/bT0Pry/https://parbhatpuri.com/):
  540ms)
* Syntax highlighting for code blocks
* [Disqus](https://disqus.com/) for Comments
* Google Analytics
* RSS/ATOM feeds
* Easy to install

## Installation

You can install Pelican-Blue theme to your earlier Pelican project or
create a new project from the Pelican
[Quickstart](http://docs.getpelican.com/en/3.6.3/quickstart.html) guide.

* Clone the repository

```
$ git clone https://github.com/leotrs/pelican-blue.git
```

* Create a `THEME` variable in your `pelicanconf.py` file and set its value
  to the location of pelican-blue theme.

```python
THEME = 'path-to-pelican-blue-theme'
```

* Add the following code to your `pelicanconf.py` file to display the
  social icons.

```python
SOCIAL = (('linkedin', 'https://www.linkedin.com/in/username'),
          ('github', 'https://github.com/username'),
          ('twitter', 'https://twitter.com/username'))
```

## Contributing

Your contributions are welcome to improve the `pelican-blue` theme.
