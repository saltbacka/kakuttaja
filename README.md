# Kakuttaja

Drop in caching and compressing script to your assets folder.

## Features

- Caches files automatically
- Minifies CSS, JS and HTML files automatically

## TODO

- SASS/LESS pre-processing
- More image compression methods
- On-demand image resizing and cropping

## Instructions

### Set up

Copy `index.php` and `.htaccess` files to your assets folder.

### Configuring

You can see some configuration options in `index.php` file.

### Usage

Load assets and resources the way you did before and files are cached automatically.

You can compress images by adding a query string argument to the URL. Example: `https://example.com/assets/img/example.jpg**?10**`. Quality values can be from 1 to 100. 1 being lowest and 100 highest quality.

See [example/](example/) for more details.
