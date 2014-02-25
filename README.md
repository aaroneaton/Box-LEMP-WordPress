# Box-LEMP-WordPress
A [Wercker][wercker] box for WordPress development on the LEMP stack.

## What's new?
- This README

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

## Changelog
### 0.0.3
- This README

### 0.0.2
- Cleaned up the provisioning script
- Changed from a `service` to `main` box.

### 0.0.1
- Finally got this thing to deploy

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