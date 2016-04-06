# WooCommerce SCSS

WooCommerce styles for use in [Alpha](https://github.com/wpsitecare/alpha), [Foxtrot](https://github.com/wpsitecare/foxtrot), and any other Sassy WordPress theme.

__Contributors:__ [Ozzy Rodriguez](https://github.com/ozzyrod), [Robert Neu](https://github.com/robneu)  
__Requires:__ WordPress 4.5, WooCommerce 2.5.2  
__Tested up to:__ WordPress 4.5, WooCommerce 2.5.2  
__License:__ [MIT](http://wpsitecare.mit-license.org/)  

### Usage

The easiest way to use these styles is to clone them into your theme and integrate them into your build process. They will work out of the box with the [Alpha](https://github.com/wpsitecare/alpha) and [Foxtrot](https://github.com/wpsitecare/foxtrot) starter themes as they share the same variable and dependency structure.

You may need to make adjustments if you want to use the styles in another theme. Please feel free to fork and adapt these styles to meet your own needs!

Because this replaces all of the default WooCommerce styles, you'll probably want to force the plugin's styles to be disabled programmatically rather than allow the user to make the choice from the admin. To do this, simply add the following to your theme's global functions:

`add_filter( 'woocommerce_enqueue_styles', '__return_empty_array' );`

### Requirements

- [Susy](http://susy.oddbird.net/)
- [Sass MediaQueries](https://github.com/paranoida/sass-mediaqueries)
