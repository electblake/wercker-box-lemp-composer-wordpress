# Box-LEMP-WordPress
A [Wercker][wercker] box for WordPress development on the LEMP stack.

Based on channeleaton/box-lemp-wordpress@0.0.8

## What's inside?
This box comes with almost everything you need to test and deploy your WordPress theme or plugin.

- [Nginx][nginx]
- [Composer][composer]
- [Node][node]
- [NPM][npm]
- [Grunt][grunt]
- [Bower][bower]
- [WP-CLI][wp-cli]

## How to use
WordPress is installed in `/srv/www/wordpress`. In your project's `wercker.yml`, copy your project files to the proper location.

## License
As with everything good in WordPress, GPL2.

[wercker]: http://wercker.com
[nginx]: http://wiki.nginx.org/Main
[composer]: https://getcomposer.org/
[node]: http://nodejs.org/
[npm]: https://www.npmjs.org/
[grunt]: http://gruntjs.com/
[bower]: http://bower.io/
[wp-cli]: http://wp-cli.org/